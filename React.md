**1.  what is useState?**

**Ans:** 

      The useState hook is a function that allows you to add state to functional components in React. It returns an array with two elements: the current state value and a function to update that value.

**(i) How does useState handle state updates? Is it synchronous or asynchronous:-**
      
      State updates in React using useState are asynchronous. This means that the state may not update immediately after calling the state updater function. React batches state updates for performance optimization.

**(ii) What happens if you pass a function to setState instead of a value:-**

      Passing a function to the state updater function allows you to access the current state value and update it based on that. This is particularly useful when updating state based on the previous state value.

**(iii) How do you use the useState hook to manage an object or array state:-**

      To manage complex state like objects or arrays, you can use the state updater function to make immutable updates.


**2.What is the difference between framework and library?**

   **(i)**  A library is a collection of pre-written code that developers can use to optimize tasks it provides specific functionalities that you can call when needed. In a library the developer is in control of the application flow. They choose when and where to call the library functions.. **Eg. React.**
      
   **(ii)** A framewok is a comprehensive provides a foundation and structure for developing software applications. It dedicates a specify way of organizing and developing an application. 
       
    In a framework, the framework itself is in control of the applications flow. It calls the developers code when necessary. This is often referred as "Inversion of control"**..Eg.Angular.**


**3.Differences between props and state?**             

   **• Props:** Used to pass data from parent to child components; they are immutable and read-only.
      
   **• State:** Managed within the component; it is mutable and can be both read and modified.

**(i)  Props:**
            
   **• Data Flow:**  Data is passed from a parent component to a child component.
    
   **• Immutability:**  Props are immutable, meaning they cannot be modified by the child component.
    
   **• Usage:**  Props can be used in both functional and class components.
    
   **• Access:**  Props are read-only.

**(ii)  State:**
            
   **• Data Flow:** State is managed within the component itself and is not passed to other components directly.
           
   **• Mutability:** State is mutable, meaning it can be modified within the component.
     
   **• Usage:** State can be used in class components or with the useState hook in functional components.
   
   **• Access:** State is both readable and writable.    


**4. What is JSX?**

      JSX stands for JavaScript XML. It allows us to write HTML inside JavaScript and place them in the DOM without using functions like appendChild( ) or createElement( ).


  **Examples:**

   **With JSX:**

      import React from 'react';
      import ReactDOM from 'react-dom/client';

      const myElement = <h1>I Love JSX!</h1>;

      const root = ReactDOM.createRoot(document.getElementById('root'));
      root.render(myElement);

   **Without JSX:**

      import React from 'react';
      import ReactDOM from 'react-dom/client';

      const myElement = React.createElement('h1', {}, 'I do not use JSX!');

      const root = ReactDOM.createRoot(document.getElementById('root'));
      root.render(myElement);        


**5. (i) what is redux saga**

            Redux Saga is a middleware library that helps manage side effects in Redux applications, such as data fetching or communicating with external services.It allows you to handle complex asynchronous operations in a more predictable and efficient way. Redux Saga works by using generator functions, which enable you to write asynchronous code that looks synchronous, making it easier to read, test, and maintain.

   **(ii) What is the use of Redux in React?**

            Redux helps manage the state of your entire React application in a centralized way. Instead of each component managing its own state, Redux allows you to keep the application’s state in one place (the store). This makes it easier to handle complex applications, share data between components, and maintain the state across different parts of your app.

   
**(iii) What is difference between ReactJS and Redux:**      

   **ReactJS:**
      
      Use React state system for simple and local state that does not need to be shared with other components or persisted across sessions. For example, UI state such as form inputs, dropdown menus, modals, etc. 
      
   **Redux:**
      
      Use Redux for complex and global state that needs to be shared with other components or persisted across sessions.  For example, user authentication status or data fetched from an API that multiple components need to access.


 6.   **differentiate between state and Redux:**

   **State:** 
      
      This is a way to keep track of data within a single React component. Each component can have its own state, and when the state changes, the component re-renders to reflect those changes. Think of it as a local storage for each component's data.

   **Redux:** 
      
      This is a library used for managing state globally across your entire application. Instead of each component having its own state, Redux provides a centralized place (called a store) where all the application state is stored. This makes it easier to manage and share state across different components without prop drilling (passing data down through props).     

   **In summary:**

       **- State** is for local, component-specific data.
       **- Redux** is for global, application-wide data.


