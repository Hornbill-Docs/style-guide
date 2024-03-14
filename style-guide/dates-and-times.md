# Dates and times

<code>ELMER: Complete</code>

Maintain uniformity in writing dates and times, ensuring they are expressed in a manner that is understandable internationally.

## Dates

To prevent misunderstandings regarding dates, refrain from using solely numeric formats in text. For example, *12/1/2007* is interpreted as *December 1, 2007* in the United States but as *January 12, 2007* in numerous other countries. For this reason, using words to express dates is recommended.

Adhere to the following guidelines when expressing dates:

- If including the day of the week, add it before the month as follows: `DAY_OF_WEEK, MONTH DAY, YEAR`. Take note of the placement of the commas as shown in the format.
- Spell out the names of months and days of the week in full. Give the full four-digit year, not a two-digit abbreviation.
- Do not use a forward slash (/) or hyphen (-) in dates, nor the abbreviations *st*, *nd*, *rd*, and *th*.
- Write out century names in full.

**Examples (incorrect) ❌**
- 11/6/2015
- 6-11-2015
- The 8th of August, 2008
- August 8th, 2008
- 2 March 1999
- 2nd March 1999
- March 2nd, 1999
- Thursday July 30th, 2010
- 21st century

**Examples (correct) ✅**
- November 6, 2015
- August 8, 2008
- March 2, 1999
- Thursday, July 30, 2010
- twenty-first century

### Partial dates and abbreviations

Omit the comma between the month and year when referencing a specific month and year together.

**Example (incorrect) ❌**
- September, 2008

**Example (correct) ✅**
- September 2008

Generally, avoid abbreviating days of the week and months. However, abbreviations to their three-letter forms are permissible for space-saving purposes, such as in headings or tables. Ensure the abbreviation's first letter is capitalized and omit periods at the end.

When abbreviating dates, apply abbreviations consistently across the entire date. Avoid combining full written-out forms with abbreviated forms within the same date expression.

Ensure uniform application of abbreviations throughout your documentation. For instance, if abbreviations are used within table cells, maintain this practice across all cells for consistency.

**Example (incorrect) ❌**
- Mon, April 6, 2015

**Example (correct) ✅**
- Mon, Apr 6, 2015

### Leading zeros

Avoid adding a leading zero to single-digit dates unless it is necessary for aligning dates in a list or table, or if it is required to accurately represent a date format, such as in a date field, or when providing an example of such formatting.

**Examples (incorrect) ❌**
- The software update was released on May 05, 2020.
- Our data center commenced operations on September 09, 2015.

**Examples (correct) ✅**
- The software update was released on May 5, 2020.
- Our data center commenced operations on September 9, 2015.
- For scheduling the installation, enter `07Oct21` in the setup wizard.
- The device's release date entered in the system log is `03Mar18`.

### Date ranges

To convey a span of dates, adopt one of these approaches:

- Employ the terms *from* and *through* for clarity in expression. Avoid using *to* and *between* when indicating date ranges.
- When indicating a date range in an abbreviated format, such as within a table, utilize a hyphen flanked by spaces on either side ( - ). This abbreviation method should not be applied within continuous text, and mixing the textual and abbreviated forms within the same context should be avoided.

**Examples (incorrect) ❌**
- 9-15 June 2010
- June-September 2010
- between June 2010 and January 2011
- from 6 October - 12 October 2007
- from 6Jun2010-12Jun2011

**Examples (correct) ✅**
- June 9 - 15, 2010
- June - September 2010 *or* from June through September 2010
- from June 2010 through January 2011
- from October 6 through October 12, 2007
- Jun 6, 2010 - Jun 12, 2011

### Dates in the middle of a sentence

If a `MONTH DAY, YEAR` date format is used within a sentence, insert a comma following the year.

**Example**
- The November 8, 2005, release of ...

Conversely, should the date within a sentence include only the month and year, refrain from adding a comma.

**Example**
- The November 2005 release of ...

### Numeric-only date format

