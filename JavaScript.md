1. **What is javascript and what are the different datatypes?** 

**Ans:**    Js is a programming language .It isone of the most widely used web development languages.It was     design to build dynamic and  interactive web page.  It was  created by brendan eich in 1995. 

    Primitive Datatypes is store only a single values they are String,number,boolean,null,undefined,symbol.      Non primitive values can store multiple  and complex values they are object and array


2.  **what is generator function?**
     
**Ans:**       "A generator function in JavaScript is a special type of function that allows you to pause and   resume its execution. It's defined using the function* syntax and uses the yield keyword to produce values.
            The key features of generator functions are:

            They return an iterator object when called.
            They can pause execution using yield and resume from where they left off.
            They maintain their internal state between calls.
            They're useful for working with large data sets or infinite sequences efficiently.


3. **What are the differences between Java and JavaScript?** 
        
**Ans:**        JavaScript is a client-side scripting language and Java is object Oriented Programming language. Both of them are totally different from each other.
        •	JavaScript: It is a light-weighted programming language (“scripting language”) for developing interactive web pages. It can insert dynamic text into the HTML elements. JavaScript is also known as the browser’s language.
        •	Java: Java is one of the most popular programming languages. It is an object-oriented programming language and has a virtual machine platform that allows you to create compiled programs that run on nearly every platform. Java promised, “Write Once, Run Anywhere”.            


4. **What is the difference between null and undefined?**

**Ans:**        null is an assignment value that represents no value or an empty value, while undefined is a     variable that has been declared but not assigned a value.


5. **Why do we use the word “debugger” in JavaScript?**

**Ans:**            The word “debugger” is used in JavaScript to refer to a tool that can be used to step through JavaScript code line by line. This can be helpful for debugging JavaScript code, which is the process of finding and fixing errors in JavaScript code. To use the debugger, you need to open the JavaScript console in your browser. Then, you can use debugger commands to comb through your code line by line.

It's essential to know debugging techniques as well as the more general ideas behind code optimization and speed improvement. In addition to operating smoothly, efficient code significantly enhances the user experience.


6. **Spread Operator**
        
**Ans:**        The spread operator (...) is used to unpack elements of an iterable (like an array) into a list of arguments or elements. It can be used to easily combine arrays or copy them.

**Eample:**
          const array1 = [1, 2, 3];
          const array2 = [4, 5, 6];

        // Combining arrays using the spread operator
        const combinedArray = [...array1, ...array2];

        console.log(combinedArray); // Output: [1, 2, 3, 4, 5, 6]

        concat Method
        The concat method is a built-in array method in JavaScript that is used to merge two or more arrays into a new array without changing the original arrays.

**Example**:
             const array1 = [1, 2, 3,];
             const array2 = [4, 5, 6];

        // Combining arrays using the concat method
        const combinedArray = array1.concat(array2);

        console.log(combinedArray); // Output: [1, 2, 3, 4, 5, 6]


7.   **Define Javascript operator and different types of operator?**

**Ans:**            Javascript operators are used to perform different type of mathematical and logical  computations.

            Types of Operator

            Arithmetic Operator
            Assignment Operator

            Comparison Operator
            String Operator
            Logical Operator
            Bitwise Operator
            Ternary Operator
            Type Operator

            +	Addition
            -	Subtraction
            *	Multiplication
            **	Exponentiation (ES2016)
            /	Division
            %	Modulus (Division Remainder)
            ++	Increment
            --	Decrement
            Arithmetic

            =	x = y	x = y
            +=	x += y	x = x + y
            -=	x -= y	x = x - y
            =	x = y	x = x * y
            /=	x /= y	x = x / y
            %=	x %= y	x = x % y
            *=	x *= y	x = x ** y
            Assignment

            ==	equal to
            ===	equal value and equal type
            !=	not equal
            !==	not equal value or not equal type
            >	greater than
            <	less than
            >=	greater than or equal to
            <=	less than or equal to
            ?	ternary operator
            Comparison Operator

            &&	logical and
            ||	logical or
            !	logical not
            Logical

            typeof	Returns the type of a variable
            instanceof	Returns true if an object is an instance of an object type
            Type operator

            &	AND
            |	OR	
            ~	NOT	
            ^	XOR	
            <<	left shift	
            >>	right shift	
            >>>	unsigned right shift	
            Bitwise Operator


8.   **what is javascript hoisting?**

**Ans:**        In Javascript, hoisting is the default behavior of moving all the declaration at the top of the Scope before code execution.      


9. **what is the difference beyween var, const, let**

     **Ans**      In JavaScript, var, let, and const are used to declare variables, but they have key differences:

