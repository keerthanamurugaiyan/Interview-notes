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


**31. What is the Virtual Dom?**
      
      The Virtual Dom is a lightweight copy of the actual Dom in memory. React uses its to  improve performance by updating only the changed parts of the actual Dom.


**32. What is a closure in javascript?**
      
            A closure is a feature where an inner function has access to the outer functions variables.


 **33. . What is the role of deferred scripts in JavaScript?**

            The processing of HTML code while the page loads are disabled by nature till the script hasn't halted. Your page will be affected if your network is a bit slow, or if the script is very hefty. When you use Deferred, the script waits for the HTML parser to finish before executing it. This reduces the time it takes for web pages to load, allowing them to appear more quickly. 


 **34. What is Destructuring in JavaScript?**

      oru array illa object la irukka multiple values-a separate variables-la store panna destructuring use pannuvom.

      In JavaScript, destructuring is a way to extract values from arrays or objects and assign them to variables in a simple and concise manner. Instead of accessing each value individually, destructuring allows you to unpack multiple values and store them in variables easily.

   **Example :-**

      // Array Destructuring
      const fruits = ['apple', 'banana', 'orange'];
      const [fruit1, fruit2, fruit3] = fruits;
      console.log(fruit1); // Output: apple
      console.log(fruit2); // Output: banana
      console.log(fruit3); // Output: orange

      // Object Destructuring
      const person = { name: 'John', age: 30, city: 'Chennai' };
      const { name, age, city } = person;
      console.log(name); // Output: John
      console.log(age); // Output: 30
      console.log(city); // Output: Chennai  


**35. what is the use of window object?**
      
      window object is created auomatically by the browser.
      that represents a window of a browser.
      it is not an object of javascript.
      it is a browser object.
      the window object is used to display the popup diolog box.
      lets see with description.
      
   **METHODS:**
      **alert():**
            display the alert box containing with ok button.
      **confirm():**
            confirm dialog box box containing the message with ok and cancel button.
      **prompt():**
            display a dialog box to get input from the user.
      **open():**
            opens the new window.
      **close():**
            closes the current window.
      **setTimeout():**
            perform the action after specified time.


**36. What is a promise chaining?**

            Promise chaining is a way to execute multiple asynchronous operations in sequence by chaining promises together.  


**37. Explain passed by value and passed by reference.**

        In JavaScript, primitive data types are passed by value and non-primitive data types are passed by reference.


**38. What is 'this' keyword in javascript ?**

      The 'this' keywprd in Javascript refer to the currently calling object. It is commonly used in constructors to assign values to object properties.
      Ex : const person = {
      name: "Vino",
      greet() {
            console.log('Hello, ' + this.name); // 'this' refers to the 'person' object
      }
      };
      person.greet(); 

   **Output :**
       Hello Vino        
                          

**39. What do you mean by Self Invoking Functions?**
      
      •  Without being requested, a self-invoking expression is automatically invoked (initiated). If a function expression is followed by (), it will execute automatically. A function declaration cannot be invoked by itself.

      •  Normally, we declare a function and call it, however, anonymous functions may be used to run a function automatically when it is described and will not be called again. And there is no name for these kinds of functions


**40. what is self invoked function?**
           
            A self-invoking function is a nameless (anonymous) function that is invoked immediately after its definition.

            An anonymous function is enclosed inside a set of parentheses followed by another set of parentheses (), which does the execution.

            (function(){
            console.log("This function is called immediately");
            })();
            Self-invoking functions are useful for initialization tasks. For example, if we have a web page in which we want to attach event listeners to DOM elements and other initialization work, self-invoking functions would be the best tool for the job!

            The primary benefit of self-invoking functions is that they execute only once and won’t fill the global namespace with all sorts of crud that lasts for the lifetime of the page.

            It doesn’t seem like adding a few things to the global namespace would be a problm until you start getting into thousands of lines of javascript and having collisions between functions or variables.

   **How they actually work ?**
            
            Since the function is defined anonymously, there are neither global nor even local variables except, of course, the variables declared inside the function’s body. We do not keep reference to the function, not even to its return value. After the function has been initialized, it is being immediately invoked and it’s executed only once as after the execution we’ll lose the reference to the function.      


**41. Error Handling Techniques?**
            
   **try...catch Statement:**

            This is the most common way to handle errors in JavaScript. The code that might throw an error is placed inside the try block. If an error occurs, the control is passed to the catch block, where you can handle the error.

   **eg:**   try {
            let result = riskyFunction();
            } catch (error) {
            console.error("An error occurred:", error.message);
            }

            finally Block:

            You can use a finally block after try...catch. Code in the finally block will execute regardless of whether an error was caught or not, making it ideal for cleanup operations.

   **eg:**  try {
            let result = riskyFunction();
            } catch (error) {
            console.error("An error occurred:", error.message);
            } finally {
            console.log("This will run no matter what.");
            }

            wait      


