# reference-website
1. Naming convention for all filenames, paths and folders
- The naming conventions for all filenames should be lowercase, no spaces and dashes are fine. Folder naming convention should be similar to filenames. For paths, the folders, assets and files should be inside the root folder so they can be easily linked inside any .html files
    `index.html` 

2. Best practices for commit messages
- The best practices for commit messages are to separate the subject from body with a blank line. Not to end the subject line with a period and not to capitalize the subject line and each paragraph.

3. What is HTML>
- Html stands for Hyper Text Markup Language and its used for creating web pages and describes the structure of the web page. 

4. Proper syntax for HTML?
- The proper syntaxt for HTML consists mainly of tags that are enclosed inside angle brackets such as <h1>. These tags are used to indicate the start and end of text. However, the end tag is a bit different. We add a forward slash in the tag such as </h1> to demonstrate the end of the tag. 

5. Explain or demonstate commonly used html tags/elements:
- headings: h1-h6 
    - Different heading have different weights and sizes. One being the most important, the lagest and six being the least and smallest. 
- p
    - The p tag is used for paragraphs. If you have many paragraphs you can start numbering them such as, p1, p2, p3, etc.. They would look like this <p1> Insert your text here </p1>
    <p2> Insert your text here </p2>
- lists:ul, ol, dl
    - A ul list is an element that represents an unordered list of items. Meaning if we were to change the order of the items, it would not chnage the meaning of the list. 
    - A ol list is an element that represents an ordered list of items. Usually this means the list is numbered and changing the order would change the meaning. 
    - A dl list is an element that represents a description list. This is commonly used to implement a glossary or to display metadata ( a list of key-value pairs)
- a
    - The a tag defines a hyperlink, which is used to link from one page to another. The most important attribute of the a element is the href attribute as it indicates the links destination. 
- img
    - The img tag is used to incorporate in-lin graphics such as icons or small graphics into the html document. 
- q
    - The q tag indicates that the enclosed test is a short inline quotation. This element is intended for short quotations that dont require paragraph breaks. 
- blockquote
    - This element represents a section that is quoted from another source. 
- cite
    - This element is used to mark up the title of a cited creative work. 
- em
    - This element is used to mark texts that has stress emphasis.
- strong
    - This element is used to indicate that its content have strong importance, seriousness, or urgency. Meaning the text is typically in bold. 
- b 
    - This element is used to draw the reader's attention to the element's contents, which are not otherwise important. 
- i
    - This element is used to indicate a technical term, a phrase from another language, a thought, s aship name, etc. 
- small
    - This element represents side-comments and small print, like copyright and legal text, independent of its styled presentation. 

6. Explain block Elements and also explain the list of block elements and why they are used from below:
    - Block elements are elements that begin a new line on a web page and extends the full width of the available horizontal space of its parent element. Which creates large blocks of content like paragraphs or page divisions. 
    1. html
        -
    2. head
        - The head element contains machine-readable information about the document such as its titles, scrips and style sheets. 
    3. body
        - The body element represents the content of the Html document and there should only be one body element in the document. 
    4. header
        - The header element is the introductory content, typically a group of introductory or navigational aids. 
    5. nav
        - The nav element is a section of a page that links to other pages or to parts within the page, a section with navigational links. 
    6. main
        - The main element is what indicates and specifies the main content of the document.
    7. section 
        - The section element is a generic standalone section of a document, which doesnt have a more specific semantic element to represent it. It whould always contain a heading. 
    8. article
        - The article element is a self-contained composition in a document, page, application, or site which is intended to be independently distributable or reusable. 
    9. div
        - The div element is a generic contain for flow content. It has no effect on content or layout until its styled in some ways using CSS.
    10. aside
        - The aside element is a section of a page that consists of content that is related to the content around the side element, which could be separated from that content. 
    11. footer
        - The footer element represents a footer for its nearest ancestor sectioning content or sectioning root element. 
    12. span
        - The span element is a generic inline container for phrasing content, which does not inherently represent anythihng. 
    13. small
         - The small element is a side-comments and small print, like copyright and legal text, which is independent of its styled presentation. 

7. Explain why accessibility is important and also wxplain the accessibility properties like:
    - Accessibility is important even in Html due to the visual and dynamic nature of the webpage that you make, it's important to make sure that the website will also make sense to the visually-impaired or blind users. As we do not know who will be looking or consulting the pages. It's important to make to it accessible for everyone. 
    1. landmark roles
        - The importance of landmark roles in Html is to allow assistive technologies to navitage and find content quickly. 
    2. aria labels
        - The importance of aria labels is to provide an acessible name for an element if there is no visible name for the element you can refer. 
    3. image alternative texts
        - The importance of image alternative texts is to help screen-reading tools to describe images to the visually impaired readers and allows search engines to better crawl and rank your website. 

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
    - CSS stands for cascading style sheets. Its a design language that makes a website look more appealing than jus plain or uninspiring peices of texts. It also determines visual structure, layout and aesthetics. The code required to attach a CSS file inside an Html file is <link rel="stylesheet" href="css_folder/style.css">

