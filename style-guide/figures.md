# Figures and images

<code>ELMER: Work In Progress</code>

Use figures within text passages to enhance or supplement your content. Figures encompass visual elements like images, illustrations, and screen captures, which are non-textual in nature.

## Using images

Only use images when they offer valuable visual clarification of information challenging to convey solely through words or for screenshots of user interfaces that are essential to the discussion.

Adhere to these guidelines when using images:

- Use a specialized tool for the task. If you need to create a diagram, use a drawing or diagramming tool. Likewise, for taking screen captures, use a screen capture tool. While some software might offer both functionalities, utilizing specialized tools that excel in each task is preferable. Specialized tools are designed to focus on specific tasks, leading to a more efficient workflow.
- Standardize the tools used for documentation and ensure all contributors adhere to this selection. For instance, choose a single diagramming tool to maintain consistency and quality. This approach is particularly beneficial for teams with multiple writers, each with individual tool preferences, or for companies engaging contract writers.
- Prefer SVG files for diagrams like architectural drawings and flowcharts, as they remain crisp upon zooming in. If an SVG file is unavailable, use a PNG file unless there is a specific reason to select a different format.
- For animations and videos, avoid using animated GIFs. Instead, opt for more resource-efficient formats like MP4.
- Do not use images of text, code samples, or terminal output. Use actual text.
- Maintain consistency within a single document or documentation set regarding the operating system used for screenshots. For instance, choose either macOS or Linux for all screenshots. Also, ensure uniformity in the appearance of your screenshots. If they include drop shadows of the main window, apply this style consistently across similar screenshots.
- If branding or watermarks are needed to be applied to images owned by the company, ensure that the styling is enforced to maintain consistency and signify ownership.
- Crop screenshots to display only relevant information. For instance, exclude the full window when highlighting a specific button or menu item. Cropping directs the reader's attention to the intended details in the screenshot and aids in maintaining its relevance, even if other UI elements change.
- Exclude any personally identifying information (PII) from screenshots.

  Should the original screenshot contain PII, conceal it using a solid-color overlay that is completely opaque. Avoid using blurs, mosaics, or similar effects to obscure PII, as these can potentially be reversed, exposing the concealed information.

  When exporting images in formats that hold separate layers, like PDF or TIFF, ensure the image is flattened upon export to prevent layer separation and potential exposure of hidden details.
- Do not use image maps. Instead, opt for a list of text references after the image. Image maps pose challenges for accessibility and entail technical complexities in their creation and maintenance.

## High-resolution images

Use images with a high pixel density to ensure clarity and detail. This preference is significant for diagrams, technical illustrations, and photographs where precision is key. Modern browsers can use high-resolution images if available; this makes the images look better on high-resolution displays.

On the other hand, balance resolution with file size to maintain page load speeds. Aim for a high enough resolution for clarity without excessively increasing the file size.

To ensure a high-resolution image is displayed, utilize the `<img>` element's `srcset` attribute alongside the standard `src` attribute. The `srcset` attribute allows for specifying different image assets for varying screen resolutions. This attribute can receive a comma-separated list of image URLs, each followed by a size qualifier: `1x` for standard resolution and `2x` for double the resolution.

When a web browser supports the `srcset` attribute, it selects from the provided images, choosing one that matches the display's resolution. In cases where the browser does not support `srcset`, it defaults to the image specified in the `src` attribute. Therefore, it is essential always to include the `src` attribute.

For example, to offer images for both standard and double resolutions, include the `srcset` attribute in your image tag, listing URLs for both `1x` and `2x` image assets:

```html
<img src="/assets/images/dogs.png"
  srcset="/assets/images/dogs.png 1x,
  /assets/images/dogs_2x.png 2x"
  width="375" alt="" />
```

The following guidelines provide specific recommendations for the optimal use and maintenance of high-resolution images:

- Prioritize vector images (such as SVG files) for diagrams and illustrations, as they maintain quality at any size.
- For raster images (like PNGs or JPEGs), ensure they are at least 300 DPI for printed materials and a minimum of 72 DPI for web usage.
- Test how images appear on different devices, especially for responsive web design. Ensure that high-resolution images remain crisp and clear across various screen sizes and resolutions.
- Provide alternative text for all high-resolution images to ensure accessibility for screen reader users.
- Be mindful of file sizes, as huge images can hinder accessibility for users with slower internet connections.
- Review and update images to ensure they meet high-resolution standards, significantly if UI elements or product designs change.