**7. What is React Router?**
 
      React Router is a libreary that enables navigation among views 
      in a React application , allowing for the development of single-page applications
 
 **Eg:**  Flipkart 
          Amazon
          Facebook


**8.  How do you create forms in React?**

      import React, { useState } from 'react';

      function MyForm() {
      const [formData, setFormData] = useState({
         name: '',
         email: ''
      });
      const handleChange = (e) => {
         const { name, value } = e.target;
         setFormData({
            ...formData,
            [name]: value
         });
      };
      const handleSubmit = (e) => {
         e.preventDefault();
         console.log('Form submitted:', formData);
      };

      return (
         <form onSubmit={handleSubmit}>
            <div>
            <label>Name:</label>
            <input
               type="text"
               name="name"
               value={formData.name}
               onChange={handleChange}
            />
            </div>
            <div>
            <label>Email:</label>
            <input
               type="email"
               name="email"
               value={formData.email}
               onChange={handleChange}
            />
            </div>
            <button type="submit">Submit</button>
         </form>
      );
      }

      export default MyForm;


**9. What is the difference between  React and React native?**

   **React:**
      ReactJS, is a JavaScript library for building user interfaces, particularly for web applications. It is primarily used to create dynamic and interactive web pages. It perform in web. Uses CSS for styling. Styles are applied via class names or inline styles.

   **React Native:**
      React Native is a framework for building mobile applications using JavaScript and React. 
      It allows developers to create cross-platform mobile apps for iOS and Android using a single codebase. 
      It perform in Mobile (iOS and Android)Uses JavaScript objects to style components.
      Styling is done using a subset of CSS properties, but not all CSS properties are available, and the styling syntax is different (StyleSheet.create() is commonly used).
      Uses a different set of components that map directly to native UI components, such as <View>, <Text>, <Button>, etc., instead of standard HTML elements like <div>, <span>, or <button>.

 
 **10. Explain the difference between React and Angular?**

   **React.js**
      •	React.js is a JavaScript library. As it indicates react js updates only the virtual DOM is present and the data flow is always in a single direction.
      •	React.js is more simplified as it follows MVC ie., Model View Control.
      •	It is highly scalable.
      •	It supports Uni-directional data binding which is one-way data binding.
      •	It has a virtual DOM.     

   **Angular**
      •	Angular is a framework. Angular updates the Real DOM and the data flow is ensured in the architecture in both directions.
      •	The architecture is complex as it follows MVVM models ie., Model View-ViewModel. 
      •	It is less scalable than React JS.
      •	It supports Bi-directional data binding which is two way data binding.
      •	It has regular DOM.


**11.  What is one way binding in react?**

            In React, one-way binding (also known as one-way data flow) refers to the way data flows in a single direction from the parent component to the child component. It is a key concept that ensures that changes in the state of a component affect the user interface (UI) predictably.            


**12.  What are keys in React?**
         
         A key is a special string attribute that needs to be included when using lists of elements.

   **The "REACT WAY" to render a list**  
            **(i)**Use array.map
            **(ii)**Note a for loop
            **(iii)**Give each item a unique key
            **(iv)**Aviod using array index as the key       

   **Example of a list using key -**

         const ids = [1,2,3,4,5];
         const listElements = ids.map((id)=>{
         return(
         <li key={id.toString()}>
         {id}
         </li>
         )
         })

   **Importance of keys -**

     • Keys help react identify which elements were added, changed or removed.
     • Keys should be given to array elements for providing a unique identity for each element.
     • Without keys, React does not understand the order or uniqueness of each element.
     • With keys, React has an idea of which particular element was deleted, edited, and added.
     • Keys are generally used for displaying a list of data coming from an API.
   
   **Note-** Keys used within arrays should be unique among siblings. They need not be globally unique.


**13. Explain the building blocks of React?**

   The five main building blocks of React are:

   **Components:** These are reusable blocks of code that return HTML.
   
   **JSX:** It stands for JavaScript and XML and allows you to write HTML in React.
   
   **Props and State:** props are like function parameters and State is similar to variables.
   
   **Context:** This allows data to be passed through components as props in a hierarchy.
   
   **Virtual DOM:** It is a lightweight copy of the actual DOM which makes DOM manipulation easier. 