9. What is the difference between CSS property and valu (write explanation and an example code)
    - The difference between CSS property and Valu is that, property is an aspect of a selector, meaning you can change the font-family, color, and font-size of the text on your web page. However, the valu is a possible setting for a property. An example of this would be 
p {
  color: blue; "color" is the property, and "blue" is the value
  font-size: 16px; "font-size" is the property, and "16px" is the value 
}

10. Why do we use border-box property in CSS?
    - We use the border-box property in CSS to tell the browser to account for any border and padding in the values you specify for an element's width and height. 

11. Explain different type of ways we can add spacing to an element
    - The different ways we can add spacing to an element is by using margins, paddings, grid gap, and flebox gap. 

12. What is the main difference between margin and padding?
    - Padding represents the amount of inner space an element has. Margin is whitespace available surrounding an element. 

13. What are the different types of display properties?
    - The different types of display properties are block, inline, flex, grid, table, etc.. 

14. Write a brief explanation of flexbox property
    - Flexbox is a one-dimensional layout system that we can use to create a row or a column axis layout. It makes it easier to design and build responsive web pages without having to use tricky hacks. 

15. What are the different types of flexbox properties and what is the major difference between them?
    - Flexbox is a CSS layout model that provides a flexible way to distribute space along a single axis (either horizontally or vertically) within a container. There are several flexbox properties that can be used to control the layout and behavior of flex containers and their child elements

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flebox property
    - <div class="container">
  <div class="item">Item 1</div>
  <div class="item">Item 2</div>
  <div class="item">Item 3</div>
</div>

.container {
  display: flex; /* Flexbox property to create a flex container /
  flex-direction: row; / Sub-property to set the direction of flex items, in this case, to row /
  justify-content: space-between; / Sub-property to align flex items along the horizontal axis with space between them /
  align-items: center; / Sub-property to align flex items along the vertical axis, in this case, to the center /
}

.item {
  flex: 1; / Sub-property to specify flex grow, flex shrink, and flex basis of flex items /
  padding: 10px; / Example of other CSS properties you can use on flex items */
}

17. Write a code example on how you will use a flexbox property on a parent element with sub properties
    - .container {
  display: flex;
  flex-direction: row;
  justify-content: center; 
  align-items: center; 
}

18. What is CSS grid property?
    - A grid property is a shorthand property that sets all of the explicit and implicit grid properties in a single declaration. 

19. Write the parent of two sub-properties used for CSS grid property
    - The parent property that encompasses both grid-template-rows and grid-template-columns in CSS Grid Layout is grid-template. This property is a shorthand property that allows you to define both the rows and columns of the grid in a single declaration.

20. What is the difference between display: flex and display: grid?
    - The difference between the flex and the grid is that the flexbox was designed for layout in one dimension either row or a column. However, the grid was designed for two dimensional layut, such as rows and columns at the same time. 

21. What sub-property we use to divide elements in CSS grid properties?
    - You can use the grid-template-rows and grid-template-columns properties to define the size and layout of the grid tracks, which are the columns and rows of the grid. These properties are used to divide the grid container into a grid of tracks, which are then used to position and size the grid items (child elements) within the grid

22. What unit we use to fractionally divide the elements width in CSS grid property and what are other units we can use alternatively (Write a code example)
    - The fr (fraction) unit is used to fractionally divide the width of grid columns or rows. It represents a fraction of the available space in the grid container. An example of this would be: 
    .grid-container {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr; 
    }

23. What is the are property in CSS grid we use for the child elements?
    - In CSS Grid Layout, the properties that are used for child elements (i.e., the items within a grid container) are known as "grid item properties". These properties allow you to control the placement, sizing, and behavior of the grid items within the grid container. 

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property
    - The grid-auto-columns property in CSS Grid Layout can be used to prevent displaying empty columns by specifying the size of implicit (automatically generated) grid columns. An example of this would be:

.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr; 
  grid-auto-columns: 200px; 
} 

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file
    - The steps to adding google fonts to your CSS file is to look for a font you like in google fonts, then pick the styles you want such as bold, regular, italic, etc.. Then onces you've added them to the side bar, you select link and then you can copy the link by clicking the two small pages. Once you've done that, you can go into your html and in the head you can paste the link and you're all done.  