## Screen captures

Using screen captures as a visual aid can enhance orientation, minimize confusion, and improve information retrievability for readers. However, deciding to include them requires careful consideration. Consult with your translation coordinator, information architect, management, and other stakeholders to navigate the complexities involved.

Avoid translating or mirroring screen captures. Instead, use images from the national language versions of your product. Adhere to international design standards for graphics, which cover cultural considerations, approved graphic file formats, and space requirements for text.

Screen captures are effective when they fulfill one or more of the following objectives:

- Demonstrate the outcomes of sequential steps or user interactions
- Assist users in locating specific components within a multifaceted user interface
- Illustrate complex or intricate user interfaces that are challenging to describe solely through text
- Guide readers who are engaging with the publication without direct access to the user interface
- Offer alternatives that enhance accessibility

Screen captures tend to be less effective in the following scenarios:

- Utilizing poor-quality captures.
- Displaying straightforward interfaces that offer no extra guidance to the user.
- Enhanced with unsuitable borders, highlighting, or design elements that hinder quick recognition.
- Applied inconsistently, like including them for certain complex processes but not for others.
- Overused, such as detailing the interface instead of focusing on user tasks.

When creating screen captures, take into account the following factors:

- The precision and correctness of the screen captures.
- Ongoing maintenance and updates in subsequent releases.
- The ease of producing screen captures in different languages.
- Legal implications related to content that may be under the intellectual property rights of another entity.

Follow these guidelines should you decide to incorporate screen captures:

- Use images of windows and user interface elements judiciously.
- Focus the capture on the specific screen or window area that demands user attention.
- Accurately represent user interface elements as they appear to users for immediate recognition.
- Only include the cursor, mouse pointer, or menus when they are crucial to understanding.
- Maintain consistent proportions among your screen captures.
- Annotate captures if it aids in locating specific user interface components.
- Document the necessary user interface actions for each capture and any system prerequisites to replicate the scenario. Provide these comprehensive instructions to translators and language testers.

## Text associated with images

Alt text, figure captions, and figure descriptions are crucial text elements associated with images, each serving a unique function. Regardless of these elements, an introduction sentence often precedes images. The sentence may end with a colon or a period; typically, a colon is used if it directly precedes the image, and a period is used if additional content, like a note paragraph, separates the introduction from the image. Always present an image with a complete sentence. Introducing screenshots is not necessary when they directly follow procedural text describing a user interface.

<!-- image goes here -->

### Alt text

Alt text (alternative text) is crucial for making images accessible to users who rely on screen readers due to visual impairments and in situations where images might not be displayed. It describes the content and function of images, ensuring that all users can understand their significance.

Alt text should be descriptive yet concise, offering insights into the image's relevance to the surrounding content. It plays a crucial role in accessibility, allowing content to be more inclusive.

As an example, here is how you write alt text for HTML or Markdown:

```html
<img
  src="/images/corgi-on-beach.png"
  alt="Corgi strolling alone on a beach" width="375"
/>
```

```markdown
![Corgi strolling alone on a beach](/images/corgi-on-beach.png)
```

Sometimes, an image's role is solely decorative or visually supports content already described in the text. In these cases, using empty alt text (`alt=""`) is appropriate so assistive technologies can skip them. Decorative images might include:

- UI screenshots that visually guide but do not add new information.
- Icons that are supplementary to text instructions.
- Images designed to enhance visual appeal without contributing additional content.

Remember, the `<img>` element requires the `alt` attribute, even if it is empty. Omitting the `alt` attribute could lead screen readers to announce the image's filename, disrupting the user's experience.

