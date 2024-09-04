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


.                   