**14. What are fragments?**
         
         It's a common pattern or practice in React for a component to return multiple elements. Fragments let you group a list of children without adding extra nodes to the DOM. You need to use either <Fragment> or a shorter syntax having empty tag (<></>).


**15. React Hooks:** 

   **(i) useState Hook**
            
            useState allows you to add state to a function component. It returns two values: the current state and a function to update it.

   **(ii). useEffect Hook:**
            
            useEffect lets you perform side effects in function components, such as data fetching, subscriptions, or manually changing the DOM.

   **(iii). useContext Hook:**
            
            useContext allows you to access React’s Context API, making it easier to pass data through a component tree without manually passing props at every level.

   **(iv). useReducer Hook:**

            useReducer is used for managing more complex state logic. It's an alternative to useState when state transitions are more involved.

   **(v). useRef Hook:**
            
            useRef is used to persist values across renders without causing a re-render when the value changes. It’s often used to reference DOM elements.   


**16. What is virtual DOM in React?**

            React uses Virtual DOM which is like a lightweight copy of the actual DOM(a virtual representation of the DOM). So for every object that exists in the original DOM, there is an object for that in React Virtual DOM. It is the same, but it does not have the power to directly change the layout of the document. Manipulating DOM is slow, but manipulating Virtual DOM is fast as nothing gets drawn on the screen. So each time there is a change in the state of our application, the virtual DOM gets updated first instead of the real DOM.            


**17. What npm stands for**

            npm stands for Node Package Manager. It's a tool that comes with Node.js and is used to manage libraries and packages in JavaScript projects.

  **Here's a simple breakdown of how npm works:**

   **Node:**
             Refers to Node.js, a runtime environment that allows JavaScript to run outside of the browser (e.g., on a server).

   **Package:**
               A package is a piece of reusable code, like a library, that you can install and use in your project.
  
   **Manager:**
               npm helps manage these packages, allowing you to easily install, update, and remove them.

            With npm, you can also create and share your own packages. It’s very common in JavaScript development to use npm to install things like libraries, frameworks, or tools for building applications.


**18. what are web components**

            Web Components are a set of standardized technologies in web development that allow developers to create reusable, encapsulated, and customizable UI elements. These components work natively in browsers without requiring external libraries or frameworks.

   **Benefits of Web Components:**

   **Reusabil8ity:** Components can be reused across different projects or pages.
   
   **Encapsulation:** Styles and scripts within the component are isolated, avoiding conflicts with the global page.
   
   **Compatibility:** Works with any framework (React, Vue, Angular) or without a framework, since it's a native browser technology.


**19.  What are components and their type in React?**

            A Component is one of the core building blocks of React. In other words, we can say that every application you will develop in React will be made up of pieces called components. Components make the task of building UIs much easier. 

   **In React, we mainly have two types of components:** 

   **Functional Components:**
               Functional components are simply javascript functions. We can create a functional component in React by writing a javascript function. 

   **Class Components:** 
               The class components are a little more complex than the functional components. The functional components are not aware of the other components in your program whereas the class components can work with each other. We can pass data from one class component to another class component.   


**20. What are keys in React and why do we need them?**

            The "key" is a special attribute used when working with arrays of 
            elements in React. It helps React keep track of changes, additions, 
            and removals in the array.
            
            When you're rendering a list of items, React needs a way to identify 
            each item uniquely. The "key" prop serves this purpose, allowing 
            React to efficiently update the user interface.    


**21. Why ReactDOM is separated from React?**

            ReactDOM was separated from React to promote modularity and maintainability of the library. Initially, React bundled both the core React library and the DOM-specific rendering logic. However, as React evolved to support multiple platforms (such as web, mobile, and even virtual reality), it became necessary to decouple the core functionality from the platform-specific rendering mechanisms. 


**22. What is conditional rendering in React?**

            Conditional rendering in React involves selectively rendering components based on specified conditions. By evaluating these conditions, developers can control which components are displayed, allowing for dynamic and responsive user interfaces in React applications.

            Let us look at this sample code to understand conditional rendering. 

            {isLoggedIn == false ? <DisplayLoggedOut /> : <DisplayLoggedIn />}

            Here if the boolean isLoggedIn is false then the DisplayLoggedOut component will be rendered otherwise DisplayLoggedIn component will be rendered.            