**I. Scope:**

   **• var:**   Function-scoped: Variables declared with **var** are available throughout the function in which they are declared. If declared outside a function, they are globally scoped.
var does not respect block scope, meaning it's not confined within {} (e.g., in loops or conditionals).

   **• let:**  Block-scoped: Variables declared with **let** are confined to the block in which they are declared (i.e., inside {}).

   **• const:**  Block-scoped: Similar to **let, const** is also block-scoped.

**II. Reassignment:**

   **• var:**  Can be reassigned and redeclared within its scope.

   **• let:**  Can be reassigned but cannot be redeclared within the same scope.

   **• const:**  Cannot be reassigned or redeclared. However, for objects and arrays, their contents can be modified (but not the reference itself).

**III. Hoisting:**

   **• var:**  Variables declared with **var** are hoisted to the top of their scope and initialized as **undefined**.
 
   **let** and **const:**  These are also hoisted but are not initialized. Accessing them before declaration will result in a **ReferenceError**.


10.   **Explain the differences between these methods.**

**Ans:**

**I. Find Method:**
      Find method get the first element that satisfies a condition. If no element satisfies the condition, it returns undefined.

**Example:**
      const numbers = [1, 2, 3, 4, 5];
      const found = numbers.find(num => num > 3);
      console.log(found); // Output: 4

**II. Filter Method:**
      The filter method get an array of elements that satisfies a condition. If no elements satisfy the condition, it returns an empty array.

**Example:**
      const numbers = [1, 2, 3, 4, 5];
      const filtered = numbers.filter(num => num > 3);
      console.log(filtered); // Output: [4, 5]

**III Slice Method:**
      Slice method get a subset of the array from start index to end index(end index not included)

**Example:**
      const numbers = [1, 2, 3, 4, 5];
      const sliced = numbers.slice(1, 4);
      console.log(sliced); // Output: [2,3,4]


11.  **Diffrence between Local Storage and Session Storage:**    

**Ans:**

      LocalStorage and SessionStorage are two types of web storage in your browser that help store data locally on your device. 

**I.Local Storage:**

      LocalStorage keeps data even after you close the browser, so it's useful for saving things like user preferences.

**II.Session Storage:**

      SessionStorage, on the other hand, only keeps data as long as the browser tab is open. Once you close the tab, the data is gone. Both are easy to use for storing small pieces of data like tokens or settings, but LocalStorage is more permanent, while SessionStorage is temporary.      


12.  **Palindrome in JavaScript.**

**Ans:**

      A palindrome is a value that reads the same from backward or forward.
      To perform this check we will use the following approaches:

**Approach 1:**

  Array  split(), reverse() and  join() methods.

**Approach 2:**

 **ApproachII: Using for loop**

   - Initialize a variable and store the reverse of the value in it using for loop
   - Compare the original value with the reversed value
   - If both values are equal return true else return false

**Approach III: Using for loop (efficient approach)**

   - Iterate over the string from forward and backward direction
   - Check if the character match
   - Return false for the first character that does not match
   - Return true if all the comparisons are performed and the characters match


13.   **What are the ways of adding JavaScript code in an HTML file?**

      **There are primarily two ways of embedding JavaScript code:**

      - We can write JavaScript code within the script tag in the same HTML file; this is suitable when we need just a few lines of scripting within a web page.
      - We can import a JavaScript source file into an HTML document; this adds all scripting capabilities to a web page without cluttering the code.


14.    **What is Destructuring?**

      We may have an array or object that we are working with, but we only need some of the items contained in these.
      Destructuring makes it easy to extract only what is needed.

**I. Array Destructuring:**
      const vehicles = ['mustang', 'f-150', 'expedition'];
      const [car, truck, suv] = vehicles;

**II. Object Destructuring:**

           const vehicleOne = {
           brand: 'Ford',
           model: 'Mustang',
           type: 'car',
           year: 2021,
           color: 'red',
           registration: {
           city: 'Houston',
           state: 'Texas',
           country: 'USA'
   }
   }
      myVehicle(vehicleOne)
      function myVehicle({ model, registration: { state } }) {
      const message = 'My ' + model + ' is registered in ' + state + '.';
      document.getElementById("demo").innerHTML = message;
      }  


