1. **What are Attributes?**
    
   **Ans:** each element have attributes
             changes element behaviours
             Attributes are types:
             Types:
             Generic : class, id, style,,
             Specific : src ,href, ,,,

2. **Difference between subscript and superscript in html**

**Ans:**

**I.Subscript:**
      
   **Position:** Characters are placed slightly below the baseline of the surrounding text.
      
   **Common Uses:**  To represent array elements (e.g., array[i], where "i" might be subscripted in some notations).
      
   **Example:**  Subscript: **H₂O**

**II.Superscript:**

   **Position:** Characters are placed slightly above the normal line of text.
      
   **Common Uses:**  To denote exponents (e.g., x², where the "2" is superscripted).
      Particularly for representing units and constants (e.g., m² for square meters).

   **Example:**    Superscript: **E = mc²**


3.  **Whats is forms in HTML ?**

         Forms are essential for collecting user information, conducting surveys, processing orders, and more. They are defined using the <form> element and typically include various input elements like text fields, checkboxes, radio buttons, and buttons.

      **Input Elements:**  These are the fields where users can enter data. Common types include:

      **Text Input (<input type="text">):**  For single-line text input.
      **Password Input (<input type="password">):**  For password fields where input is obscured.
      **Checkbox (<input type="checkbox">):**  For selecting one or more options.
      **Radio Button (<input type="radio">):**  For selecting a single option from a group.
      **Submit Button (<input type="submit">):**  For submitting the form data.  


**4.   Events in Html?**

**Ans:**

**(i) Animationstart:**
      The  event occurs when a CSS animation starts.

**(ii) Animationiteration :**
      The animationiteration event occurs when a CSS animation is repeated.

**(iii) Animationend:**
      The animationend event occurs when a CSS animation has completed.


**5. Why do we need to use HTML entities?**

            We use HTML entities to ensure that special characters are displayed correctly on a webpage. For example, if you want to display a less-than sign (<) on a webpage, you need to use &lt; to avoid it being interpreted as the start of an HTML tag 


**6. What is the advantage of collapsing white space?**

            In HTML, a blank sequence of whitespace characters is treated as a single space character, Because the browser collapses multiple spaces into a single space character and this helps a developer to indent lines of text without worrying about multiple spaces and maintain readability and understandability of HTML codes.      


**7. Difference between intenal link and external link:**

   **Internal Link:**
            An internal link navigates to another page or section within the same website.
   
   **Syntax:**
            <a href="about.html">About Us</a>
            This link takes the user to the "about.html" page within the same website.

   **External Link:**
            An external link takes you to a different website or domain.
   
   **Syntax:**
            <a href=""https://www.google.com" target="_blank">Go to Google</a>
            This link opens an external website, like Google, often in a new tab if you use target="_blank"  .
  
   **<a> tag:**
       The anchor tag creates the link.            


**8.  In how many ways you can display HTML elements?**

   **inline:**     Using this we can display any block-level element as an inline element. The height and width attribute values of the element will not affect.

   **block:**     using this, we can display any inline element as a block-level element. 

   **inline-block:**     This property is similar to inline, except by using the display as inline-block, we can actually format the element using height and width values.

   **flex:**     It displays the container and element as a flexible structure. It follows flexbox property.

   **inline-flex:**     It displays the flex container as an inline element while its content follows the flexbox properties.

   **grid:**     It displays the HTML elements as a grid container.

   **none:**     Using this property we can hide the HTML element.


   **9. 1. What is the use of an iframe tag?**
    
                  In HTML, the <iframe> tag is used to embed another HTML document within the current document. It's like showing another webpage inside your webpage. Think of it as creating a window inside your page, and through that window, you can see another web page or content.

   **Example:**
          
          <iframe src="https://www.example.com" width="600" height="400"></iframe>


**10. How to create a hyperlink in HTML?**

        The HTML provides an anchor tag to create a hyperlink that links one page to another page. These tags can appear in any of the following ways:

   **Unvisited link** - It is displayed, underlined and blue.
   
   **Visited link** - It is displayed, underlined and purple.
   
   **Active link** - It is displayed, underlined and red.

   

