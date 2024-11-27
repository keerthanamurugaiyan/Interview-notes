1.  **What is the Bootstrap grid system?**

**Ans:**     The Bootstrap grid system uses a 12-column layout to build responsive layouts. It divides the page into a series of rows and columns, allowing for flexible and fluid layouts.

2.   **What do yo know about the Bootstrap grid system?**

**Ans :**  The Bootstrap Grid System is a mobile-first, responsive grid system that scales up to 12 columns as the device or viewport size grows.

**There are five classes in the Bootstrap grid system :**

**Ans:**

    • col- for extra small devices, whose screen width is less than 576px.
    • col-sm- small devices, whose screen width is equal to or greater than 576px.
    • col-md- medium devices, whose screen width is equal to or greater than 768px.
    • col-lg- large devices, whose screen width is equal to or greater than 992px.
    • col-xl- extra large devices, whose screen width is equal to or greater than 1200px.


3.    **Why do we need to use bootstrap?**
    
     **a.**  it is a free and open source web designing frame work.
     
     **b**  Bootstrap has the support of all the web browsers like internet explorer, google chrome, firefox, opera, safari etc...
     
     **c**  it is a very powerful mobile first frontend frame work.
     
     **d**  also it is very easy to start as one needs to have an idea of html and css only to work with it.
     
     **e**  we can design a responsive website through it which adjust to desktop, table, and mobile.
     
     **f**  it comprises functional buitt-in components which are easy to customize.      


**4. What are the key components of Bootstrap?**

        Key components include the Grid System, Typography, Forms, Buttons, Navigation Bars, Modals, Alerts, and more.

     
**5. What is Bootstrap utilities?**

    Bootstrap utilities are pre-defined classes that allow you to apply common CSS styles quickly and easily. They cover various properties like:

   **1.** Spacing (margin, padding): .m-, .mx-, .my-, .p-, .px-, .py-
   **2.** Sizing: .w-, .h-
   **3.** Text: .text-, .font-,
   **4.** Color: .bg-, .text-
   **5.** Borders: .border-, .rounded-
   **6.** Display: .d-, .flex-, .inline-
   **7.** Position: .position-, .fixed-, .absolute-
   **8.** Visibility: .visible-, .invisible-

  **Examples:**

    - .m-3 (margin: 3 units)
    - .p-2 (padding: 2 units)
    - .text-center (text-align: center)
    - .bg-primary (background-color: primary)
    - .d-none (display: none)

Utilities simplify CSS coding, making development faster and more efficient.  


**6. How do you include Bootstrap in a project?**

    You can include Bootstrap in your project either by using a Content Delivery Network (CDN) or by downloading the Bootstrap files and including them in your project. For CDN, add the Bootstrap CSS and JS links in the <head> and before the closing **</body>** tag, respectively.


 **7. What is a Bootstrap card and how is it used?**
        
        A Bootstrap card is a versatile component that helps organize and display various types of content in a structured format. You use the .card class to create the basic card layout. Inside the card, you can use .card-header for the top section, .card-body for the main content, and .card-footer for the bottom section, making it easy to present information clearly and neatly.   


**8. How do you integrate Bootstrap with a custom theme?**

         By customizing Bootstrap’s variables, overriding default styles with your own CSS, and integrating the theme’s design elements with Bootstrap’s components.


**9. What are the different Navbar Components in Bootstrap?**

   - **Navbar Brand:** Displays the website's name/logo, typically on the left. Use the `.navbar-brand` class.
   - **Navbar Links:** Clickable links to navigate the site. Use `.nav-link` inside `.navbar-nav`.
   - **Dropdowns:** Groups related links under one item. Use `.dropdown` and `.dropdown-menu`.
   - **Navbar Toggler:** A "hamburger" icon to toggle the navbar on small screens. Use `.navbar-toggler`.
   - **Collapse Content:** Shows/hides content to save space on small screens. Wrap it in `.collapse`.
   - **Forms:** Embed forms like search or login in the navbar. Use Bootstrap form classes (e.g., `.form-inline`).
   - **Navbar Text:** Adds text like welcome messages. Use `.navbar-text`.


**10. what is bootstrap utility classes?**

            Bootstrap utility classes are predefined CSS classes provided by the Bootstrap framework that enable developers to quickly apply specific styles to elements without writing custom CSS. These classes cover a wide range of styling needs and help in speeding up the development process by providing common, reusable styling options.  


**11.  What is a Bootstrap modal and how do you use it?**

            A modal is a popup window that is displayed on top of the current page. You can create a modal using the modal class and trigger it with a button or link using data-toggle="modal" and data-target="#modalId" attributes  


**12. What is a navbar in Bootstrap?**

        A navbar (navigation bar) in Bootstrap is a component that helps create a responsive navigation menu for a website. It typically contains links to different sections of the website, making it easy for users to navigate through the content.            


**13. What is a breadcrumb in Bootstrap?**

A **breadcrumb** in Bootstrap is a navigation tool that shows the path of pages the user has visited to reach the current page. It helps users understand where they are within a website.

For example, if a user is on a blog post page, the breadcrumb might look like:
`Home > Blog > Post`

**In Bootstrap:**
- A breadcrumb is made using an **unordered list** (`<ul>`) with the class `.breadcrumb`.
- Bootstrap's **CSS** will automatically add the separators (like `>`).

**Example Code**:
```html
<nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="#">Home</a></li>
    <li class="breadcrumb-item"><a href="#">Library</a></li>
    <li class="breadcrumb-item active" aria-current="page">Data</li>
  </ol>
</nav>
```

Here, "Home" and "Library" are links, while "Data" is the current page.


**14. Display Headings :**

        Display headings are used to stand out more than normal headings (larger font-size and lighter font-weight), and there are six classes to choose from: .display-1 to .display-6:

**Example :**
               
                <div class="container mt-3">
                  <h1>Display Headings</h1>
                
                  <h1 class="display-1">Display 1</h1>
                  <h1 class="display-2">Display 2</h1>
                  <h1 class="display-3">Display 3</h1>
                  <h1 class="display-4">Display 4</h1>
                  <h1 class="display-5">Display 5</h1>
                  <h1 class="display-6">Display 6</h1>
                </div>