15.  **Different types of error in javascript?**
        
        Eight type of error in javascript:

 **i. Eval error:**
      EvalError is one of the built-in error types in JavaScript,
      along with other error types like SyntaxError, ReferenceError and etc.
 
 **ii. Range Error:**
      A RangeError in JavaScript occurs when a value is not within the set or
      expected range of values. 
     
 **iii. Reference Error:**
      A ReferenceError in JavaScript occurs when you try to access a variable 
      or function that hasn't been declared or is out of scope
     
 **iv. syntax Error:**
      A syntax error in JavaScript occurs when the code does not follow the rules 
      or structure of the JavaScript language.
     
 **v. type Error:**
      A TypeError in JavaScript is an error that occurs when an operation 
      or function is performed on a value of an inappropriate type.
     
 **vi. URI error:**
      In JavaScript, a URI (Uniform Resource Identifier) error typically occurs 
      when there's a problem with encoding or decoding a URI component.
 
**vii. Aggregate Error:**
      In JavaScript, AggregateError is a special error object 
      that represents multiple errors that occurred during the execution of a Promise-related operation,
      such as Promise.all(), Promise.any(), or Promise.allSettled().It is used to 
      encapsulate multiple error instances in a single error object, making it easier 
      to handle multiple errors at once.
 
**viii. Internal Error:**
      In JavaScript, an "Internal Error" generally refers to a problem that occurs 
      within the JavaScript engine or runtime environment, which isn't directly related
      to your own code but rather to the environment executing your code. 
      These errors are often less common and can be caused by a variety of factors


**16.   unshift method:**
      
      prepend the value to the beggining if the array.

**eg:** 
      var a =[2,3,4]
      a.unshift(1);
      console.log(a);
      
**output:** [1,2,3,4]


**17.  what are the ways to assign properties to an object in js:**

  **standard way:**
      var a ={};
      a.firstName='john';
      
  **array syntax:**
      a['lastname']='due';
      console.log(a);
      
  **output:**
      {firstName:'john',lastName:'due'}
      
      console.log(a); 


**18.  What is the use of async and await in JavaScript?**

**Ans:** 
      
Async and await are used to handle asynchronous operations more easily than Promise chaining.
            
   **•  async:** Declares an asynchronous function that returns a Promise.
   **•  await:** Pauses the execution of the async function until the Promise is resolved or rejected.
            
   **Example:** 
            
            function simulatedAPI() {
            return new Promise((resolve, reject) => {
                  let random = Math.floor(Math.random() * (11 - 1) + 1);
                  setTimeout(() => {
                        if (random <= 5) {
                        resolve("Operation success: " + random);
                        } else {
                        reject("Operation fails");
                        }
                  }, 1000);
            });
            }

            async function simulateAPI() {
            try {
                  let result = await simulatedAPI();
                  console.log("success:", result);
            } catch (error) {
                  console.error('failed:', error);
            }
            }

            simulateAPI();


19.  **Array methods:**

  **(i) push() :**
     The **push()** method adds one or more elements to the end of an array and returns the new length of the array.
    
      **eg:**
            let fruits = ['apple', 'banana'];
            fruits.push('orange');
            console.log(fruits); // ['apple', 'banana', 'orange']

  **(ii) pop() :**
      The **pop()** method removes the last element from an array and returns that element.

      **eg:** 
            let fruits = ['apple', 'banana', 'orange'];
            let lastFruit = fruits.pop();
            console.log(lastFruit); // 'orange'
            console.log(fruits);    // ['apple', 'banana']

  **(iii) shift() :**
     The **shift()** method removes the first element from an array and returns that element.

      **eg:**
            let fruits = ['apple', 'banana', 'orange'];
            let firstFruit = fruits.shift();
            console.log(firstFruit); // 'apple'
            console.log(fruits);     // ['banana', 'orange']


  **(iv) unshift() :**
      The **unshift()** method adds one or more elements to the beginning of an array and returns the new length of the array.
   
      **eg:**   
            let fruits = ['banana', 'orange'];
            fruits.unshift('apple');
            console.log(fruits); // ['apple', 'banana', 'orange']          


**21. What is delete in javascript?**

      The delete operator removes a property from an object. If the property's value is an object and there are no more references to the object, the object held by that property is eventually released automatically


**22. 1. What are arrow functions?**
      
   An arrow function is a shorthand way to write functions in JavaScript. It uses the **` =>`** syntax and has a more concise form than regular functions. Arrow functions are also unique because they do not bind their own **`this`** context; instead, they inherit **`this`** from their surrounding scope.

   **eg:**
      
   **// Regular function**
      function add(a, b) {
      return a + b;
      }

  **// Arrow function**
      const add = (a, b) => a + b;



**23. 1.what is the use of constructor function in javascript?**
      
      contructor function is used to create a objects in javascript.

**when we use this function?**

      if we want to create multiple objects having similer properties and methods
      thatb time it was used.

   **eg:**
      functionPerson(name,gender){
      this.name = name;
      this.age = age;
      this.gender = gender;
      }
      var person1 = new person("vivek",76,"male");
      console.log(person1);

      var person2 = new person("john",34,"femake");
      console.log(person2);


      example is common for both qn  


