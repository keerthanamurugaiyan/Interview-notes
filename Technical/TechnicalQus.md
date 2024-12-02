**1.   In Javascript write a function that takes a string. Split the string by dot(.) and returns the second last string from that split. If there are no dots in the original string return an empty string. For example the parameter "ggg.ttt.com" the function returns "ttt"?**

varum

function elements(str){
    let product=str.split(".")
    if(product.length <2){
        return ""
    }
    return product[product.length -2]
}
console.log(elements("aaa.bbbb.hdhsfh.sdfhdsgh.sdhghgsdh"))
console.log(elements("aagfggga"))
console.log(elements("aaa.ccc.hhh.fgfftt.hhghgg"))


**2. Given the following JavaScript code, which calculates the minimum number of coins needed to make a specific total, what will the output be when the total is set to 108?**

    function findCombination(total) {
    let coins = [20, 10, 5, 3, 1];
    let result = {};

    for (let i = 0; i < coins.length; i++) {
        let coinValue = coins[i];
        let coinCount = Math.floor(total / coinValue);
        if (coinCount > 0) {
            result[coinValue + "rs"] = coinCount;
            total -= coinValue * coinCount;
        }
    }

    return result;
}

let total = 108;
let combination = findCombination(total);

for (let [coin, count] of Object.entries(combination)) {
    console.log(`${count} - ${coin}`);
}


**3. Program to find longest word in a given sentence ?**

        function findLongestWord(sentence) {
            const words = sentence.split(' ');
            let longestWord = '';
            for (let word of words) {
                if (word.length > longestWord.length) {
                    longestWord = word;
                }
            }
            return longestWord;
        }
        const sentence = "I Want to goooooooooo ghghghgffsdsdf";
        const longestWord = findLongestWord(sentence);
        console.log( longestWord);


**4. How to check whether a string is palindrome or not ?**

        function isPalindrome(str) {
        const normalizedStr = str.toUpperCase();
        const reversedStr = normalizedStr.split('').reverse().join('');
        return normalizedStr === reversedStr;
        }
        const inputString = "WoW";
        const result = isPalindrome(inputString);
        console.log(`${result ? "yes" : "no"}`);

        
**5. Write a program to remove duplicates from an array?** 

    function removeDuplicates(arr) {
    return [...new Set(arr)];
    }
    const array = [1, 2, 2, 3, 4, 4, 5, 6, 6];
    const uniqueArray = removeDuplicates(array);
    console.log(uniqueArray); 

**6. Write a function for mobile number validation in Javascript Regular expression?**
       
        function validNumber(val){
        const validateNumber = /^\d{10}$/;
        return validateNumber.test(val)
        };
        console.log(validNumber(1234567890))  


**7. Write a JavaScript program to find the maximum number in an array.**

        function findMaxNumber(arr) {
        if (arr.length === 0) {
            return "Array is empty";
        }
        const maxNumber = Math.max(...arr);

        return maxNumber;
        }
        const numbers = [];
        const max = findMaxNumber(numbers)
        ;
        console.log("The maximum number is:", max);


**8. Program to find Reverse of a string without using built-in method ?**

        function reverse(str){
            let user='';
            for(let i=str.length-1;i>=0;i--){
                user+=str[i];
            }
            return user;
        }
        let input='Hello World'
        let user=reverse(input)
        console.log(user)


**9. Find subset an array**
        
        function findSubsetSum(arr, targetSum) {
        let result = [];
        let tempSum = 0;
    
        // Sort the array in descending order to prioritize larger numbers
        arr.sort((a, b) => b - a);
    
        for (let i = 0; i < arr.length; i++) {
            if (tempSum + arr[i] <= targetSum) {
                tempSum += arr[i];
                result.push(arr[i]);
    
                // If we reach the target sum, break the loop
                if (tempSum === targetSum) {
                    break;
                }
            }
        }
    
        return result;
    }
    
    const input = [1, 6, 9, 10, 70, 90, 210, 410];
    const targetSum = 80;
    const subset = findSubsetSum(input, targetSum);
    console.log('Subset:', subset);
    console.log('Sum:', subset.reduce((acc, val) => acc + val, 0));

        
