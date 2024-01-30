# Lists

<code>ELMER: Complete</code>

Use vertical lists to visually organize a lengthy series at the end of a sentence or within a series of parallel sentences or paragraphs.

Lists enhance readability and translatability, provided they are concise. Refrain from using in-sentence enumerations in technical content. Be cautious with the frequency of list usage; too many lists mixed with short introductory sentences may appear to be an outline rather than a complete document.

## Unordered lists

Use an unordered (bulleted) list when the order of items does not matter. Organize items within these lists logically. If a logical arrangement is not apparent, sort them alphabetically. When grouping items in a non-intuitive manner, explain your grouping criteria briefly. In relevant cases, especially in hardware or software lists, prioritize your company's products at the beginning of the list.

**Example**

The marketing team emphasizes the following features of the software:
- Advanced security measures
- Efficient data management
- Customizable settings
- Real-time analytics

## Ordered lists

Use an ordered (numbered) list when the order of the items is crucial, such as in procedural documentation or when ranking items. When listing rules or similar information, their numerical position allows for easy reference; for instance, the first item in a list of rules is inherently referred to as Rule 1. For detailed guidance on composing procedural steps, see "[Procedures](/style-guide/procedures)."

**Example**

Adhere to the following rules for safe laboratory conduct:

1. Always wear protective gear, including lab coats and safety goggles.
2. Never eat or drink in the laboratory.
3. Label all chemicals and solutions clearly.
4. Dispose of hazardous waste properly.

## Definition lists

Use definition (or term) lists to describe terms or explain concepts. Emphasize the term or descriptive name in bold unless specific coding requirements of your library or tool dictate otherwise, such as using italics for message variables, program keywords, or program variables. Conclude each definition with a period.

Ensure clear visual distinction between terms or descriptive names and their corresponding definitions. Begin each term or descriptive name with a capital letter, except when standard usage dictates lowercase, as in examples like *num_circles* or *prodname*. Also, capitalize the first word of each definition.

Refrain from employing unordered lists with bold formatting, as exemplified in the incorrect example. Opt instead for a definition list. This list can be formatted in one of three ways, as demonstrated in the subsequent correct examples. In the first correct example, the term being defined appears as the inaugural word of a defining sentence. In the second apt example, the term defined is not integrated into the defining sentence. The third suitable example presents the definition as a fragment, akin to a glossary style. Maintain consistency in your approach to composing definition lists and avoid intermixing these three styles.

**Example (incorrect) ❌**

The following data types are commonly used in programming:

- **Integer** represents whole numbers without a fractional component.
- **Float** is used for numbers that include a fractional part.
- **String** denotes a sequence of characters typically used for text.
- **Boolean** indicates a true or false value.
- **Array** refers to a collection of elements, often of the same data type.

**Example 1 (correct) ✅**

When the defined term is the first word of a defining sentence.<br><br>

The following data types are commonly used in programming:

**Integer**

Represents whole numbers without a fractional component.

**Float**

Is used for numbers that include a fractional part.

**String**

Denotes a sequence of characters typically used for text.

**Boolean**

Indicates a true or false value.

**Array**

Refers to a collection of elements, often of the same data type.

<br>

**Example 2 (correct) ✅**

When the defined term is not part of the defining sentence.<br><br>

The following data types are commonly used in programming:

**Integer**

Use this type to represent whole numbers without a fractional component.

**Float**

Use this type for numbers that include a fractional part.

**String**

Use this type to represent a sequence of characters typically used for text.

**Boolean**

Use this type to represent a value of true or false.

**Array**

Use this type to represent a  collection of elements, often of the same data type.

<br>

**Example 3 (correct) ✅**

When the definition is a fragment (glossary style).<br><br>

Below is a list of key terms you will encounter in your career as a software developer:

**API**

Application Programming Interface, a set of routines for accessing software applications.

**Git**

A version control system for tracking changes in files and coordinating work.

**SQL**

Structured Query Language, used for managing and querying databases.

## Capitalization in lists

Capitalize the first word of each item in a vertical list.

**Examples**

The software provides compatibility with various file formats:

- High-quality images can be saved in JPEG format.
- Transparent backgrounds are best utilized with PNG files.
- Animated graphics are typically created in the GIF format.
- Uncompressed bitmap images are often stored as BMP files.

<br>

Reset your password in this order:

1. Go to the login page and click on **Forgot Password**.
2. Enter your registered email address.
3. Follow the link sent to your email to set a new password.

## Wording of list items

Ensure that list items maintain grammatical parallelism. For instance, avoid combining different grammatical structures, such as mixing passive voice with active voice or intermingling declarative sentences with imperative ones.

