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

   **(I). Universal Selector (*)**
         Selects all elements on the page.
         **Example:** * { margin: 0; padding: 0; } removes margin and padding for all elements.

   **(II). Type Selector (Element Selector)**
         Selects elements based on their HTML tag name.
         **Example:** p { font-size: 16px; } targets all <p> (paragraph) elements.

   **(III). Class Selector (.)**
         Selects elements with a specific class attribute.
         **Example:** .button { background-color: blue; } selects elements with the class "button".

   **(IV). ID Selector (#)**
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


**11. what is css overflow?**

            the overflow property determines how content that exceeds the size of its container is handled. It is particularly useful when you want to control what happens when content is too large to fit within an element.

**visible (default):**
      The content is not clipped and may overflow outside the container. This can lead to content spilling out beyond the defined boundaries.

**hidden:**
      The content is clipped, and anything that overflows the container is hidden. The overflowed part is not visible and cannot be scrolled to. 


**12. 1.What is the difference between ~isibility: hidden and display: none~?**

   **Visibility: hidden:**
           **=>** The element is hidden, but it still takes up space in the layout.
           **=>** The content remains invisible, but the area it occupies is not removed.
   
   **Display: none:**
           **=>** The element is completely removed from the layout as if it doesn't exist.
           **=>** It takes up no space, and surrounding elements may adjust to fill the gap                             


**13. What is Flexbox and how its work?**
            
            Flexbox is a CSS tool used to organize and align elements in a container. It helps in easily placing items horizontally or vertically, making layouts flexible and responsive to different screen sizes.

   **Here’s how it works:**
            Container Setup: First, you define a parent container as a flex container, which will control the layout of its child items.
   
   **Horizontal Alignment:** 
            You can align the items inside the container to the left, right, center, or spread them out evenly.
   
   **Vertical Alignment:** 
            You can align items to the top, bottom, center, or stretch them to fill the height of the container.
   
   **Responsive Design:** 
            Flexbox adjusts the size and position of items automatically based on the available space, which makes it useful for building layouts that adapt to different devices.


**14. CSS position property:**

                The CSS position property is used to specify how an element is positioned in a webpage. It determines where an element will appear and how it behaves in relation to other elements

 **Here are the different types of positioning in CSS:**

   **Static:** 
           This is the default position. Elements are placed in the normal document flow (based on how they appear in the HTML).

   **Relative:**
           The element is positioned relative to its normal position. You can use top, right, bottom, and left properties to move it from where it would normally be.

   **Absolute:**
           The element is positioned relative to its nearest positioned ancestor (anything except static). If there's no positioned ancestor, it uses the document body.

   **Fixed:** 
           The element is positioned relative to the browser window, so it stays in the same place even when the page is scrolled.

   **Sticky:**
           The element switches between relative and fixed, depending on the scroll position. It behaves like relative until it hits a certain point on the page, and then it sticks in place.                


**15. what is animatable in css ?**

                In CSS, animatable refers to properties that can be smoothly transitioned or animated over time using CSS animations or transitions. If a CSS property is animatable, you can create visual effects where the property changes gradually rather than instantly.


**16. There are three main types of stylesheets used in web development:**

   **Inline Styles:**
                Written directly in the HTML element using the style attribute.
   
   **Example:**
       
        <h1 style="color: blue;">Hello World</h1>
        Internal (Embedded) Stylesheet:
        Defined within a <style> tag inside the <head> section of the HTML document.
        Example:
        <style>
          h1 {
            color: blue;
          }
        </style>
   
   **External Stylesheet:**
                Written in a separate CSS file and linked to the HTML document using a <link> tag.

   **Example:**
        
        <link rel="stylesheet" href="styles.css">
        CSS File (styles.css):
        h1 {
          color: blue;
        } 


**17. what is colspan  and rowspan in html.**
    
   **a)Colspan :**
              Colspan attribute is used to span a cell across multiple columns.
    
   **b) Rowspan :**
              Rowspan attribute is used to span a cell across multiple rows. 


**18. What is object-fit property in css?**

                The object-fit property in CSS is used to control how an element’s content fits within its container. This is particularly useful for images and other media elements, allowing you to specify how they should be resized and positioned within a given space. 


