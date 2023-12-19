# Footnotes

<code>ELMER: Complete</code>

A footnote is a supplementary note placed at the bottom of a page to provide additional information or citations related to the main text. It is typically marked by a superscript number in the text, directing the reader to the corresponding detailed note at the page's footer.

Avoid using footnotes; instead, try to incorporate the necessary information directly into the text using a brief parenthetical phrase or sentence. Also, footnotes are redundant, lessen clarity and accessibility, and present challenges for localization efforts.

Use a footnote solely in instances where integrating additional information directly into the text would disrupt its continuity or flow.

If a footnote is necessary for conveying information, opt for a symbol rather than a number. Follow this sequence for the symbols:

- `*`
- `†` (dagger)
- `‡` (double dagger)
- `#`

Place the footnote symbol at the end of the sentence, clause, word, abbreviation, or specific item it refers to, using a superscript format. For instance, use `<sup>†</sup>` to elevate the symbol above the text's baseline. Place the corresponding footnote content at the bottom of the page where the symbol appears.

**Examples (incorrect) ❌**
- This is an example sentence that has a footnote.<sup>1</sup>

**Examples (correct) ✅**
- This is an example sentence that has a footnote.<sup>\*</sup>

  <sup>\*</sup> This footnote is at the bottom of the page.

## Footnotes in tables

If your authoring tool supports footnotes in a table, include the footnote text in the last row of the table.

**Example**

<table>
  <thead>
    <tr>
      <td colspan="4" align="center"><strong>Table 1</strong> Device Specifications</td>
    </tr>
    <tr>
      <th>Model</th>
      <th>Height (cm)</th>
      <th>Depth (cm)</th>
      <th>Width (cm)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>AlphaPro X1</td>
      <td>15.2</td>
      <td>0.8</td>
      <td>7.6</td>
    </tr>
    <tr>
      <td>BetaMax Z3<sup>*</sup></td>
      <td>14.5</td>
      <td>0.7</td>
      <td>7.4</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="4"><sup>*</sup> The third and latest iteration of newer generation Z-based models.</td>
    </tr>
  </tfoot>
</table>

If your authoring tool does not support footnotes in tables, include a phrase such as *See note 1*, and use an ordered list with a heading of *Note* or *Notes* in the last row of the table.

**Example**

<table>
  <thead>
    <tr>
      <td colspan="4" align="center"><strong>Table 1</strong> Device Specifications</td>
    </tr>
    <tr>
      <th>Model</th>
      <th>Height (cm)</th>
      <th>Depth (cm)</th>
      <th>Width (cm)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>AlphaPro X1</td>
      <td>15.2</td>
      <td>0.8</td>
      <td>7.6</td>
    </tr>
    <tr>
      <td>BetaMax Z3 (See note 1)</td>
      <td>14.5</td>
      <td>0.7</td>
      <td>7.4</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="4">
        <p>Note:</p>
        <ol>
          <li>The third and latest iteration of newer generation Z-based models.</li>
        </ol>
       </td>
    </tr>
  </tfoot>
</table>