**11. Different kinds of Doctypes:**

 ### i. **Strict Doctype**

   - **Purpose**: Used for modern, standards-compliant HTML. 

   - **Allows**: Only current HTML elements; no deprecated features.

   - **Example**:
  
          ```html
          <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
          ```

   ### ii. **Transitional Doctype**
   
   - **Purpose**: Used for documents that may still include older HTML features.
   
   - **Allows**: Deprecated elements and attributes, making it easier to transition to modern standards.
   
   - **Example**:

     ```html
          <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
          ```

   ### iii. **Frameset Doctype**

   - **Purpose**: Used for documents that use frames to split the page into sections.
   
   - **Allows**: Frames but does not support the `<body>` tag.
   
   - **Example**:

         ```html
          <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
          ```

   ### **HTML5 Doctype**

   - **Purpose**: The simplified declaration for HTML5.

   - **Example**:

         ```html
          <!DOCTYPE html>
          ```


**12. html tags**

   **I. sourse tag:**

            The <source> tag is used in HTML to provide multiple media options (like videos or audio files) to ensure compatibility across different browsers. It helps the browser pick a format it supports.

   **II. embed tag:**

            The <embed> element is used to embed external content or applications, such as videos, audio, or interactive content (like Flash files). It is commonly used for multimedia purposes.

   **III. canvas tag:**

            The <canvas> element is used to draw graphics on a web page using JavaScript. It allows for rendering 2D shapes, images, and even animations.

            
**13. What are void elements in HTML?**

            Void elements in HTML are elements that do not require a closing tag because they are self-contained. These elements do not wrap any content and are used for structural or media purposes. Examples include:

   **<br /> -**  Inserts a line break.
   
   **<img /> -** Embeds an image.
   
   **<hr /> -** Creates a horizontal line or thematic break.

   **<input /> -** Creates an input field in a form.

   **<meta /> -** Provides metadata about the HTML document.

   **<link /> -** Links to an external resource like a stylesheet.

   **<source /> -** Specifies multiple media resources for elements like <video> or <audio>.

   **<area /> -** Defines an area in an image map.
   
   **<base /> -** Specifies the base URL for all relative URLs in a document.

        These elements are self-closing because they don't have any content, so there’s no need for an opening and closing pair. They are often called "self-closing tags."


**14. What is Microdata in HTML5, and how does it help search engines?**

**Microdata in HTML5** allows you to add extra information (metadata) to web content, helping search engines understand it better. It organizes content into items, each with properties (name-value pairs). Most search engines like Google and Bing use the schema.org vocabulary to interpret microdata.

### Key Attributes:

   - **itemscope**: Defines the scope of an item.
   - **itemtype**: Specifies the vocabulary URL (like `http://schema.org/SoftwareApplication`).
   - **itemprop**: Adds properties to an item (like name, rating, price).
   - **itemid**: A unique identifier for the item.
- **itemref**: Points to other element IDs with additional properties.

### Example:

                <div itemscope itemtype="http://schema.org/SoftwareApplication">
                  <span itemprop="name">Interviewbit Games</span> -
                  REQUIRES <span itemprop="operatingSystem">ANDROID</span><br>
                  <div itemprop="aggregateRating" itemscope itemtype="http://schema.org/AggregateRating">
                    RATING: <span itemprop="ratingValue">4.6</span> (
                    <span itemprop="ratingCount">8864</span> ratings)
                  </div>
                  <div itemprop="offers" itemscope itemtype="http://schema.org/Offer">
                    Price: Rs.<span itemprop="price">1.00</span>
                    <meta itemprop="priceCurrency" content="INR" />
                  </div>
                </div>

**Result**: This helps Google parse the app's name, OS requirement, rating, and price directly from the webpage.

**15. Difference between Subscript and Superscript in HTML**

**i. Subscript:**

   - **Position:** Characters are placed slightly below the baseline of the surrounding text.
   - **HTML Tag:** `<sub>...</sub>`
   - **Common Uses:**
      - Representing array elements in notations, like `array[i]`, where "i" is subscripted.
      - Writing chemical formulas, such as `H₂O` (water) or `CO₂` (carbon dioxide).
      - Denoting certain mathematical or scientific variables and constants.
   - **Example:** `H<sub>2</sub>O` <!-- displays "H₂O" -->

**ii. Superscript:**

   - **Position:** Characters are placed slightly above the baseline of the surrounding text.
   - **HTML Tag:** `<sup>...</sup>`
   - **Common Uses:**
      - Denoting exponents, like `x²` (where "2" is superscripted).
      - Indicating units and constants, such as `m²` for square meters or `E = mc²`.
   - **Example:** `x<sup>2</sup>` <!-- displays "x²" -->


**16. How many `<h1>` tags can be used in a webpage?**  
  
- **Best practice** is to use **only one `<h1>` tag** per webpage.  
- This is because `<h1>` represents the **main heading** of the page, helping search engines and users identify the page's primary topic.  
- Using multiple `<h1>` tags can confuse search engines and affect SEO.  

 
