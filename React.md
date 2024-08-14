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
      
       **(ii)** **•** A framewok is a comprehensive provides a foundation and structure for developing software applications. It dedicates a specify way of organizing and developing an application. 
       **•** In a framework, the framework itself is in control of the applications flow. It calls the developers code when necessary. This is often referred as "Inversion of control"**..Eg.Angular.**


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
