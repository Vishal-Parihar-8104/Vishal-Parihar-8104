- 👋 Hi, I’m @Vishal-Parihar-8104


<!---
Vishal-Parihar-8104/Vishal-Parihar-8104 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Array Function in Js 
// 1. Add elements using push() and unshift()
let numbers = [1, 2, 3, 4];
numbers.push(5);        
numbers.unshift(0);    
console.log("Final array (1):", numbers); 


let fruits = ["Apple", "Banana", "Mango", "Grapes", "Orange"];
fruits.pop();          
fruits.shift();          
console.log("Modified fruits array (2):", fruits); 

let arr = [10, 20, 30, 40];
arr.splice(1, 1, 25);     
console.log("Spliced array (3):", arr); 

let colors = ["Red", "Green", "Blue", "Yellow"];
let colorString = colors.join('-');
console.log("Joined string (4):", colorString); 

let numArray = [100, 200, 300];
let stringResult = numArray.toString();
console.log("Array toString() result (5):", stringResult); 

let arr6 = [5, 10, 15, 20];
console.log(arr6.at(-1)); 

let arr7 = [1, 2, 3, 4, 5];
arr7.copyWithin(3, 0, 2);
console.log(arr7);  

let arr8 = [1, [2, 3], [4, [5]]];
let flatArr8 = arr8.flat(2);
console.log(flatArr8);  

let arr9 = [10, 20, 30, 40, 50];
let midTwo = arr9.slice(1, 3);  
console.log(midTwo);  

let arr10a = [1, 2];
let arr10b = [3, 4];
let merged = arr10a.concat(arr10b);
console.log(merged);  

let arr11 = [10, 20, 30, 40, 50];
delete arr11[2];  
console.log(arr11);      
console.log(arr11.length);  





let arr12 = [9, 8, 7, 6];
let newArr12 = arr12.toSpliced(1, 1, 10, 11);
console.log(arr12);    
console.log(newArr12); 

let arr13 = [1, 2, 3, 4, 5];
arr13.splice(-2, 2);  
console.log(arr13);   

let arr14 = [7, 8, 9];
let copy14 = arr14.slice();
copy14.unshift(6);
console.log(arr14);
console.log(copy14);  

function joinWithQuote(arr) {
    return arr.join("'");
}

console.log(joinWithQuote([1, 2, 3]));  
function getLastItem(arr) {
    return arr[arr.length - 1];
}

console.log(getLastItem([1, 2, 3, 4]));  

function getSecondLastItem(arr) {
    return arr.at(-2);
}

console.log(getSecondLastItem([10, 20, 30, 40])); 

function reverseArray(arr) {
    let result = [];
    for (let i = 0; i < arr.length; i++) {
        result.unshift(arr[i]);
    }
    return result;
}

console.log(reverseArray([1, 2, 3, 4]));  

function flatten2DArray(arr) {
    return arr.flat();
}

console.log(flatten2DArray([[1, 2], [3, 4]]));

function combineNamesAndMarks(names, marks) {
    let result = [];
    for (let i = 0; i < names.length; i++) {
        result.push(names[i] + ": " + marks[i]);
    }
    return result;
}

let names = ["Ram", "Shyam"];
let marks = [80, 90];
console.log(combineNamesAndMarks(names, marks)); 

