# Text formatting summary

<code>ELMER: Work In Progress</code>

At Hornbill, we understand the importance of clear and effective text formatting in improving the readability and emphasis of our documentation. This document is a quick reference, outlining when and how to apply bold, italic, code font, and other formatting styles to communicate our content precisely and clearly.

**Note:** For documentation maintenance, this document does not provide examples of text formatting. Instead, we have provided links to various topics within our style guide, where these text formatting styles are applied.

## Bold

Apply bold formatting when dealing with UI elements, terms in a definition list, notes, and notices.

Labels used to introduce examples, such as *Example* or *Examples* must be in bold. If the examples are in text, and some of their contents require bold formatting, then do so.

When using HTML, use the `<b>` tag instead of the `<strong>` tag. The former is appropriate for purely text styling and visual presentation.

When using Markdown, use `**` instead of `__` (double underscores) for bold formatting. The `**` syntax is recognizable in a text editor.

For more information and examples of the bold formatting of specific text elements, see the following:
- "[Definition lists](/style-guide/lists#definition-lists)"
- "[Notes and notices](/style-guide/notes-and-notices)"

## Italic

Use italics to emphasize a word or phrase that needs to stand out for conceptual or contextual reasons. For example, italics may be used to highlight an essential term in a given context or to distinguish a word used in an unconventional or ironic sense.

When introducing a new concept, term, or abbreviation the reader might not be familiar with, use italics on its first occurrence. Doing so signals to the reader that the term is significant and defined within the document.

Use italics for the titles of books, reports, websites, and other standalone works to distinguish them from the rest of the text.

Use italics using the `<i>` tag in HTML documents. In Markdown, italicize text by enclosing it with a single asterisk `*`.

**Remember:** Reserve italics for specific instances outlined above to maintain their impact. Overuse of italics can make the text difficult to read and reduce the emphasis intended.

For examples of italicization, see the following:

- "[Words as words](/style-guide/words-as-words)"
- "[Pluralize a single letter](/style-guide/letters-as-letters)"
- "[Key terms](/style-guide/key-terms)"
- "[Quotation marks for emphasis](/style-guide/quotation-marks#quotation-marks-for-emphasis)"

## Underline

In general, do not underline.

The following are the only instances where you need to underline:

- When documenting a *command* that has a default parameter value
- When showing the relationship between terms in a glossary

<code>ELMER: TODO: Add links to the respective topics</code>

For more examples, see the following:
- Using text to specify command syntax
- Relationships between terms in a glossary

## Code font

Use the `<code>` tag in HTML or the backtick <code>`</code> in Markdown to implement a monospace font and additional styling for code within text, inline code, and user input.

Use code blocks, denoted by `<pre>` in HTML or triple backticks <code>```</code> in Markdown, for presenting code samples or extensive segments of code.

Avoid altering or customizing font styles directly within the text.

<code>ELMER: TODO: Add a link to the text below</code>

Apply code font styling to denote code elements, including filenames, class names, method names, HTTP status codes, console output, and placeholders. For further details, see  "[Some specific items to put in code font]()."

## Capitalization

Use sentence-style capitalization for headings, titles, table elements, and figure captions. For detailed information and examples, see "[Capitalization](/style-guide/capitalization)."

## Quotation marks

Use quotation marks appropriately.

Use double quotation marks for quotations, references to topic titles or online information, and words used in a special sense.

Use single quotation marks when writing hexadecimal numbers and for code syntax and programming elements that require them.

Avoid using quotation marks to emphasize words or phrases. Use italic formatting instead. For more information and examples, see "[Quotation marks](/style-guide/quotation-marks)."

## Other punctuation guidelines

Avoid using ampersands (&) as conjunctions or as a shorthand for *and*. Instead, utilize *and*. This rule applies to headings and navigation as well.

**Exception:** The use of *&* is allowed when referring to a user interface element or the name of a menu that includes *&*.

Place quotation marks and ending punctuation outside of the link text.
