**1.Difference between Static web pages and Dynamic web pages.**

**Ans:**

**I. Static web page:**
        The content of static web page is fixed and does not chance unless the page's HTML code is manually updated.

**(eg) :**  Portfolio

**II. Dynamic web page:**
    Dynamic web pages are generated in real-time based on user interactions. Database queries or other criteria , The content can change without altering the pages HTML code.

**(eg) :** Flipcart , You tube


**2.What are pseudo-classes and pseudo-elements? Can you provide examples?**

**Ans:**
    
   **(i)  Pseudo-classes:**  Apply styles to elements based on their state **(e.g., :hover for when an element is hovered over, :focus for when an element is focused).**
    
   **(i)  Pseudo-elements:**  Target specific parts of an element **(e.g., ::before to insert content before an element's content, ::after to insert content after).**


**3. What are the tools used for api testing?**
    
   **•** Soapui pro
   **•** Postman
   **•** Alertsite api monitoring   


**4. What is Api?**
    
   An API **(Application Programming Interface)** is a set of rules that allows different software applications to communicate with each other, enabling them to request and exchange data. It's like a bridge that connects different systems, allowing them to work together.


**5. What is Toasts ?**

Key Characteristics of Toasts:

Non-intrusive:Toasts do not block the user interface and automatically disappear after a short time.

Customizable :You can style and position toasts as needed, including adding headers,body content, and different visual styles.

Auto-dismissal: They can be set to disappear automatically after a set time or can be dismissed by the user.

 **Example:** success and error. 


**6. Explain the difference between React and Angular?**
 
   **React.js:-**
      **•**	React.js is a JavaScript library. As it indicates react js updates only the virtual DOM is present and the data flow is always in a single direction.
      **•**	React.js is more simplified as it follows MVC ie., Model View Control.
      **•**	It is highly scalable.
      **•**	It supports Uni-directional data binding which is one-way data binding.
      **•**	It has a virtual DOM.     

   **Angular:-**   
      **•**	Angular is a framework. Angular updates the Real DOM and the data flow is ensured in the architecture in both directions.
      **•**	The architecture is complex as it follows MVVM models ie., Model View-ViewModel. 
      **•**	It is less scalable than React JS.
      **•**	It supports Bi-directional data binding which is two way data binding.
      **•**	It has regular DOM.  


**7. Is there any relation between Java and JavaScript?**
       
       No, they are entirely two different programming languages and have nothing to do with each other. But both of them are Object Oriented Programming languages and like many other languages, they follow similar syntax for basic features(if, else, for, switch, break, continue etc).          


**8. 1. How an HTTP Server Works:**

   **Client Sends a Request:**
         The process begins when a client (like a web browser) sends an HTTP request to the server. This request includes details like the method (GET, POST, etc.), the URL, headers, and sometimes a body (for POST requests).

   **Server Receives the Request:**
         The HTTP server listens on a specific port (usually port 80 for HTTP and 443 for HTTPS). When it receives a request, it processes the incoming data.

   **Server Processes the Request:**
         The server determines what action to take based on the request. For example, if a user requests a webpage, the server might retrieve the HTML file associated with that URL or generate content dynamically using a server-side language like Node.js, PHP, or Python.
   
   **Server Sends a Response:**
         After processing, the server sends an HTTP response back to the client. This response includes a status code (e.g., 200 for success, 404 for not found), headers, and a body (which could be an HTML page, JSON data, an image, etc.).

   **Client Receives the Response:**
         The client processes the response and displays the content to the user or handles the data accordingly.


**9. What is the fetch API?**
         
         The fetch API is a modern JavaScript interface that allows you to make network requests, such as retrieving data from a server or sending data to a server. It provides a more powerful and flexible way to work with HTTP requests and responses compared to older techniques like XMLHttpRequest.


**10. What is Authentication and Authorization?**
         
         Authentication and authorization are both important security processes that work together to keep applications, systems, and data safe: 
 
   **Authentication:**
         Verifies the identity of a user or device to ensure that only authorized users can access systems, services, and resources. 
 
   **Authorization:**
         Determines what actions, resources, or services a user is allowed to perform, based on their level of access.


**11. what is waterfall model and agile model ?**

   **(ii) Waterfall Model:-**

   **Sequential Process:**
               
                The Waterfall model is linear and sequential. Each phase must be completed before moving to the next (e.g., Requirements → Design → Implementation → Testing → Deployment → Maintenance).

   **Rigid Structure:**
           
                Once a phase is completed, it's difficult to go back and make changes. There’s little room for flexibility or changes during development.

   **Documentation-heavy:**
                   
                   This model requires comprehensive documentation at every stage, ensuring that each phase is well documented.
Best for Small Projects: Waterfall works best for projects with clearly defined requirements that are unlikely to change.
Testing at the End: Testing is done only after the entire development process is complete, which may delay discovering issues.

   **(i) Agile Model:-**

   **Iterative and Incremental:**
                   
                   Agile is flexible and emphasizes iterative development. It breaks the project into small, manageable units (called sprints), where each sprint focuses on developing a small part of the functionality.

   **Flexibility:**
                   
                   Agile allows changes to be made throughout the project, even late in the development cycle. Teams can adapt to changing requirements.

   **Continuous Collaboration:**
   
                   Agile encourages regular communication and collaboration between developers and stakeholders to ensure the project is on track.

   **Less Documentation:**
                   
                   Instead of heavy documentation, Agile focuses on working software and direct collaboration, though some level of documentation is still maintained.

   **Early Testing:**
   
                   Testing is done throughout the project at the end of each sprint, which helps identify and fix issues early.


**12. What is the difference between HTML and React event handling?**

 **i, Event Naming Convention**:
   
   - In *HTML*, event names are written in *lowercase*.

     html
             <button onclick="activateLasers()"></button>
     
   - In *React*, event names follow the *camelCase* convention.

     jsx

             <button onClick={activateLasers}></button>
     
 **ii, Preventing Default Behavior**:
   
   - In *HTML*, you can return `false` to stop the default behavior of an event.

     html

             <a href="#" onclick="console.log('The link was clicked.'); return false;"></a>
     
   - In *React*, you must use the `preventDefault()` function explicitly to stop the default behavior.

     jsx

             function handleClick(event) {
               event.preventDefault();
               console.log('The link was clicked.');
             }
             <a href="#" onClick={handleClick}></a>
     
 **iii, Calling Functions**:
   
   - In *HTML*, you directly call a function by adding `()` after the function name.

      html

             <button onclick="activateLasers()"></button>
     
   - In *React*, you pass the function name without `()` when assigning it to an event handler. React will call the function when the event occurs.

     jsx

             <button onClick={activateLasers}></button>     

   **In summary:**

        - React uses camelCase for event names, requires `preventDefault()` for stopping default actions, and functions are passed without `()` in event handlers.


**13. What is WebRTC?**

                WebRTC stands for Web Real-Time Communication. It is a free and open-source project that enables real-time communication capabilities within browsers and applications. It provides protocols and APIs for peer-to-peer audio, video, and data sharing without the need for additional plugins or software installations. WebRTC allows users to have seamless voice and video calls, as well as share screens and transfer files directly from their web browsers. It has become popular for building applications such as video conferencing, live streaming, and real-time collaboration tools.


**14. What is the difference between HTML and CSS?**

   **HTML:**  Provides the structure and content of a web page. It defines elements like headings, paragraphs, images, links, and forms.

   **Example:** <p>Hello, world!</p>

   **CSS:** Provides the style and appearance of the HTML content, controlling layout, colors, fonts, and spacing.

   **Example:** 
                p {
                  color: blue;
                  font-size: 20px;
                }


**15. Explain the difference between TCP and UDP with examples.**

### TCP (Transmission Control Protocol):

   - **Example:** Sending a file online with confirmation if it’s received correctly.
   - **Reliable:** with feedback, uses a three-step "handshake" to start.

  ### TCP Three-Way Handshake:

   - **SYN**: The sender says, “Ready?” (sends a SYN (synchronize) packet).
   - **SYN-ACK**: The receiver replies, “Yes, I’m ready” (sends SYN-ACK (synchronize acknowledgment) packet).
   - **ACK**: The sender confirms, “Great, let’s start!” (sends ACK (acknowledgment) packet).

 This establishes a reliable connection.

  ### UDP (User Datagram Protocol):

   - **Example**: Live video or gaming, where speed is key.
   - **Fast** but no feedback, so less reliable. 

 **In summary:**

   - **TCP** = Reliable, feedback.
   - **UDP** = Fast, no feedback.


**16. What is Authentication and authorization ?**

  **i,Authentication**

   **Definition:** Authentication is the process of verifying the identity of a user. It answers the question, "Who are you?"

   **Purpose:** Ensures that the user is who they claim to be.

   **Process:** Typically involves logging in with credentials like username/email and password. Other methods include OTPs, biometric scans, etc.

   **Example in JavaScript:** Using Firebase Authentication or Passport.js to verify a user’s identity.

                // Example using JSON Web Token (JWT) for authentication
                const token = jwt.sign({ userId: user.id }, "yourSecretKey");


  **ii,Authorization:**

   **Definition:** Authorization is the process of determining whether a user has permission to access a resource or perform an action. It answers the question, "What are you allowed to do?"

   **Purpose:** Ensures that the authenticated user has permission to access specific data or perform actions.

   **Process:** Usually takes place after authentication. It checks roles or permissions assigned to the user.

   **Example in JavaScript:** Checking a user's role (e.g., "admin" or "user") before allowing them access to a resource.

                        // Example for checking authorization
                        if (user.role === 'admin') {
                          // grant access
                        } else {
                          // deny access
                        }

                        
**17. What is the difference between a framework and a library?**

   **i,Framework:**
                A framework is like a full setup. It gives you rules on how to code, and you have to follow those rules. In a framework, most of the control is with the framework itself, so your freedom is somewhat limited.

   **Example :** Angular. (It has predefined rules for how to connect pages, handle data, and so on.)

   **ii,Library:**
                A library is more like a tool. You can use it for whatever purpose you want, giving you a lot of freedom. Here, the control is entirely with you, and the library just acts as support. There are no strict rules, and you decide how to use it.

   **Example:** React. (You can decide completely how you want to use React.)

   