**24. What are the types of errors in javascript?**

      There are two types of errors in javascript.

   **Syntax error :**    Syntax errors are mistakes or spelling problems in the code that cause the program to not execute at all or to stop running halfway through. Error messages are usually supplied as well.

   **Logical error :**    Reasoning mistakes occur when the syntax is proper but the logic or program is incorrect. The application executes without problems in this case. However, the output findings are inaccurate. These are sometimes more difficult to correct than syntax issues since these applications do not display error signals for logic faults.  


**24. 2. Difference between “ == “ and “ === “ operators.**

   Both are comparison operators. The difference between both the operators is that **“==”** is used to compare values whereas, **“ === “** is used to compare both values and types.


**25. what are the types of event handler click function in javascript?**

   **1, onclick:** Triggered when an element is clicked.
   **2, ondblclick:** Triggered when an element is double-clicked.
   **3, onmouseover:** Triggered when the mouse pointer moves over an element.
   **4, onmouseout:** Triggered when the mouse pointer moves out of an element.
   **5, onmousemove:** Triggered when the mouse pointer moves within an element.
   **6, onmousedown:** Triggered when the mouse button is pressed down.
   **7, onmouseup:** Triggered when the mouse button is released.
   **8, onkeydown:** Triggered when a key is pressed down.
   **9, onkeyup:** Triggered when a key is released.
   **10, onkeypress:** Triggered when a key is pressed down and held.
   **11, onsubmit:** Triggered when a form is submitted.
   **12, onreset:** Triggered when a form is reset.
   **13, onfocus:** Triggered when an element gains focus.
   **14, onblur:** Triggered when an element loses focus.
   **15, onchange:** Triggered when the value of an input element changes.
   **16, oninput:** Triggered when the user inputs data in an input field.
   **17, onload:** Triggered when the document or an image has finished loading.
   **18, onerror:** Triggered when an error occurs during loading.

**most using to :**
      
   **•**onclick
   **•**onchange
   **•**onsubmit
   **•**onblur      


**26.what is higher-order function.**
   
   **a,**   Takes one or more functions as arguments: This means you can pass a function to another function as an input.
   **b,**   Returns a function as its result: The function can generate and return another function.


**27. What is NaN property in JavaScript?**

      NaN property represents the “Not-a-Number” value. It indicates a value that is not a legal number.

      typeof of NaN will return a Number.

      To check if a value is NaN, we use the isNaN() function,

      Note- isNaN() function converts the given value to a Number type, and then equates to NaN.
      isNaN("Hello")  // Returns true
      isNaN(345)   // Returns false
      isNaN('1')  // Returns false, since '1' is converted to Number type which results in 0 ( a number) 
      isNaN(true) // Returns false, since true converted to Number type results in 1 ( a number)
      isNaN(false) // Returns false
      isNaN(undefined) // Returns true   


**28. What is the setTimeout and setInterval?**
      
      setTimeout executes a function after a specified time delay. setInterval repeatedly executes a function at regular intervals.

   **setTimeout:-**
      
      setTimeout oru function a oru specific time delay apram execute pannum. Example, neenga setTimeout la 2000 milliseconds (2 seconds) time set pannina, adhaanaal 2 seconds kkeppuram oru function run aagum.

      setTimeout(function() {
      console.log('This message appears after 2 seconds');
      }, 2000);  // 2000 milliseconds = 2 seconds

   **setInterval:**

      setInterval oru function-a regular intervals la execute pannum. Example, neenga setInterval la 1000 milliseconds (1 second) time set pannina, adhu oru function a every 1 second ku continuous a execute pannum. Ithu stop panna clearInterval use pannalam.

      let intervalId = setInterval(function() {
      console.log('This message appears every 1 second');
      }, 1000);  // 1000 milliseconds = 1 second

      // To stop the interval after 5 seconds
      setTimeout(function() {
      clearInterval(intervalId);
      console.log('Interval stopped');
      }, 5000);  // 5000 milliseconds = 5 seconds


**29. what is Optional Chaining?**
      
      Optional chaining is a feature in JavaScript that allows you to safely access deeply nested properties of an object without having to manually check each level for null or undefined. It uses the ?. operator and helps prevent runtime errors that would occur if you tried to access a property of an undefined or null object."


**30. what is  nullish coalescing operator?**

      The nullish coalescing operator (??) in JavaScript is used to provide a default value when the left-hand side of the operation is null or undefined. It allows for more precise control than the logical OR (||) operator, which returns the right-hand side if the left-hand side is any 'falsy' value (like 0, '', false, etc.)."      
