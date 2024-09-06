1.  **Types of text Property in css :**
        
   **Ans:** CSS, text properties are used to style and manipulate the text within an HTML element. 
                color: Sets the color of the text.
                font-family: Specifies the font for the text.
                font-size: Defines the size of the text.
                font-weight: Determines the thickness of the text (e.g., bold).
                font-style: Specifies the style of the text (e.g., ital)

**2.Difference between display block element and display inline element**    

   **Ans:**      

   **Block Elements:**
            
   **CSS Display Value:** display: block;
            
   **Characteristics:**
               Takes up the full width available.
               Starts on a new line.
               Allows you to set width and height properties.
               Margins and padding affect the surrounding layout
            
   **Inline Elements:**
         
   **CSS Display Value:** display: inline;
   
   **Characteristics:**
               Takes up only as much width as necessary.
               Does not start on a new line; instead, it sits next to other inline elements.
               Does not allow you to set width and height properties.
               Margins and padding do not affect the surrounding layout in the same way as block elements.  


3.**What is math Function in css?**

         In CSS, the math functions allow you to perform basic mathematical operations directly within your styles. These functions can help calculate values dynamically, making your CSS more flexible and responsive. 
      
      **(i) calc():**
         
         The **calc()** function lets you perform calculations to determine CSS property values.
         You can use calc() with addition (+), subtraction (-), multiplication (*), and division (/).
      
      **(ii) min():**
         
         The **min()** function returns the smallest value from a list of comma-separated expressions.
      
      **(iii) max():**
         
         The **max()** function returns the largest value from a list of comma-separated expressions.   


**4.Difference between px and em:**
         
   **(i) Pixels (px):**
         
   **• Pixels (px)** are like fixed measurements. If something is 16px, it's always 16 pixels wide, no matter what. The size doesn't change.
         
   **(ii) Ems (em):**
         
   **• Ems (em)** are relative measurements. If you say something is 1em, its size depends on the size of the text in the parent element. So, if the parent text is 16px, 1em = 16px. If the parent text is 20px, 2em = 40px.
         
   **In short:**
         
   **px** = fixed size.
   **em** = flexible size, based on the parent element's font size.   


**5. How can do create a responsive design using css?**
 
   To create a responsive design using CSS, follow these steps:

   **i.** Use relative units: Instead of pixels, use relative units like percentages (%), ems (em), or rems (rem) for measurements.

   **ii.** Define breakpoints: Identify common screen sizes (e.g., mobile, tablet, desktop) and define media queries for each.

   **iii.** Media queries: Use @media queries to apply styles based on screen sizes, orientations(portrait or landscape), or resolutions.                                
           

 **6. 1. what is calc() function in CSS.**   
     
     The calc() function in CSS allows you to perform mathematical calculations to determine CSS property values. This function is particularly useful for creating dynamic and responsive layouts where you need to combine different units or make calculations 
     based on other values.     


**7. How do you create a CSS grid layout?**

      Use the display: grid; property on a container element, and then define rows and columns with properties like grid-template-rows and grid-template-columns.


**8. what is meane by RGB function?**          

         The RGB function is used to define colors in digital systems by specifying the intensity of three primary colors: Red, Green, and Blue. Each of these colors can have a value between 0 and 255. By combining different values of red, green, and blue, the RGB function can create a vast array of colors.

  **For example:**

        rgb(255, 0, 0) produces pure red.
        rgb(0, 255, 0) produces pure green.
        rgb(0, 0, 255) produces pure blue.
        rgb(255, 255, 255) produces white.
        rgb(0, 0, 0) produces black. 


**9. Types of Selectors:**

   Different types of CSS selectors with explanations:

   **1. Universal Selector (*)**
         Selects all elements on the page.
         **Example:** * { margin: 0; padding: 0; } removes margin and padding for all elements.

   **2. Type Selector (Element Selector)**
         Selects elements based on their HTML tag name.
         **Example:** p { font-size: 16px; } targets all <p> (paragraph) elements.

**3. Class Selector (.)**
         Selects elements with a specific class attribute.
         **Example:** .button { background-color: blue; } selects elements with the class "button".

**4. ID Selector (#)**
         Selects a single element based on its ID attribute.
         **Example:** #header { background-color: gray; } targets the element with id="header".
         The grouping selector in CSS allows you to apply the same styles to multiple elements by listing them together, separated by commas. Instead of writing separate rules for each element, you group them and apply a single set of styles.


**10. HTML Tags:**
   **common HTML tags:-**

   **Document Structure:**
         **<html>:** Root element.
         **<head>:** Metadata and links.
         **<body>:** Main content.

   **Text Formatting:**
         <p>: Paragraph.
         <h1> - <h6>: Headings.
         <b>, <strong>: Bold text.
         <i>, <em>: Italic text.
         <br>: Line break.

   **Links and Images:**
         <a>: Hyperlink.
         <img>: Image (self-closing).

   **Lists:**
         <ul>: Unordered list.
         <ol>: Ordered list.
         <li>: List item.

   **Tables:**
         <table>: Table.
         <tr>: Table row.
         <td>: Table cell.
         <th>: Table header.

   **Forms:**
         <form>: Form container.
         <input>: Input field.
         <button>: Button.

   **Semantic Tags:**
         <header>: Header section.
         <nav>: Navigation links.
         <section>: Content section.
         <footer>: Footer section.

   **Self-closing:**
         <img>, <br>, <hr>: No closing tag needed. 


**11. What are pseudo-classes and pseudo-elements? Can you provide examples?**

   **Pseudo-classes:**
         Apply styles to elements based on their state **(e.g., :hover for when an element is hovered over, :focus for when an element is focused).**
   
   **Pseudo-elements:** 
         Target specific parts of an element **(e.g., ::before to insert content before an element's content, ::after to insert content after).**                 

                   