**Example (incorrect) ❌**

To effectively manage a project:

1. Define the project goals and scope.
2. A comprehensive project plan should be developed.
3. You must implement the plan and monitor progress.

**Example (correct) ✅**

To effectively manage a project, follow these steps:

1. Define the project goals and scope.
2. Develop a comprehensive project plan.
3. Implement the plan and monitor progress.

**Example (incorrect) ❌**

The training program offers the following benefits:

- Professional skill enhancement
- It increases job satisfaction.
- It improves career prospects.

**Example (correct) ✅**

The training program offers the following benefits:

- It enhances professional skills.
- It increases job satisfaction.
- It improves career prospects.

**Remember:** To avoid translation problems, use complete sentences or noun phrases for list items.

## Length of lists

Use at least two list items in an ordered list. For unordered lists, a single item is permissible only if it aligns with the format of other unordered lists in the same section.

Limit lists to a maximum of nine items to avoid overwhelming the reader. Consider dividing your content into multiple lists if it requires more than nine items. However, lengthy reference lists organized alphabetically are an exception, as they serve more as a resource for readers to locate specific information rather than for sequential reading.

## Alphabetization and sorting methods of lists

For manually organizing lists without a clear sorting criterion, adopt [letter-by-letter alphabetization](https://cmosshoptalk.com/2016/05/11/sections-16-58-61-in-the-spotlight/). Regarding indexes and glossaries, the sorting is typically managed by the authoring tool rather than the writer.

When alphabetizing items in a list, apart from index entries, utilize the letter-by-letter approach instead of word-by-word. The distinctions between these two methods are illustrated in the example below:

| Letter-by-letter alphabetization<br>(use this method) | Word-by-word alphabetization<br>(do not use this method) |
|---|---|
| form | FOR statement |
| format | form |
| FORMAT statement | format |
| forms control | FORMAT statement |
| FOR statement | forms control |

When an item in a list contains punctuation such as a hyphen, slash, or apostrophe, disregard these punctuation marks and consider the item as one continuous word for alphabetization purposes.

**Example**

The following is a letter-by-letter alphabetization of keywords that contain hyphens:

1. `END-IF` (treated as *endif*)
2. `ENDING` (treated as *ending*)
3. `END_INVOKE` (treated as *endinvoke*)

When sorting a list that includes symbols, numbers, and alphabetic characters, follow this order: symbols first, then numbers, and finally alphabetic characters. Consider providing a spelled-out version for numerical items to accommodate users who may search for the word form. For handling symbols, your writing and editing team should establish specific guidelines on their treatment.

When determining how to sort lists containing symbols, consider these guidelines:

- Treat symbols as if they are spelled out for alphabetization. For instance, *@* might be treated as "at," and *#* as "number."
- Sort the symbols using their ASCII values. In ASCII, symbols generally precede numbers and letters, so they would appear at the beginning of an alphabetized list.
- Ignore symbols and alphabetize the item based on the first letter or number following the symbol.

**Examples**

- Treating symbols as spelled out:
  - @Example (treated as *at Example*)
  - #Example (treated as *number Example*)
  - Example

- Sorting by ASCII values:
  - #Example
  - @Example
  - Example

- Ignoring symbols:
  - @Example
  - #Example
  - Example (the symbols are ignored, so the subsequent text determines the order)

## Punctuation in lists

Construct lists uniformly, ensuring that either all items begin with complete sentences or none do. For lists with only complete sentences, end each item with a period. For lists composed solely of sentence fragments, omit end punctuation.

In lists where items start with sentence fragments followed by complete sentences, punctuate all items, including fragments, with a period.

**Examples (incorrect) ❌**

When configuring network security, consider the following aspects:

- Firewall settings – they control inbound and outbound network traffic based on an applied rule set.
- VPN configurations – this feature ensures secure remote access to the network.
- Encryption protocols – these protocols safeguard data transmission across the network.

<br>

When configuring network security, consider the following aspects:

- Firewall settings. They control inbound and outbound network traffic based on an applied rule set.
- VPN configurations
- Encryption protocols

<br>

**Examples (correct) ✅**

When configuring network security, consider the following aspects:

- Firewall settings. They control inbound and outbound network traffic based on an applied rule set.
- VPN configurations. This feature ensures secure remote access to the network.
- Encryption protocols. These protocols safeguard data transmission across the network.

<br>

When configuring network security, consider the following aspects:

- Firewall settings. They control inbound and outbound network traffic based on an applied rule set.
- VPN configurations.
- Encryption protocols.

<br>

Apply the same punctuation rules to nested lists as standard lists. Punctuate the introductory phrases of nested lists in the same manner as those of primary lists.

**Example**

1. Set up the development environment:<br>
  a. Download the latest version of the Integrated Development Environment (IDE) from the official website.<br>
  b. Install the necessary plugins and extensions for your project.<br>
  c. Configure the IDE settings according to your project requirements.
2. Initialize the version control system.

## Lead-in wording

In most instances, use a complete sentence to introduce a list that is not procedural in nature. Within a task-oriented document, the inclusion of an introductory sentence can be omitted if the list immediately succeeds headings such as "Before you begin," "Prerequisites," "Restrictions," or similar headings. For detailed instructions on presenting a procedure, see "[Procedures](/style-guide/procedures)."

**Translation consideration:** To mitigate potential issues in translation, it is advisable to introduce lists with complete sentences rather than phrases. Since machine translation systems typically operate at the sentence level, providing them with a complete sentence enhances the accuracy and quality of the translated output.

**Exception for marketing content:** For marketing materials, it is permissible to introduce a vertical list with a fragment rather than a complete sentence.

**Example (incorrect) ❌**

Examples of this type of interaction include:

**Example (correct) ✅**

The following statements are examples of this type of interaction:

<br>

When writing a lead-in sentence for a list, end it with a colon unless there's an intervening sentence between the lead-in and the first list item. In cases where an additional sentence is present, conclude both the lead-in and the intervening sentence with a period.

**Example 1**

The system supports the following user authentication methods. Each method offers a different level of security and user experience.

- Password-based authentication requires users to enter a predefined password.
- Biometric authentication uses unique ...
- Two-factor authentication combines ...

**Example 2**

The software performs the following operations during the initial setup:

- Scans the system for compatible hardware components.
- Configures network settings based on detected infrastructure.
- Installs essential drivers and software updates.

**Example 3**

The application supports the following data conversion processes:

- A JSON string to a JavaScript object.
- A JavaScript object to a JSON string.
- A CSV file to an array of objects.
- An array of objects to a CSV file.

**Example 4**

**Prerequisites**

- Verify network connectivity and stability.
- Confirm administrative access to the server.

<br>

You can use an imperative sentence to introduce a numbered list.

**Example**

Reset your password in this order:

1. Go to the login page and click on **Forgot Password**.
2. Enter your registered email address.
3. Follow the link sent to your email to set a new password.

<br>

Do not continue the lead-in sentence after the list; do not use a conjunction at the beginning or end of a list item.

**Example (incorrect) ❌**

In preparing your report, ensure to include:

- An analysis of current market trends, and
- A detailed financial forecast for the next quarter, also
- Insights from customer feedback surveys conducted last month

**Example (correct) ✅**

In preparing your report, ensure to include the following elements:

- Analysis of current market trends
- Detailed financial forecast for the next quarter
- Insights from customer feedback surveys conducted last month

**Example (incorrect) ❌**

For optimal performance of the software, the user should:

- regularly update the application,
- clear the cache memory to improve speed, and
- backup data frequently, as this is crucial.

**Example (correct) ✅**

For optimal performance of the software, the user should perform the following actions:

- Regularly update the application
- Clear the cache memory to improve speed
- Backup data frequently

## Nested lists

When constructing nested lists, whether ordered or unordered, limit the nesting to a maximum of two levels and avoid exceeding three levels under any circumstances. Instead, opt for reorganizing the content for clarity and conciseness. Specifically, adhere strictly to a two-level nesting structure for procedural steps, reformatting the content if necessary.

For nested ordered lists intended for outline presentation, adhere to the specified numbering scheme unless your authoring tool prescribes an alternative format.

- Begin each first-level with an Arabic numeral, followed by a period.
- Begin each second-level item with a lowercase letter, followed by a period.
- If a third-level item is required, begin the item using a numbering scheme that is distinct from that of the first and second levels.

**Example**

1. Power down the server.
2. Upgrade the software:<br>
  a. Download the latest software version.<br>
  b. Run the installation wizard to update the system.<br>
3. Restart the server to apply updates.

When you create nested unordered lists, ensure that the bullet symbol for the first level differs from the bullet symbol for the second level.

**Example**

The system maintenance tasks include:
<ul style="list-style-type: disc;">
  <!-- First level with disc bullets -->
  <li>Data backup procedures
    <ul style="list-style-type: circle;">
      <!-- Second level with circle bullets -->
      <li>Schedule automatic backups</li>
      <li>Define backup storage locations</li>
    </ul>
  </li>
  <li>System updates
    <ul style="list-style-type: circle;">
      <li>Check for software updates</li>
      <li>Apply security patches</li>
    </ul>
  </li>
</ul>
