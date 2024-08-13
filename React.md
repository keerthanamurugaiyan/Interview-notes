**1.  what is useState?**

**Ans:** 

      The useState hook is a function that allows you to add state to functional components in React. It returns an array with two elements: the current state value and a function to update that value.

**(i) How does useState handle state updates? Is it synchronous or asynchronous:-**
      
      State updates in React using useState are asynchronous. This means that the state may not update immediately after calling the state updater function. React batches state updates for performance optimization.

**(ii) What happens if you pass a function to setState instead of a value:-**

      Passing a function to the state updater function allows you to access the current state value and update it based on that. This is particularly useful when updating state based on the previous state value.

**(iii) How do you use the useState hook to manage an object or array state:-**

      To manage complex state like objects or arrays, you can use the state updater function to make immutable updates.