**23. What is Controlled Components?**

   **i)** In controlled components, form elements(like input, textareas, etc.)  are controlled by react state.

   **ii)** The Value of the form elements is bound to the state, and any change in the input updates the state via event handlers like onChange.

**What is UnControlled Components?**
 
   **i)** In uncontrolled components, form elements store their own state in the DOM, and React does not manage it directly.

   **ii)** You access the values of form elements using refs rather than React state.

   
**24. Explain the steps to create a react application?**

   **1.Install Node:**
            Before installing React, ensure that Node is installed on 
your computer. You can download it from Node.js

   **2. Create React App:**
            Open the terminal and run the following command to create 
a new React application (replace my-react-app with your 

   **preferred application name):**
            "npx create-react-app my-react-app"

   **3. Run the Application**
            In the terminal, run the following command to start the 

   **development server:**
            npm start


**25. what is the difference between element and component in react**

   **Element**

   **Definition:**
               A React element is an object representation of a DOM node. It is the simplest building block of a React application and describes what you want to see on the screen.

   **Component**

   **Definition:**
               A React component is a JavaScript function or class that can accept inputs (called props) and returns a React element (or elements). Components can manage their own state and lifecycle.

   **Types:** There are two main types of components:

   **Functional Components:** Simple functions that return a React element.

   **Class Components:** More complex components that can hold and manage state and lifecycle methods.


**26. What is higher-order component in React?**

            Higher-order components or HOC is the advanced method of reusing the component functionality logic. It simply takes the original component and returns the enhanced component. HOC are beneficial as they are easy to code and read. Also, helps to get rid of copying the same logic in every component.


**27. what is the diffference between takeEvery and takeLatest in redux saga?**

Here’s a concise 2-mark explanation of the difference between `takeEvery` and `takeLatest` in Redux Saga:

---

### **Difference between takeEvery and takeLatest:**

 **takeEvery:**

 - **Definition:** Allows multiple instances of a saga to run concurrently for each dispatched action.

 - **Behavior:** Each action dispatched triggers a new saga, meaning all instances run to completion.

 **takeLatest:**

 - **Definition:** Only allows the most recent instance of a saga to run, canceling any previous instances for the same action type.
    
 - **Behavior:** If a new action is dispatched while a saga is still running, the previous saga is canceled, and only the latest action is processed.


### Summary of Differences:
| Feature              | `takeEvery`                           | `takeLatest`                          |
|----------------------|---------------------------------------|---------------------------------------|
| **Behavior**         | Spawns a new saga for every action   | Cancels previous saga, keeps the latest |
| **Concurrency**      | Allows multiple sagas to run         | Only runs the latest saga             |
| **Use Case**         | When every action should be handled   | When only the latest action matters   |


**28. what is react context api?**

            The React Context API is a feature in React that allows you to manage and share state across components without having to pass props manually at every level of the component tree. It's mainly used to avoid "prop drilling", which occurs when you pass data from parent to deeply nested child components unnecessarily.


**29. What is the purpose of useReducer,***

      The useReducer hook is used in React for managing complex state logic. It’s helpful when:

   **State is complex:** If you have multiple related state variables or complex state updates, useReducer can organize this better than useState.

   **Multiple actions:** When you need to handle different actions (like incrementing, decrementing, or resetting a counter).            


**30. What are inline conditional expressions?**

            Inline conditional expressions in React allow you to render different parts of the UI based on certain conditions, all within the JSX syntax. These are useful for showing or hiding elements dynamically based on state or props.

**There are several ways to use inline conditional expressions:**

   **1. If Statements:**
            You can use regular JavaScript if statements, but these are typically used outside of the JSX return because they don't return a value directly inside JSX.

   **2. Ternary Operator (?:)**

            This is a shorthand way of writing an if-else statement inside JSX. It allows you to conditionally render one of two values based on whether the condition is true or false.

  **Example:**

                  jsx
                  Copy code
                  <h1>Hello!</h1>
                  {
                    messages.length > 0 ? (
                      <h2>You have {messages.length} unread messages.</h2>
                    ) : (
                      <h2>You don't have unread messages.</h2>
                    )
                  }
                  If messages.length > 0 is true, the first <h2> will be rendered.
                  If false, the second <h2> will be rendered.

   **3. Logical AND Operator (&&):**

            You can use the && (AND) operator to conditionally render something only when the condition is true. If the condition is false, it simply skips rendering that part of the UI.

   **Example:**
                  
                  jsx
                  Copy code
                  <h1>Hello!</h1>
                  {
                    messages.length > 0 && !isLogin && (
                      <h2>You have {messages.length} unread messages.</h2>
                    )
                  }
            In this example:

            If both messages.length > 0 and !isLogin are true, the message will be displayed.
            If any of them is false, nothing is rendered.

            
