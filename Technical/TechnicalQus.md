1.   In Javascript write a function that takes a string. Split the string by dot(.) and returns the second last string from that split. If there are no dots in the original string return an empty string. For example the parameter "ggg.ttt.com" the function returns "ttt"?

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
