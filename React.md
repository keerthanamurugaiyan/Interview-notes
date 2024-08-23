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


**5.  What is the use of Redux in React?**

      Redux helps manage the state of your entire React application in a centralized way. Instead of each component managing its own state, Redux allows you to keep the application’s state in one place (the store). This makes it easier to handle complex applications, share data between components, and maintain the state across different parts of your app.

   
**What is difference between ReactJS and Redux:**      

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