**31. Controlled Components in React**

**Controlled Components** are input elements where React state controls the input value. This ensures the input field and state are always in sync, making it easier to manage user inputs.

### Steps to Create a Controlled Component

i. **Initialize the State**: Use `useState` to create a state variable (e.g., `username`).

ii. **Set Input Value**: Tie the input's `value` to the state (`<input value={username} />`).

iii. **Handle Input Changes**: Create a function (like `handleChange`) to update the state when the user types.

4. **Attach Event Handler**: Connect this function to the input’s `onChange` event.

### Example Code

            import React, { useState } from "react";
            
            function UserProfile() {
              const [username, setUsername] = useState(""); // Step 1
            
              const handleChange = (e) => {
                setUsername(e.target.value); // Step 3
              };
            
              return (
                <form>
                  <label>
                    Name:
                    <input type="text" value={username} onChange={handleChange} /> {/* Steps 2 and 4 */}
                  </label>
                </form>
              );
            }

- **State** controls the input value.
- **Event handler** keeps the state updated with user input.
- Input is fully managed by React, ensuring consistent behavior.


**32. What are effects in redux saga?**

  **- call:**
             To invoke a function (e.g., API call) and wait for it to complete.

  **- put:**
             To dispatch an action to the Redux store.

  **- take:**
              To pause the saga until a specific action is dispatched.

  **- takeEvery:**
             To listen for every occurrence of a specific action and run a saga for each one.

  **- takeLatest:**
             To run a saga for the latest occurrence of an action and cancel any previous ones if they are still running.

  **- select:**
             To access the current state from the Redux store.

  **- fork:**
             To create a non-blocking task that runs concurrently with the rest of the saga.

  **- delay:**
             To pause the saga for a specified amount of time (non-blocking delay).

   
**33. What is useContext?**

            UseContext allows components to access shared values from a context provider without passing props manually. It simplifies sharing state across multiple components, avoiding prop drilling.


**34. state the core principle of redux ?** 
 
 This principle is based on three key concepts:

   **i. Single Source of Truth:** The entire application's state is stored in one central store, making it easy to manage and maintain. All parts of the app access and derive state from this single store, ensuring consistency.

   **ii. State is Read-Only:** The application state cannot be modified directly. To make any change, an action must be dispatched. Actions are plain JavaScript objects that describe the change, keeping the flow of data predictable and easy to debug.

   **iii. Changes are Made with Pure Functions:** Redux uses pure functions, called reducers, to manage how state changes in response to actions. Reducers take the current state and an action, then return a new state, ensuring that updates are consistent and free from side effects.            


**35. Is it true that Redux can only be used with React?**

            No, it is not true that Redux can only be used with React. Redux is being used as a data store for lots of UI layers. There are bindings available in Redux for React, Angular, Angular 2, Vue, etc.    


**36. Features of React**

 **i. Component-Based Architecture**:  
   React uses a modular approach, breaking the UI into reusable, self-contained components. This makes the code more organized and easier to maintain.

 **ii. Virtual DOM**:  
   React creates a lightweight, in-memory version of the DOM. When updates happen, only the necessary changes are applied to the actual DOM, making updates faster and more efficient.

 **iii. JSX (JavaScript XML)**:  
   JSX allows developers to write HTML-like code in JavaScript, making the code more readable. It combines HTML tags and JavaScript in the same file and is compiled by tools like Babel.

 **iv. One-Way Data Binding**:  
   React enforces a one-way data flow from parent to child components, making the application easier to understand and debug. This approach keeps components modular and predictable.

 **v. State Management**:  
   React provides `useState` and `useReducer` hooks for managing component state. For complex state needs, tools like Context API and Redux help manage global state.

 **vi. Single-Page Application (SPA) Development**:  
   React is ideal for SPAs, which update content dynamically without reloading the whole page, offering a smoother user experience.

   
