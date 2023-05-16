# HTML AND CSS Notes

# HTML

HTML stands for Hypertext Markup Language. It is the standard markup language used for creating and structuring the content of web pages. HTML uses tags to define elements within a document, such as headings, paragraphs, images, links, and various other components. These tags provide structure to the content and allow web browsers to interpret and display the web page correctly

HTML tags are used to define and structure the content of a web page. They are enclosed within angle brackets (< >)

It contains three parts: the **opening tag and information in it**, the **content**, and the **closing tag. one of the information in opening tag if Attributes which is key value pair**

## Attributes

HTML attributes provide additional information or modify the behavior of HTML elements. They are added to the opening tag of an HTML element and are specified within the tag as **name-value pairs**. Here's a brief explanation of HTML attributes:

- **`class`**: Specifies one or more class names to apply styling or identify elements for JavaScript or CSS.
- **`id`**: Assigns a unique identifier to an element, which can be used for styling or JavaScript manipulation.
- **`src`**: Specifies the source URL of an external resource, such as an image or a script.
- **`href`**: Specifies the target URL of a hyperlink or the location of a linked resource.
- **`alt`**: Provides alternative text for an image, which is displayed if the image cannot be loaded.
- **`style`**: Defines inline CSS styles to apply specific formatting to an element.
- **`disabled`**: Disables or makes an element non-interactive, such as a disabled input field or button.
- **`value`**: Sets the initial value of an input field or the value associated with a selected option in a dropdown list.
- **`placeholder`**: Displays a short hint or example text within an input field to guide user input.
- **`required`**: Specifies that an input field must be filled out before submitting a form.
- **`target`**: Specifies where to open a linked resource, such as a new browser window or tab.
- **`action`**: Specifies the URL where the form data should be submitted when the form is submitted.
- **`method`**: Defines the HTTP method to be used when submitting the form, usually either "GET" or "POST".
- **`name`**: Assigns a name to the form element, which is used to reference it on the server-side or in client-side scripting.
- **`enctype`** is set to **`"multipart/form-data"`**, which is the encoding type used for file uploads.

## Most use HTML tags

1. **`<html>`**: Represents the root element of an HTML document.
2. **`<head>`**: Contains meta-information about the document, such as the title and links to external resources.
3. **`<body>`**: Encloses the main content of the web page.
4. **`<h1>`** to **`<h6>`**: Headings of different levels, with **`<h1>`** being the highest level.
5. **`<p>`**: Defines a paragraph of text.
6. **`<a>`**: Creates a hyperlink to another web page or resource.
7. **`<img>`**: Inserts an image into the web page.
8. **`<ul>`**: Defines an unordered list.
9. **`<li>`**: Represents a list item within an unordered or ordered list.
10. **`<div>`**: Defines a division or a container that can be used to group other elements.
11. **`<span>`**: Used for applying styles or manipulating specific sections of text within a larger element.
12. **`<table>`**: Creates a table for displaying tabular data.
13. **`<tr>`**: Defines a row within a table.
14. **`<td>`**: Represents a cell within a table row.
15. **`<form>`**: Encloses input fields and other elements for creating web forms.
16. **`<input>`**: Creates an input field within a form.
17. **`<button>`**: Defines a clickable button.
18. **`<label>`**: Associates a label with a form element.
19. **`<select>`**: Creates a dropdown list.
20. **`<option>`**: Represents an option within a dropdown list.

# CSS

CSS stands for  Cascading Style Sheets, is a styling language used to describe the presentation and appearance of HTML  documents. It allows us  to control the layout, colors, fonts, and other visual aspects of web pages.

CSS works by selecting HTML elements using selectors and applying styling rules to them. Here's a brief explanation of how CSS works:

1. Selectors: CSS selectors target specific HTML elements or groups of elements to apply styles. Selectors can be based on element names, classes, IDs, attributes, or hierarchical relationships.
2. Declaration Block: Within CSS rules, a declaration block is enclosed in curly braces and contains one or more property-value pairs. Each pair specifies a specific aspect of the element's style.
3. Properties and Values: CSS properties define the visual properties of an element, such as color, font-size, margin, or background-color. Values are assigned to properties to specify how the property should be applied.
4. Cascading and Specificity: CSS follows a cascading model, where styles can be inherited from parent elements or overridden by more specific rules. Specificity determines which style takes precedence when multiple rules target the same element.
5. External and Internal CSS: CSS styles can be written inline within HTML elements, placed in the **`<style>`** element within the HTML document's **`<head>`**, or stored in separate external CSS files and linked to the HTML document using the **`<link>`** element.