**10. Rotate an array**

   **function rotateRightByOne:**     
     
         function rotateRightByOne(arr) {
        // Remove the last element and insert it at the beginning of the array
        let lastElement = arr.pop();  // Removes the last element
        arr.unshift(lastElement);  // Inserts the last element at the beginning
        return arr;
    }

   **Example usage:**
       
        const arr = [1, 2, 3, 4, 5];
        console.log(rotateRightByOne(arr));  // Output: [5, 1, 2, 3, 4]

   **function rotateLeftByOne:**
   
           function rotateLeftByOne(arr) {
            // Remove the first element and append it to the end of the array
            let firstElement = arr.shift();  // Removes the first element
            arr.push(firstElement);  // Appends the first element to the end
            return arr;
        }

   **Example usage:**
            
            const arr = [1, 2, 3, 4, 5];
            console.log(rotateLeftByOne(arr));  // Output: [2, 3, 4, 5, 1]


**11. Explain the steps to create a react application and print Hello World?**

            To install React, first, make sure Node is installed on your computer. After installing Node. Open the terminal and type the following command.

        npx create-react-app <<Application_Name>>
        
        Navigate to the folder.
        
        cd <<Application_Name>>
        
        This is the first code of ReactJS Hello World!
        
        import React from "react";
        import "./App.css";
        function App() {
          return <div className="App">Hello World !</div>;
        }
        export default App;
        
        Type the following command to run the application
        npm start            


**12. Write a function to flattern a nested array**
       
        let  nums=[1,[2,3],[9,[8,0]]]
        function user(nums){
            return nums.flat()
        }
        console.log(user(nums))


**13. Replace and ReplaceAll in javaScript**

   **replace():** Replaces only the first occurrence of a pattern.

   **replaceAll():** Replaces all occurrences of a pattern.

   **(i),replace();**
        
        let str = "Hello world, welcome to the world of JavaScript!";
        let result = str.replace("world", "universe");

   console.log(result); 

   **// Output:** "Hello universe, welcome to the world of JavaScript!"

   **(ii),replaceAll();**

            let str = "Hello world, welcome to the world of JavaScript!";
            let result = str.replaceAll("world", "universe");

    console.log(result); 

   **// Output:** "Hello universe, welcome to the universe of JavaScript!"
   

**14. write a program to find a minimum in array**
       
        function user(arr){
            if(arr.length === 0){
                return "Array is Empty";
            }
            return Math.min(...arr);
        }
        let num = [2, 90, 99, 88, 34];
        
        console.log(user(num));


**15. Write a program**
        
        *****
        ****
        ***
        **        
        *

        function user(star){
    for(let i=star; i>=1;i--){
        let twinkle='';
        for(j=1;j<=i; j++){
            twinkle +="*"
        }
        console.log(twinkle);
    }
  }
  user(5)

   **Output**

        *****
        ****
        ***
        **
        *


**16. What would be the result of 3+2+”7″?**
    
   Here, 3 and 2 behave like an integer, and “7” behaves like a string. So 3 plus 2 will be 5. Then the output will be **5+”7″ = 57.**


**17. Math Properties:**

   **(i) Math.PI()**
            
   console.log(Math.PI);    
            **// output: 3.141592653589793**
       
   **(ii) Math.trunc()** 
           
   console.log(Math.trunc(5.4));   
            **// output: 5**
       
   **(iii) Math.round()**
           
   console.log(Math.round(5.4));    
            **// output: 5**
       
   **(iv) Math.ceil()** 
          
   console.log(Math.ceil(5.3));    
            **// output: 6**
       
   **(v) Math.floor()** 
           
   console.log(Math.floor(4.8));   
            **// output: 4**
       
   **(vi) Math.pow()** 

   console.log(Math.pow(3,4));
            **// output: 81**
       
   **(vii) Math.min()** 
               
   console.log(Math.min(4,6));   
              **// output: 4**
       
   **(viii) Math.max()** 
               
   console.log(Math.max(6,3));    
              **// output: 6**
       
   **(ix) Math.random()** 
               
   console.log(Math.random());    
             **// output: 0.5487990729071615**
       
   **(x) random integer generation** 
   
   console.log(Math.floor(Math.random()*100+1));    
             **// output: 55**

   **(xi) Math.abs()**

   console.log(Math.abs(-9.8));  
               **// output: 9.8** 

   **(xii) Math.sqrt()**

   console.log(Math.sqrt(16));
              **// output: 4** 
        
          
