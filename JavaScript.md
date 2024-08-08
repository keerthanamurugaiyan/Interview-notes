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
        
**Ans**        JavaScript is a client-side scripting language and Java is object Oriented Programming language. Both of them are totally different from each other.
        •	JavaScript: It is a light-weighted programming language (“scripting language”) for developing interactive web pages. It can insert dynamic text into the HTML elements. JavaScript is also known as the browser’s language.
        •	Java: Java is one of the most popular programming languages. It is an object-oriented programming language and has a virtual machine platform that allows you to create compiled programs that run on nearly every platform. Java promised, “Write Once, Run Anywhere”.            


4. **What is the difference between null and undefined?**

**Ans**        null is an assignment value that represents no value or an empty value, while undefined is a     variable that has been declared but not assigned a value.


5. **Why do we use the word “debugger” in JavaScript?**

**Ans**            The word “debugger” is used in JavaScript to refer to a tool that can be used to step through JavaScript code line by line. This can be helpful for debugging JavaScript code, which is the process of finding and fixing errors in JavaScript code. To use the debugger, you need to open the JavaScript console in your browser. Then, you can use debugger commands to comb through your code line by line.

It's essential to know debugging techniques as well as the more general ideas behind code optimization and speed improvement. In addition to operating smoothly, efficient code significantly enhances the user experience.


6. **Spread Operator**
        
**Ans**        The spread operator (...) is used to unpack elements of an iterable (like an array) into a list of arguments or elements. It can be used to easily combine arrays or copy them.

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

**Ans**            Javascript operators are used to perform different type of mathematical and logical  computations.

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