**42. //indexOf//**
      
      It is used to find the index of an element
      let fruits=['Apple','Orange','Guva']
      let fruit=fruits.indexOf('Guva')
      console.log(fruit);

   **//Splice//**
     
      It is used to add and remove element from an array
      let fruits = ['Apple', 'Orange', 'Guava'];
      let fruit = fruits.splice(1, 1, 'Greenapple');

      console.log(fruit); 
      console.log(fruits);


**43. (i),Sorts**

   **Definition:** Sorts the elements of an array in place and returns the array.
   **Example:**
      let numbers = [3, 1, 4, 1, 5];
      numbers.sort();
      console.log(numbers):
      **// Output:** [1, 1, 3, 4, 5]

   **(ii).Join**

   **Definition:** Joins all elements of an array into a string.
   **Example:**
      let words = ['Hello', 'World'];
      let sentence = words.join(' '); // Joins elements with a space
      console.log(sentence); 
      **// Output:** 'Hello World' 


**44. What is the difference between querySelector() and getElementById()?**

   **getElementById() :**
        Only selects elements by their id attribute. You must provide the exact id of the element.
        Returns a single element object that matches the given id. If no element with the specified id exists, it returns null.

   **querySelector() :**
        More versatile; it allows you to select elements using any valid CSS selector **(e.g., #id, .class, tag, attribute, etc.)**
        Returns the first element that matches the given CSS selector. If no element matches the selector, it returns null. 


**45. Split method is used to convert string to an array.**
          
          let js="javascript";
          const java=js.split("")
          console.log(java)

   **Concat method is used to join two array elements.**
          
          let user=[1,2,3,4]
          let looser=[5,7,8,9]
          let total=user.concat(looser)
          console.log(total)
                   

**46. why we used eventpreventdeafault ?**

   **Form Submission:** 
      
      In HTML, when a form is submitted, the default action is to reload the page or navigate to a new 
      URL (as specified by the action attribute). By using event.preventDefault(), you can prevent this default action, 
      allowing you to handle the form submission with JavaScript instead

**Example:**
      
      document.querySelector('form').addEventListener('submit', function(event) {
      event.preventDefault(); // Prevents the form from submitting
      // Handle form submission with JavaScript
      });


**47. (i)Array Length**
            
            To get the length of an array, you can use the .length property.
            const fruits = ["apple", "banana", "cherry", "date"];
            console.log(fruits.length); 

   **(ii)Array Slice**
            
            The slice() method returns a shallow copy of a portion of an array into a new array. You can specify the start and end indices.
            const fruits = ["apple", "banana", "cherry", "date", "elderberry"];
            const slicedFruits = fruits.slice(1, 3);
            console.log(slicedFruits);      
     

 **48. What is type coercion?**

            Type coercion is the automatic conversion of values from one type to another by JavaScript. For example, when adding a number to a string, JavaScript converts the number to a string and performs concatenation. 


**49. What is Array in Javascript?**

            An array in JavaScript is a special type of object used to store multiple values in a single variable. Arrays can hold different data types such as numbers, strings, or even other arrays. They are indexed, meaning each element is assigned a numeric index starting from 0 


**50. In javascript, how do you turn object{} into an array[]?**

      In JavaScript, you can turn an object into an array in several ways, depending on what information
      you want to extract from the object. Here are some common methods:

   **(i). Convert Object Values to Array: If you want to get an array of the object's values:**

      const obj = { a: 1, b: 2, c: 3 };
      const valuesArray = Object.values(obj);
      console.log(valuesArray); **// Output: [1, 2, 3]**

   **(ii). Convert Object Keys to Array: If you want to get an array of the object's keys:**

      const obj = { a: 1, b: 2, c: 3 };
      const keysArray = Object.keys(obj);
      console.log(keysArray); **// Output: ['a', 'b', 'c']** 

   **(iii). Convert Object Entries to Array: If you want to get an array of the object's key-value pairs:**

     const obj = { a: 1, b: 2, c: 3 };
     const entriesArray = Object.entries(obj);
     console.log(entriesArray); **// Output: [['a', 1], ['b', 2], ['c', 3]]**                      


**51. What is a pure function?**

            A pure function is a function that meets two important criteria:

            Deterministic: It always returns the same result given the same inputs. This means it behaves consistently regardless of external factors or system state.

            No Side Effects: A pure function does not modify any external state or interact with the outside world. It doesn't change global variables, update data, perform I/O operations (like logging or making HTTP requests), or modify its inputs.


**52. what is map function in javascript?**

            In JavaScript, the map() method is used to create a new array by applying a function to each element of an existing array. It iterates over the array, applies a callback function to each element, and returns a new array with the transformed values.
            const numbers = [1, 2, 3, 4];
            const doubled = numbers.map(function(number) {
            return number * 2;
            });

            console.log(doubled); 

            console.log(numbers)
            ;  


**53. what is DOM manipulation?**

        DOM manipulation refers to the process of changing, adding, or removing elements and content from a webpage dynamically using            JavaScript. The DOM (Document Object Model) is a programming interface that represents the structure of a webpage as a tree of           objects (nodes), such as elements, attributes, and text.


**54. Why do we need JSON.Parse and JSON.Stringify?**
            
           •  When working with web application data is often exchanged between the client and the server.
           
           •  The data is typically sent in JSON format because it is a lightweight, text based format that is easy to read and write for              both humans and machines

   **JSON Parse:**
            JSON.parse is a method in javascript that takes JSON String and converts it into a JavaScript object.

   **JSON Stringify:**
            JSON.stringify is  a method in Javascript that takes a javascript and converts it into a JSON String.


**55. Array.length and Array.toString()**

**Array.length**
   
   **Description:** 
           The .length property of an array returns the number of elements in the array.
   
   **Example:**
        const arr = [1, 2, 3, 4, 5];
        console.log(arr.length);  

**Array.toString()**

   **Description:** 
           The .toString() method converts the elements of an array into a comma-separated string.
  
   **Example:**
        const arr = [1, 2, 3, 4, 5];
        console.log(arr.toString());             


**56. What are Cookies?**
       
       • Cookies are data, stored in small text files, on your computer.
        
       • When a web server has sent a web page to a browser, the connection is shut down, and the server forgets everything about the user.
        
       • Cookies were invented to solve the problem "how to remember information about the user":
        
       • When a user visits a web page, his/her name can be stored in a cookie.
       • Next time the user visits the page, the cookie "remembers" his/her name


**57.  What are all the looping structures in JavaScript ?**

           In JavaScript, there are several looping structures, each designed for different use cases.
           Let’s explain the most common ones:

   **i=> While Loop:**
          
           A while loop continues to execute as long as a specified condition evaluates to true.
           The condition is checked before the loop's code runs, so if the condition is false from the start,
           the loop will not execute.
   
   **Example:**
        
        let i = 0;
        while (i < 5) {
            console.log(i);
            i++;
        }

   **ii=> For Loop:**
          
           A for loop is commonly used when the number of iterations is known. 
           It is a compact version of a loop that combines initialization, condition checking, 
           and incrementing (or decrementing) in a single line.
  
   **Example:**
        
        for (let i = 0; i < 5; i++) {
            console.log(i);
        }

   **iii=> Do-While Loop:**
            
   **A do-while loop is similar to a while loop, but with one key difference:**  
                   
            it checks the condition after executing the loop body. This guarantees that the loop
            will run at least once, regardless of the condition.
   
   **Example:**
            
            let i = 0;
            do {
                console.log(i);
                i++;
            } while (i < 5);

   **iv=> For-In Loop:**
           
           The for-in loop iterates over the properties of an object (not the elements of an array). 
           It's useful for looping through object properties.
   
   **Example:**
   
        const obj = { name: 'John', age: 30 };
        for (let key in obj) {
            console.log(key, obj[key]);
        }

   **v=> For-Of Loop:**
           
           The for-of loop iterates over iterable objects like arrays, strings, maps, etc.
           It gives the values of the iterable, unlike for-in, which gives the keys.        
   
   **Example:**
   
        const array = [1, 2, 3];
        for (let value of array) {
            console.log(value);
        }


**58. what is filter in javascript?**

            The filter() method in JavaScript creates a new array with elements that pass the test provided by a function. It doesn’t modify the original array, but instead returns a new array that contains only the elements for which the provided function returns true.
            const numbers = [1, 2, 3, 4, 5];
            
            // Filter out numbers greater than 3
            const filteredNumbers = numbers.filter(num => num <= 3);
            
            console.log(filteredNumbers);  // Output: [4, 5]
            
            
            const employees = [
              { id: 1, name: 'Alice', age: 25 },
              { id: 2, name: 'Bob', age: 35 },
              { id: 3, name: 'Charlie', age: 28 }
            ];
            
            // Filter employees who are 30 or younger
            const youngEmployees = employees.filter(employee => employee.age <= 28);
            
            console.log(youngEmployees);
            

**59. What is promise?**

            A Promise in JavaScript is an object that represents the eventual completion (or failure) of an asynchronous operation and its resulting value. It allows you to write asynchronous code in a more readable way, avoiding callback hell (nested callbacks). Promises can be in one of three states:

   **Pending:** The initial state—neither fulfilled nor rejected.
   
   **Fulfilled:** The operation completed successfully, and the promise has a resulting value.
   
   **Rejected:** The operation failed, and the promise has a reason for the failure.


**60. what is reduceRIght in javascript?**

            In JavaScript, the reduceRight() method is similar to reduce(), but it processes the array from right to left rather than left to right. It applies a function (the "reducer") against an accumulator and each element in the array, reducing it to a single value.   

   
