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


