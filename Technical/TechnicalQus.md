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

