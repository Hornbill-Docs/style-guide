# Notes and notices

<code>ELMER: Complete</code>

Notes and notice elements are special sections used to highlight important information in a way that distinguishes it from the rest of the text. Depending on your authoring or documentation tool, these elements are often styled as colored blocks or rectangles. They may include icons to indicate the type and importance of the information visually.

Regardless of their style, use notes and notices to provide readers with necessary or helpful information separate from the main text flow. If you need help deciding whether to use a note or notice, write the content first as regular text. Then, assess if converting it into one would enhance its effectiveness or importance.

Exercise discretion when incorporating notes and notices. Excessive use of notes can diminish their impact and significance. Employ the appropriate type of notice to signal potential risks of damage or injury, ensuring that the urgency and importance are accurately conveyed to the reader.

## Notes

To effectively highlight essential hints, tips, guidance, restrictions, or advice in documentation, use a descriptive label like **Exception**, **Fast Path**, **Important**, **Remember**, **Requirement**, **Restriction**, or **Tip**. Ensure the label and the following colon are in bold for emphasis.

**Tip:** Avoid using the **Recommendation** label if possible to avoid creating a potential marketing or legal problem.

**Examples**

- **Exception:** Users with read-only access cannot execute the batch processing feature.
- **Fast Path:** To quickly access system logs, use the shortcut `Ctrl+L` in the main dashboard.
- **Important:** Always back up your database before performing a major update to avoid data loss.
- **Remember:** The number of concurrent users may impact the application's performance.
- **Requirement:** Installation requires a minimum of 4 GB RAM and 20 GB free disk space.
- **Restriction:** The API does not support concurrent calls from the same user session.
- **Tip:** Use the built-in code templates for standard functions to save time during development.

Avoid breaking up a paragraph with a note. Notes should be distinct and not inlined within other text. Keep note text unindented and ensure its use does not disrupt the layout of adjacent text.

When multiple notes are grouped, label them collectively on a separate line and organize them in a suitable list format. Use the plural version of the label if possible.

**Examples**

- **Important:**
  - Ensure the server has the latest security updates before deployment.
  - Validate all user inputs to prevent security vulnerabilities.

- **Restrictions:**
  - The software does not support versions earlier than 10.0.
  - Modification of core system files will void the warranty.

- **Tips:**
  1. Utilize keyboard shortcuts in the development environment to enhance coding efficiency.
  2. Regularly commit changes to your version control system to safeguard your work and track progress.

<br>

If a note extends beyond a single paragraph, restructure the content into a subsection with a heading rather than maintaining it as a multi-paragraph note. Lengthy notes can be challenging to distinguish from regular text, making them less effective and potentially confusing.

## Notices

Use specific headings for notices highlighting the potential risk of harm to hardware, software, data, or physical safety.

### Attention notices

Use an Attention notice to signal potential damage to programs, devices, systems, or data. Start an Attention notice with the bolded label **Attention**, followed by a colon, and then the notice text on the same line. Ensure the Attention notice is an independent paragraph with spacing above and below. In procedures, position the Attention notice *before* the step where the risk occurs.

**Example**

1. Power down the system completely.
2. Disconnect the system from the electrical outlet.

**Attention:** Ensure that all power sources are disconnected before proceeding. Failure to do so may result in electrical shock or damage to the system.

3. Open the system chassis for maintenance.

**Example**

**Attention:** Regularly update your antivirus software. Neglecting to update can leave your system vulnerable to new viruses and security threats.

<br>

To ensure clarity and compliance with international standards, avoid using the term *warning* in an Attention notice, both as the label and within the text of the notice. The term *warning* is reserved for safety-related notices concerning potential physical harm to individuals in certain countries. Restrict your safety-related communications to labels such as CAUTION or DANGER.

### CAUTION notices

Use a CAUTION notice to highlight situations that may pose a hazard to individuals due to existing conditions or potential risks arising from unsafe practices. An instance requiring a CAUTION notice could alert readers to exercise caution when handling heavy equipment.

Format the **CAUTION** label in bold and uppercase on a separate line, followed by a colon. If your authoring tool does not automatically bold the notice text, do so manually. Present each CAUTION notice as a distinct paragraph, ensuring there is space above and below it. In procedural documentation, position the CAUTION notice *before* the relevant step where the hazard may occur.

**Important:** Always consult your company's Safety department before using a CAUTION notice.

**Example 1**

1. Ensure the server is powered down and disconnected from all power sources.
2. Locate the server rack that requires maintenance.

**CAUTION: When opening the server chassis for maintenance, static electricity can cause severe damage to internal components. Always use an anti-static wrist strap or other grounding devices to prevent electrostatic discharge.**

3. Attach your anti-static wrist strap and open the server chassis for maintenance.

**Example 2**

1. Access the database configuration interface.
2. Select the file that requires modification.

**CAUTION: Direct modification of the database configuration files can render the system inoperable if not done correctly. Ensure you are familiar with the correct procedures and have verified the changes with a senior database administrator before proceeding.**

3. Carefully make the required changes to the database configuration as instructed, ensuring to double-check all entries.

### DANGER notices

Use a DANGER notice to highlight situations with the potential for causing lethal harm or extreme danger to individuals. For instance, exposed high-voltage wires in a computer with its side panel removed could be deadly.

Apply the DANGER notice judiciously, reserving it for instances where severe injury or loss of life is a real possibility without extreme caution.

Format the **DANGER** label in bold, uppercase letters on a separate line. Encase each DANGER notice within a box if your authoring tool supports it. If your authoring tool doesn't automatically apply bold formatting to the notice text, do so manually. In procedural documentation, position the DANGER notice *before* the step where the lethal risk is present.

**Important:** Always consult your company's Safety department before using a DANGER notice.

**Example**

1. Locate the power supply unit within the computer chassis.
2. Ensure the computer is disconnected from any external power source.

---

**DANGER**

**Exposed high-voltage components within the power supply unit can cause fatal electrical shock. Do not proceed with servicing internal components unless you are a qualified technician with appropriate training. Ensure the power supply unit is discharged before handling.**

---

3. If qualified, proceed to service the internal components as necessary, adhering to all safety protocols.
