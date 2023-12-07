# Verbs

<code>ELMER: Complete</code>

Ensure that your verbs are clear and concise, matching the appropriate mood, person, tense, and voice for effective communication.

## General guidelines

Keep verbs clear and concise:
- Avoid using words that primarily function as verbs as nouns or adjectives. Verbs commonly misused as nouns or adjectives include *configure*, *compile*, *debug*, *fix*, and *install*.  
  **Examples (incorrect) ❌**
    - after the compile
    - during the install
    - the debug function

  **Examples (correct) ✅**
    - after the compilation
    - during the installation
    - the debugging function

- Avoid using a phrasal verb (a verb and a preposition) if the verb alone conveys the same meaning.  
  **Examples (incorrect) ❌**
    - call up
    - click on
    - print out
    - start up

  **Examples (correct) ✅**
    - call
    - click
    - print
    - start


- Do not omit the verb from the second coordinate clause when constructing a sentence that contains two coordinate clauses.    
  **Examples (incorrect) ❌**
    - The file names are displayed in uppercase characters and the other file attributes in lowercase characters.

  **Examples (correct) ✅**
    - The file names are displayed in uppercase characters, and the other file attributes are displayed in lowercase characters.

- When you use a verb phrase at the beginning of a sentence with a present participle, such as *creating*, or a past participle, such as *created*, make sure the verb phrase modifies the correct word. Failure to do so results in a dangling modifier.  
  **Examples (incorrect) ❌**
    - Having configured your environment, the program is ready to be used.
    - Cleared of the corrupted data, you can now repopulate the repository.

  **Examples (correct) ✅**
    - After you configure your environment, you can use the program.
    - After you clear the corrupted data, you can repopulate the repository.


## Mood

Use the appropriate mood for the information type:
- Use the imperative mood for requests or instructions, such as in procedures.  
  **Examples**
    - Enter your username and password to log in to the system.
    - Please ensure that all fields are filled out before submitting the form.

- Use the indicative mood to specify information, such as facts and explanations.  
  **Examples**
    - JavaScript is a programming language commonly used for front-end web development.
    - The error message indicates a problem with the network connection.

- Do not use the subjunctive mood in technical information.  
  **Examples (incorrect) ❌**
    - If you were to save the file ...
    - It is important that the file be saved ...

  **Examples (correct) ✅**
    - If you save the file ...
    - **Important:** Save the file ...


## Person

Use the appropriate person for the information type.

### First person

Refrain from utilizing first-person pronouns such as *I* and *we*. First-person language directs the focus onto the writer rather than the reader or the information being conveyed. Additionally, the first person may create an overly informal tone.

**Examples (incorrect) ❌**

- I enjoy the challenge of learning and using different Linux distributions.
- We can create a database diagram based on the data dictionary we drafted earlier.
- Let's begin the refactoring of our JavaScript SDK.

**Examples (correct) ✅**
- The challenge of learning and using different Linux distributions is enjoyable.
- You can create a database diagram based on your previously drafted data dictionary.
- Commence the refactoring of the JavaScript SDK.

The use of the first person is acceptable in these situations:
- In the question portion of frequently asked questions (FAQs)
- In articles, white papers, or documents that have listed authors and in which the authors describe their own actions and opinions

**Examples (incorrect) ❌**
- **Q:** How does one change the properties of a class?
- Tests were conducted on servers in three different environments.

**Examples (correct) ✅**
- **Q:** How do I change the properties of a class?
- We conducted tests on servers in three different environments.

### Second person

Employ the second person, indicated by the personal pronoun *you*, whenever feasible. The second person directly addresses the reader.

**Examples**
- To ensure data integrity, you should regularly back up your database.

When providing instructions for user actions, utilize the imperative mood. Imperative sentences imply the subject as the user, typically understood as *you*.

**Examples**
- Save the document before closing the application.
- To save your changes, press Ctrl+S (Windows) or Command+S (macOS).

### Third person

Use the third person to describe concepts, facts, and results. The third person focuses on the information being presented. Most often, technical information is about things rather than people. Therefore, the third person is indicated by nouns and third-person pronouns such as *it* and *they*. When you use the third person, do not use gender-specific pronouns, such as *he* and *she*, unless the context requires them.

**Examples**
- John created his books using desktop publishing software.
- The application calculates the metrics based on the user inputs.
- Document the steps taken for future reference.

## Tense
Write in the simple present tense as much as possible.

**Example (incorrect) ❌**
- When you click Exit, the current application will terminate.

**Example (correct) ✅**
- When you click Exit, the current application terminates.


Use past or future tense only when you cannot use present tense, or it does not make sense to use present tense.

**Example (incorrect) ❌**
- If you selected **New** in the previous window, the current window will display the recommended default values.
- Cancel a broker deployment only if you are sure that the broker never responds to the deployment request.

**Example (correct) ✅**
- If you selected **New** in the previous window, the current window displays the recommended default values.
- Cancel a broker deployment only if you are sure that the broker will never respond to the deployment request.

## Voice

Use active voice as much as possible. Active voice focuses on the performer of the action and is often clearer, shorter, and more direct than passive voice.

**Examples of passive voice and active voice**
  - **Passive:** The built-in Settings application is used to configure phone-related customizations and behavior.
  - **Active:** You configure phone-related customizations and behavior using the built-in Settings application.
  <br><br>
  - **Passive:** The update was installed by the system administrator.
  - **Active:** The system administrator installed the update, optimizing system performance.

Passive voice is acceptable when any of these conditions are true:
- The system performs the action.
- It is more appropriate to focus on the receiver of the action.
- You want to avoid blaming the user for an error, such as in an error message.
- The information is clearer in the passive voice.
- Specific information types, such as glossary definitions, require passive voice.

**Examples of appropriate use of passive voice**
- The web page is updated when you click Refresh.
- When you use the **recover** command, any lost data is recovered.
- <pre>Error: An incorrect date range was entered.</pre>