**19. What are pseudo-classes and pseudo-elements? Can you provide examples?**

   **Pseudo-classes:**
         Apply styles to elements based on their state **(e.g., :hover for when an element is hovered over, :focus for when an element is focused).**
   
   **Pseudo-elements:** 
         Target specific parts of an element **(e.g., ::before to insert content before an element's content, ::after to insert content after).** 


**20. What are pseudo-clasees and pseudo-elements?**

   **Pseudo-Classes:**

                A pseudo-class is used to define a special state of an element. It targets elements based on information that is not present in the document tree, such as user interactions or element positions.

   **Pseudo-Elements:**

                A pseudo-element is used to style specific parts of an element, rather than the whole element itself. It creates "virtual" elements that don’t exist in the DOM but are still styleable.

   **Key Differences:**

                Pseudo-classes target the entire element when it is in a specific state (e.g., hovered, focused).
Pseudo-elements target specific parts of an element (e.g., the first letter, content before/after an element).

   **Syntax:**
        Pseudo-classes use a single colon (:)
        : :hover, :focus.
        Pseudo-elements use double colons (::): ::before, ::after. (However, older versions of CSS allowed pseudo-elements to be written with a single colon.)    


**21. Explain how CSS variables work.**
   
            CSS variables, also known as custom properties, allow you to define values in one place and reuse them throughout your CSS. This helps make your code more maintainable, easier to update, and flexible, especially when working with complex designs.

            CSS variables are defined using the -- prefix and are typically declared within a :root selector so they can be used globally. However, they can also be defined within any specific selector for local use.

   **example:**
      
         :root {
             --primary-color: #3498db;
             --font-size-large: 20px;
         }        
                   

**22. what is default value in css?**

                In CSS, a default value is the initial or predefined value that a CSS property will take if no specific value is assigned to it by the developer. Every CSS property has a default value that the browser applies automatically when the property isn't explicitly set.


**23. Approaching Cross-Browser Compatibility Issues in CSS:**

                Cross-browser compatibility is about ensuring that a website looks and works consistently across different browsers. Here are common strategies and techniques to handle cross-browser CSS issues:


   **Example:** 
        
        * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
        }                


**24. what is  specificity in CSS?**
        
   **(i)** Element selector 
   **(ii)** id selector
   **(iii)** class selector
   **(iv)** inline style


**25. What are CSS Grid and Flexbox, and how do they differ?**

   **CSS Grid:** A two-dimensional layout system that allows you to design both rows and columns. It provides more control over complex layouts with grid lines and areas like dashboards,gallery pages etc.., 

   **Flexbox:** A one-dimensional layout system that arranges items in either a row or a column. It is useful for simpler, linear layouts and is more flexible with item alignment and distribution.


**26. .what is universal selector.**

     The universal selector in CSS is represented by the * symbol and is used to select all elements on a web page. It applies the specified styles to every element, unless those elements are overridden by more specific selectors.

      In this case, the universal selector resets the margin and padding to 0 and applies the box-sizing property to all elements on the page.

   **Example:**
       * {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
        }   


**27. How many tags can be used to separate a section of texts?**

   **<br> tag -** Usually **<br>** tag is used to separate the line of text. It breaks the current line and conveys the flow to the next line

   **<p> tag -** The **<p>** tag contains the text in the form of a new paragraph.

   **<blockquote> tag -** It is used to define a large quoted section. If you have a large quotation, then put the entire text within **<blockquote>.............</blockquote>** tag. 


**28. What does margin: 40px 100px 120px 80px signify?**

   **The shorthand notation margin:** 40px 100px 120px 80px; in CSS sets the margin for each side of an element in a clockwise order, starting from the top.
   
   **Here's what each value represents:**
       
        Top margin: 40px
        Right margin: 100px
        Bottom margin: 120px
        Left margin: 80px

        This means that the element will have 40 pixels of space on the top, 100 pixels on the right, 120 pixels at the bottom, and 80 pixels on the left.   
        

**29. CSS Sprites**  
                CSS Sprites are a technique used in web development to optimize web page loading by combining multiple images into a single image file. This helps reduce the number of HTTP requests to the server, making the page load faster. Instead of loading each image separately, CSS is used to display different portions of the combined image, called a sprite, as needed.

   **Example:**

                /* Example CSS */
                .sprite {
                  background-image: url('icons-sprite.png');
                  width: 32px; /* Width of a single icon */
                  height: 32px; /* Height of a single icon */
                  display: inline-block;
                }
                
                .home-icon {
                  background-position: 0 0; /* Top-left corner */
                }
                
                .search-icon {
                  background-position: -32px 0; /* Shift 32px to the right */
                }
                
                .settings-icon {
                  background-position: -64px 0; /* Shift 64px to the right */
                }


**30. CSS Sprites**

                CSS Sprites is a technique that combines multiple images into a single image file to reduce the number of HTTP requests made by a webpage, thereby improving load times and performance.

   **Example:** If you have three icons: icon1.png, icon2.png, and icon3.png, you can combine them into one image file called sprites.png. You can then use CSS to display specific icons by adjusting the background-position.

   **eg,**

                //html:
                        <div class="icon1"></div>
                        <div class="icon2"></div>
                        <div class="icon3"></div>

                //css:
                        .icon1 {
                          background-image: url('sprites.png');
                          background-position: 0 0; /* Position for icon1 */
                        }
                        
                        .icon2 {
                          background-image: url('sprites.png');
                          background-position: -50px 0; /* Position for icon2 */
                        }
                        
                        .icon3 {
                          background-image: url('sprites.png');
                          background-position: -100px 0; /* Position for icon3 */
                        }
                

**31.  What are the limitations of CSS?**

   **Disadvantages of CSS are given below:**

   **- Browser Compatibility:**   Some style selectors are supported and some are not. We have to determine which style is supported or not using the @support selector).

   **- Cross Browser issue:**   Some selectors behave differently in a different browser).

   **- There is no parent selector:** Currently, Using CSS, you can’t select a parent tag.