**we use many methods to select a HTML element and style it**

1. Element Selector: Selects elements based on their element type. For example, **`p`** selects all **`<p>`** elements.
2. Class Selector: Selects elements based on their class attribute. For example, **`.my-class`** selects all elements with the class "my-class".
3. ID Selector: Selects an element based on its unique ID attribute. For example, **`#my-id`** selects the element with the ID "my-id".
4. Attribute Selector: Selects elements based on their attribute values. For example, **`[type="text"]`** selects all elements with the attribute **`type`** set to "text".
5. Descendant Selector: Selects elements that are descendants of another element. For example, **`div p`** selects all **`<p>`** elements that are descendants of a **`<div>`** element.
6. Child Selector: Selects elements that are direct children of another element. For example, **`ul > li`** selects all **`<li>`** elements that are direct children of a **`<ul>`** element.
7. Adjacent Sibling Selector: Selects an element that is the immediate next sibling of another element. For example, **`h2 + p`** selects the **`<p>`** element that comes immediately after an **`<h2>`** element.
8. Pseudo-classes: Selects elements based on a specific state or condition. For example, **`:hover`** selects an element when the mouse pointer is over it.
9. Pseudo-elements: Selects a specific part of an element. For example, **`::before`** inserts content before an element.

# CSS Style most used

## Position

CSS positions are used to control the layout and positioning of elements on a web page. There are several position values you can use in CSS:

1. Static (default): Elements are positioned in the normal flow of the document. The top, right, bottom, left, and z-index properties have no effect on static positioned elements.
2. Relative: Elements are positioned relative to their normal position. You can use the top, right, bottom, and left properties to adjust the element's position relative to where it would normally be.
3. Absolute: Elements are positioned relative to the nearest positioned ancestor (an ancestor element with a position value other than static), or the containing block if no positioned ancestor is found. Absolute positioned elements are taken out of the normal flow, so other elements will not be affected by them.
4. Fixed: Elements are positioned relative to the browser window. They will stay in the same position even if the page is scrolled. The top, right, bottom, and left properties are used to set the position of the element.
5. Sticky: Elements are positioned based on the user's scroll position. A sticky element is positioned relative to its nearest scrolling ancestor or the window if no scrolling ancestor is found. It behaves like a relatively positioned element until the scroll reaches a specified threshold, then it becomes fixed.

## z-index

used the when the element is positioned in top of each other to show the most important element to shown .the higher the value the most shown on the top

![Screenshot (151).png](HTML%20AND%20CSS%20Notes%20bd72955d4ba04c07b693aacf47ea9853/Screenshot_(151).png)

## Layout

### CSS flex:

1. Flex Container Properties:
    - **`display: flex;`**: Defines the element as a flex container.
    - **`flex-direction`**: Specifies the direction of the main axis (the primary axis along which flex items are laid out). It can be set to **`row`**, **`row-reverse`**, **`column`**, or **`column-reverse`**.
    - **`flex-wrap`**: Determines whether flex items should wrap onto multiple lines when there is not enough space. Values include **`nowrap`** (default), **`wrap`**, or **`wrap-reverse`**.
    - **`justify-content`**: Controls the alignment of flex items along the main axis. It offers options such as **`flex-start`**, **`flex-end`**, **`center`**, **`space-between`**, **`space-around`**, or **`space-evenly`**.
    - **`align-items`**: Defines how flex items are aligned along the cross axis (perpendicular to the main axis). Values can be **`flex-start`**, **`flex-end`**, **`center`**, **`baseline`**, or **`stretch`**.
    - **`align-content`**: Specifies the alignment of flex lines when there are multiple lines within the flex container. Options include **`flex-start`**, **`flex-end`**, **`center`**, **`space-between`**, **`space-around`**, or **`stretch`**.