When expressing dates in numerical format, adhere to the `YYYY-MM-DD` structure, separating each element with hyphens in alignment with [ISO 8601 international standards](https://wikipedia.org/wiki/ISO_8601) for numerical date representation.

Furthermore, when selecting a date for hypothetical or illustrative purposes, opt for a calendar day exceeding 12. This practice helps clearly distinguish the day from the month.

**Example (incorrect) ❌**
- 07/09/2017

**Example (correct) ✅**
- 2017-07-22

### Express dates and times together

When it is necessary to convey both a date and a time, present the date first, followed by the time.

**Examples**
- 2020-02-14 at 11 a.m.
- July 9, 2012, at 4 p.m.

## Times

Use the 12-hour or 24-hour system as appropriate, but do not mix the two systems in the same document. If you want to include seconds in times, use the 24-hour system.

### Using the 12-hour system

When indicating times of the day in the 12-hour format, separate hours and minutes with colons without spaces before or after the colon. Employ lowercase letters with periods for *a.m.* and *p.m.*, and ensure a space follows the time figures.

Do not use *o'clock* to refer to a whole hour.

To denote a range of times, use *to* instead of *through*. In tables or lists that require clarity in presentation, a hyphen surrounded by spaces may be used to express ranges. Include  *a.m.* and *p.m.* in both range parts.

Avoid leading zeros for times on the hour unless within a list or range where at least one time includes minutes, necessitating consistency in presentation.

**Examples (incorrect) ❌**
- Breakfast starts at 6am.
- The symposium will start at 1 o’clock in the afternoon.
- The coffee break will be from 2 to 2:30 p.m.
- Lectures will be at the following times:
  - 11a.m.-12:30p.m.
  - 4-5:15p.m.
  - 3:30-4:30p.m.

**Examples (correct) ✅**
- Breakfast starts at 6 a.m.
- The symposium will start at 1 p.m.
- The coffee break will be from 2:00 p.m. to 2:30 p.m.
- Lectures will be at the following times:
  - 11:00 a.m. - 12:30 p.m.
  - 4:00 p.m. - 5:15 p.m.
  - 3:30 p.m. - 4:30 p.m.

<br>

Use *midnight* and *noon* (instead of *a.m.* and *p.m.*) to indicate those hours.

**Examples**
- Lunch will be provided at noon sharp.
- There will be a break from 12 noon to 1 p.m.
- The server maintenance starts at midnight.
- The webinar is scheduled to begin at noon and end at midnight.

### Using the 24-hour system

When representing times of the day using the 24-hour system, employ colons to delineate hours, minutes, and seconds, ensuring no spaces are placed before or after the colon.

Avoid depicting seconds alongside whole hours unless the presentation of other times includes seconds or if the seconds are significant.

Ensure that hours, minutes, and seconds are each presented with two digits. Fractions of a second may be added after a decimal separator, detailed to a necessary level of precision.

**Examples**
- The system update is scheduled between 23:00 and 01:30, minimizing downtime during peak hours.
- The server unexpectedly went offline at 18:45, prompting an immediate investigation.
- Precise timestamp data showed that the transaction was processed at 09:05:30.
- The cron job was completed at 14:12:20.254.

### Expressing time zones

Minimize the use of time zones unless they are essential. When the inclusion of a time zone is necessary, such as for describing actual events occurring at specific times, adhere to the following guidelines:

- Inform the reader that the time is based on their local time zone, such as *11 a.m. your local time*.
- When a time zone is required, utilize the timestamp format as it appears in the user interface, when applicable.
- When specifying a particular time zone, fully spell out the region and add the UTC or GMT designation in parentheses. For instance:
  - US and Canadian Pacific Standard Time (UTC-8)
  - US and Canadian Pacific Daylight Time (UTC-7)
- Do not abbreviate the name of the time zone.
- On the uncommon occasion where the time of an event remains unaffected by daylight saving time adjustments, specify the particular time zone without referencing Coordinated Universal Time (UTC).

**Examples**
- Join our live webinar at 11 a.m. your local time to learn more about our latest software update.
- The system logs display timestamps in our application interface, such as 2023-03-15 14:30 (GMT+1).
- The global team meeting is scheduled for Eastern Standard Time (UTC-5) during winter.
- Our servers will undergo maintenance starting at Central European Summer Time (UTC+2) to minimize downtime across regions.
- Please note that the time for the quarterly financial review, Arizona Mountain Standard Time, does not shift with daylight saving changes, unlike other US time zones.

## Express divisions of the year

Avoid mentioning seasons when referencing times and dates. Spring in the northern hemisphere coincides with fall (autumn) in the southern hemisphere. For clarity and global relevance, prefer specifying the month, quarter, or temperature (when applicable).

**Examples (incorrect) ❌**
- Our new product will launch in spring 2023.
- Expect cooler temperatures starting in fall.
- The software update is scheduled for winter of this year.

**Examples (correct) ✅**
- Our new product will launch in March 2023.
- Expect cooler temperatures starting in October.
- The software update is scheduled for December of this year.