The [guiding principle from the HTML specification](https://html.spec.whatwg.org/dev/images.html#general-guidelines) is that replacing an image with its alt text should not alter the meaning of the page. If alt text would be redundant or not beneficial to visually impaired users, opting for an empty alt attribute is the best practice.

Keep these best practices in mind when writing alt text:

- Alt text should be descriptive and concise. Provide clear, brief descriptions that convey the essential information or function of the image.

  **Example image description:**

    A photo showing a group of students sitting around a table, engaged in discussion, with open laptops and notebooks in front of them.

  **Example alt text to write:**

    "Students in a study group discussing notes with laptops open."

- Do not start alt text with phrases like *image of* or *picture of*. Screen readers typically announce images, making such prefixes unnecessary.

- Incorporate punctuation within the alt text. Screen readers will pause upon encountering punctuation, enhancing the reading experience.

- Where feasible, refrain from employing all capital letters in alt text. Screen readers may interpret capitalized letters as individual characters, impacting clarity.

- While there is no strict character limit, it is best to keep alt text under 125 characters if possible. Longer descriptions can be moved to the surrounding text or a figure description.

- Ensure alt text is contextually relevant. It must fit the image's specific role within its context. The same image may require different alt text depending on how it is used in various parts of the text.

  For example, if you have a close-up photo of a chef meticulously decorating a cake, you will have an alt text for using the image for a culinary school website. You will also write a different alt text if that photo is used for a gourmet cooking article.

- Maintain uniform alt text for images that recur within your document, including controls, status indicators, or icons. This consistency aids in recognition and understanding across the document.

- Write alt text as a functional text for interactive images. If the image is interactive or serves as a hyperlink, the alt text should describe the action or destination, like, for example, "Submit button" or "Link to Cloud Security Guide."

- When applying search engine optimization (SEO) techniques to alt text, it is essential to include relevant keywords naturally and steer clear of keyword stuffing. The foremost objective of alt text should be to boost accessibility rather than focusing on SEO.

### Figure captions

Figure captions offer succinct yet detailed descriptions of figures or images, enhancing the reader's understanding of visual content. While not mandatory, they add value by providing context or additional details. For effective integration of figure captions with images in digital documentation, wrap both the `<figcaption>` element and the `<img>` element within a `<figure>` element. This method ensures that captions are directly linked to their respective images, fostering a coherent and accessible presentation of visual information. Incorporating figure captions not only aids in comprehension but also contributes to a more polished and professional document.

Follow these guidelines when writing figure captions:

- Begin with the word *Figure* followed by the figure number and a period. Then, provide a clear description.

  **Example**<br>
  **Figure 1.** The application's capabilities are divided into bounded contexts that transition into services.

- Use complete sentences for figure captions to maintain clarity and coherence.

- Conclude captions with appropriate end punctuation, such as periods, even if the caption is brief.

- Avoid spatial references like "the image below" when mentioning figures within the text. Always refer to figures by their number, ensuring precision and removing ambiguity. For instance: "... as illustrated in figure 1." Only capitalize *figure* when it begins a sentence.

  **Examples (incorrect) ❌**
    - As you can see in the image below, cloud security mechanisms are diverse.
    - The picture above illustrates various encryption methods.

  **Examples (correct) ✅**
    - As shown in figure 1, cloud security mechanisms are diverse.
    - Various encryption methods are illustrated in figure 2.

- Do not incorporate the figure caption within a sentence that references the figure. Keep references to figures and the content of captions separate to enhance readability.

  For example, if you have the following figure caption:

  **Figure 1.** The application's capabilities are divided into bounded contexts that transition into services.

  **Incorrect approach ❌**

  - "As illustrated by Figure 1, which shows the application's capabilities divided into bounded contexts, we can see the transition into services."

  In this example, the caption content "which shows the application's capabilities divided into bounded contexts" is merged into the sentence referencing the figure. Its inclusion makes the sentence cumbersome and disrupts the flow of information.

  **Correct approach ✅**

  - "As illustrated in Figure 1, the architectural design emphasizes modularity."

  The reference to the figure in the document's text is concise and separate from the figure caption itself. The caption, placed with the figure, provides a detailed description of what the figure represents. This separation allows the narrative to flow smoothly while still directing the reader to the figure for detailed visual context.

### Figure descriptions

A figure description goes beyond the concise narrative offered by a figure caption. While a caption typically provides a brief overview or context for the image or figure it accompanies, a figure description is more detailed and comprehensive. It is designed to offer an in-depth explanation of the figure's content, significance, and how it relates to the text. Usually, a figure description includes the following:
  - Description of visual elements that are not immediately apparent
  - Explanation of data or methodologies represented in the figure
  - Explicit linkage of the figure to the document's argument or narrative

Figure descriptions also enhance accessibility by providing a textual representation of visual content, which is crucial for readers who use screen readers or for situations where the figure cannot be viewed.

For complex figures, such as graphs, technical diagrams, or charts, a detailed figure description can aid readers in understanding the figure's relevance and the specifics of the presented data or concept.

**Example scenario**

Consider a technical manual that includes a software application's architecture diagram.

- **Figure caption**

  **Figure 2**. Overview of the application's architecture.

- **Figure description**

  Figure 2 illustrates the application's layered architecture, starting from the user interface at the top, then the application processing layer, and finally, the database layer at the bottom. Each layer is interconnected, with arrows indicating the flow of data. The user interface layer is designed to provide a seamless user experience, the application processing layer handles the business logic, and the database layer manages data storage and retrieval.

In the example scenario, the figure caption succinctly introduces the figure, while the figure description offers a detailed breakdown of the architecture. It explains the function of each layer and how data flows from one layer to another. This method ensures that all readers can grasp the content and significance of the figure, regardless of their ability to view it visually.

Lastly, consider the following key factors to ensure figure descriptions are effective, accessible, and supportive of the overall document:

1. Improve audience understanding by tailoring the figure description to match your intended audience's knowledge level and expectations. Aim to make the description accessible and informative for all readers, including those who rely on assistive technologies.

2. It is crucial to ensure clarity and precision in figure descriptions. Clearly and accurately describe what the figure shows, using specific terminology to avoid ambiguity and enable readers to understand the content without seeing the figure.

3. Prioritize accessibility in every figure description to ensure that users of screen readers can fully understand the content. This guideline requires the avoidance of visual references, such as saying "as shown on the right side of the figure," and making sure that the text provides all necessary information depicted in the figure.

4. Find a balance between brevity and detail. While it is crucial to provide a comprehensive explanation, keep the description concise to maintain reader engagement. For complex figures, consider using supplementary text to provide additional details.

5. Maintain consistency in the formatting and structure of figure descriptions across the document. Consistent presentation helps set clear expectations for readers and enhances the overall readability and professionalism of the document.

Figure descriptions are an essential component of comprehensive documentation, working alongside figure captions and figures to ensure visual content is accessible, understandable, and fully integrated into the document's narrative.

### Inclusion of text in figures

Including text in figures or images can be effective if it enhances the user's understanding, emphasizes key points, or labels specific parts of a visual. However, it should be done with consideration for accessibility and readability. Over-reliance on text within images can exclude those using screen readers, contribute to information being lost or overlooked in translation, and reduce the flexibility of your content across different viewing contexts.

Generally, it is advisable to refrain from integrating descriptive text within figures or images. Should the inclusion of text in images be unavoidable, ensure that this information is also available in an accessible format, like a detailed figure description, to accommodate individuals with visual impairments.

When the inclusion of text in figures or images is necessary, adhere to these guidelines to ensure clarity, accessibility, and effectiveness:

- Keep text brief. Avoid complete sentences and punctuation where feasible.
- Do not invent new abbreviations to shorten text.
- Avoid incorporating figure descriptions or captions directly within the figure or image. Place figure descriptions and captions in the text that follows the figure instead.
- Always provide an alternative text description or a figure caption that conveys the same information in the image's text. Doing so guarantees accessibility for individuals who use screen readers.
- Ensure the text within the image has high contrast against its background to improve readability for everyone, including those with visual impairments.
- Use numbered callouts in figures as aids in composing a figure description, yet avoid using callouts for extensive annotations within the image.
- If the document will be translated, remember that text in images can complicate localization. Where possible, design images so that text can be easily updated or replaced for different languages.

### Accessibility resources

For more information about the accessibility of diagrams and screenshots, see the following resources:

- [Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/glance/)
- [General text alternative guidelines from WCAG](https://www.w3.org/WAI/WCAG21/quickref/?showtechniques=111#text-alternatives)
- [Using `alt` attributes for `img` elements](https://www.w3.org/WAI/WCAG21/Techniques/html/H37.html)
- [Providing a long description in text near the non-text content](https://www.w3.org/WAI/WCAG21/Techniques/general/G74.html)
- [Complex images](https://www.w3.org/WAI/tutorials/images/complex/)