**18. Memoization**

        Memoization is the process of caching the result of a function based on its inputs, so the function doesn't need to recompute the result if the same inputs are given again

            function add(num1, num2) {
              console.log('Calculating...');
              return num1 + num2;
            }
            
            function memoize(fn) {
              let cache = {};
              return function (num1, num2) {
                let key = num1 + ',' + num2;
                if (cache[key]) {
                  return cache[key];
                } else {
                  let result = fn(num1, num2);
                  cache[key] = result;
                  return result;
                }
              };
            }
            
            const memoizedAdd = memoize(add);
            
            console.log(memoizedAdd(2, 3)); // First time
            console.log(memoizedAdd(2, 3)); // Second time (from cache)

   **//OutPut:**

       Calculating...
       5
       5


**19. //  Write a JavaScript function to print the following  number pattern:**

            function numbers(row){
                for(let i=1; i <= row; i++){
                    let total="";
                    for(let j=1; j <=i; j++){
                        total += j + ' '
                    }
                    console.log(total)
                }
                
            }
            numbers(5)       


   **outPut**

        // 1
        // 1 2
        // 1 2 3
        // 1 2 3 4
        // 1 2 3 4 5


**20. How can we print object properties or models in JavaScript?**

     In JavaScript, object properties or models can be printed in several ways:

   **1.Dot Notation:**
           **eg;**
                console.log(objectName.propertyName);

   **2.Bracket Notation:**
          **eg;**
                console.log(objectName['propertyName']);

   **3.Destructuring:**
           **eg;**
                let{username,age}
                console.log(username+age)

                
**21.remove duplicates**

        const array = [1, 2, 2, 3, 4, 4, 5];
        const uniqueArray = array.filter((value, index) => array.indexOf(value) === index);
        
        console.log(uniqueArray);

   **Output:  [1,2,3,4,5]**


**22.  Sum of all Elements**
        
        let arr = [1, 2, 3, 4];
        let sum = arr.reduce((acc, val) => acc + val,0); 
        console.log(sum) 

   **output: 10**        


**23. //  Write a function to calculate the area of a rectangle.
//  It should take the length and width as parameters and 
//  return the calculated area.**


            function calculateArea (length,width){
              return length*width;
            }
            console.log(calculateArea(6,7));

   **output: 42** 


**24. How to center elements in dynamic**
        
        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Document</title>
            <style>
                *{
                    margin: 0;
                    padding: 0;
                    box-sizing: border-box;
                }
                body{
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    min-height: 100vh;
                }
                #parent{
                    display: grid;
                    grid-template-columns: repeat(5,auto);
                    justify-content: center;
                    align-items: center;
                    width: 1000px; 
                    gap: 10px;
                }
                .child{
                    width: 200px;
                    height: 300px;
                    background-color: black;
                }
            </style>
        </head>
        <body>
            <div id="parent">
                <div class="child"></div>
                <div class="child"></div>
                <div class="child"></div>
                <div class="child"></div>
                <div class="child"></div> 
                <div class="child"></div> 
                <div class="child"></div> 
            </div>
        
            <script>
                const childCount = document.getElementById("parent").childElementCount;
                const parent = document.getElementById("parent");
                if(childCount == 6){
                    parent.style.gridTemplateColumns = 'repeat(3,auto)'
                } else if( childCount == 7 ){
                    parent.style.display = 'flex'
                    parent.style.flexWrap = 'wrap'
                }
            </script>
        </body>
        </html>


**25.What will be the output of the following code? Explain why there is a difference in output between using let and var in the loop.** 

            const b = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

            for (let i = 0; i < 10; i++) {
              setTimeout(() => console.log(b[i]), 1000);
            }

            for (var i = 0; i < 10; i++) {
              setTimeout(() => console.log(b[i]), 1000);
            }

   **Output:**
            1
            2
            3
            4
            5
            6
            7
            8
            9
            10
            undefined
            undefined
            undefined
            undefined
            undefined
            undefined
            undefined
            undefined
            undefined
            undefined


**26. Write a function to calculate the circumference of a circle. It should take the radius as a parameter and return the calculated circumference.**

   **Solution:-**

                function circumference(radius){
                return 2  Math.PI  radius;
                }


**27. Write a function to convert minutes to seconds. It should take the number of minutes as a parameter and return the equivalent number of seconds.**

        function minutesToseconds (minutes){
          
          return minutes * 60;
        }
        console.log(minutesToseconds(5));

   **//Output: 300**


**28. Write a function to check if a given number is even or odd. The function should take a number as a parameter and return 
a string indicating whether the number is even or odd.**

            function check (number){
              if (number% 2===0){
                return "even";
              }
              else {
                return "odd";
              }
            }
            let number = 10;
            
            console.log(check(number));
            