2. Flex Item Properties:
    - **`flex-grow`**: Determines the ability of a flex item to grow to fill the available space. It accepts a unitless value, where a higher value indicates more growth.
    - **`flex-shrink`**: Controls the ability of a flex item to shrink if there is not enough space. It also takes a unitless value, with a higher value indicating more shrinking.
    - **`flex-basis`**: Specifies the initial size of a flex item before any remaining space is distributed. It can be set in pixels (**`px`**), percentages (**`%`**), or other length units.
    - **`flex`**: A shorthand property that combines **`flex-grow`**, **`flex-shrink`**, and **`flex-basis`** into a single declaration. For example, **`flex: 1 0 auto;`** means the item can grow, cannot shrink, and takes its initial size based on its content.
    - **`align-self`**: Overrides the **`align-items`** property for a specific flex item. It allows individual alignment control for each item within the container.
    
    ![Screenshot (152).png](HTML%20AND%20CSS%20Notes%20bd72955d4ba04c07b693aacf47ea9853/Screenshot_(152).png)
    
    ### CSS Grid:
    
    1. Grid Container Properties:
        - **`display: grid;`**: Defines the element as a grid container.
        - **`grid-template-rows`** and **`grid-template-columns`**: Specifies the size and structure of the grid by defining the number and size of rows and columns. You can use keywords like **`auto`**, length values like **`px`** or percentages **`%`**, or the **`fr`** unit to represent fractions of available space.
        - **`grid-template-areas`**: Allows you to name areas within the grid and assign grid items to those areas using a grid-area name. This property provides a convenient way to create complex layouts.
        - **`grid-gap`** or **`gap`**: Sets the size of the gaps between grid rows and columns. You can specify different values for row and column gaps using **`grid-row-gap`** and **`grid-column-gap`** as well.
    2. Grid Item Properties:
        - **`grid-row-start`**, **`grid-row-end`**, **`grid-column-start`**, **`grid-column-end`**: Defines the placement of a grid item within the grid by specifying the start and end lines of its row and column. Alternatively, you can use the shorthand **`grid-row`** and **`grid-column`** properties.
        - **`grid-area`**: Assigns a grid item to a named grid area defined in the grid container's **`grid-template-areas`** property.
        - **`grid-row`** and **`grid-column`**: Shorthand properties that combine **`grid-row-start`**, **`grid-row-end`**, **`grid-column-start`**, and **`grid-column-end`** into a single declaration.
    3. Grid Alignment and Spacing:
        - **`justify-items`**: Aligns grid items along the row axis within their respective grid cells. Values can be **`start`**, **`end`**, **`center`**, **`stretch`**, or **`auto`**.
        - **`align-items`**: Aligns grid items along the column axis within their respective grid cells. Values can be **`start`**, **`end`**, **`center`**, **`stretch`**, or **`auto`**.
        - **`justify-content`**: Aligns the grid items along the row axis within the grid container. It offers options such as **`start`**, **`end`**, **`center`**, **`stretch`**, **`space-between`**, **`space-around`**, or **`space-evenly`**.
        - **`align-content`**: Aligns the grid items along the column axis within the grid container. Values include **`start`**, **`end`**, **`center`**, **`stretch`**, **`space-between`**, **`space-around`**, or **`space-evenly`**.
        
        ![Screenshot (153).png](HTML%20AND%20CSS%20Notes%20bd72955d4ba04c07b693aacf47ea9853/Screenshot_(153).png)
        
        ### Centering Horizontally:
        
        To center Horizontally we use after giving width and then using margin right and margin left auto
        
        ## Background:
        
        To add a background effect to an element we can use the one of the following way:
        
        background-color by setting a color
        
        background-image by adding url(image/path)
        
        using linear gradient to make a bunch of colors on top of each other in order to make the texts on the image to be shown example on hero image we used liner gradient of colors and images . and we have to set the background-size property to cover
        
         
        
        ### CSS border and CCS border-radius
        
        to make border to an element we use the CSS border property and to make the border curve at the end we use  the border-radius property to the value to need .to make the element fully circle we make the element square and we make the border radius of it 50%.
        
        ### margins and padding
        
        Margin is used to make space between space between two separate elements and padding to make the space within the element and to make the space between the content and the border of the element
        
        ### Types of box in CSS
        
        block elements:
        
        block element take a full space by default and they make the element after them to start on a new line while the inline element take only the space they need for their content and they don’t have margin top and bottom by default and we can set height by default. but we can make inline element to look like block level element from outside and inline from inside
        
        ![Screenshot (150).png](HTML%20AND%20CSS%20Notes%20bd72955d4ba04c07b693aacf47ea9853/Screenshot_(150).png)
        
    
    ### Using max-width instead of width:
    
    It will make the element to be responsive in a screen less than the specified length.