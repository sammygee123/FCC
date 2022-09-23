# Free Code Camp Projects
## Use Bracket Notation to Find the Nth-to-Last Character in a String
```  // Setup
const lastName = "Lovelace";

// Only change code below this line
const secondToLastLetterOfLastName = lastName[lastName.length-2]; // Change this line
```
# Nest one Array within Another Array
```const teams = [["Bulls", 23], ["White Sox", 45]];
```
# Access Array Data with Indexes
We can access the data inside arrays using indexes.

Array indexes are written in the same bracket notation that strings use, except that instead of specifying a character, they are specifying an entry in the array. Like strings, arrays use zero-based indexing, so the first element in an array has an index of 0.


Example

const array = [50, 60, 70];
console.log(array[0]);
const data = array[1];
The console.log(array[0]) prints 50, and data has the value 60.

``` const myArray = [50, 60, 70];
let myData = myArray[0]
```
# Modify Array Data With Indexes

Modify the data stored at index 0 of myArray to a value of 45.
```const myArray = [18, 64, 99];
myArray[0] = 45
```

# Access Multi-Dimensional Arrays With Indexes
One way to think of a multi-dimensional array, is as an array of arrays. When you use brackets to access your array, the first set of brackets refers to the entries in the outer-most (the first level) array, and each additional pair of brackets refers to the next level of entries inside.

Example
```
const arr = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
  [[10, 11, 12], 13, 14]
];
```

const subarray = arr[3];
const nestedSubarray = arr[3][0];
const element = arr[3][0][1];
In this example, subarray has the value [[10, 11, 12], 13, 14], nestedSubarray has the value [10, 11, 12], and element has the value 11 .

# Manipulate Arrays With push()

Push ["dog", 3] onto the end of the myArray variable.
```const myArray = [["John", 23], ["cat", 2]];
myArray.push(["dog", 3])
```
# Manipulate Arrays With pop()
Use the .pop() function to remove the last item from myArray and assign the popped off value to a new variable, removedFromMyArray.
```const myArray = [["John", 23], ["cat", 2]];

const removedFromMyArray = myArray.pop()
```
# Manipulate Arrays With shift()
Use the .shift() function to remove the first item from myArray and assign the "shifted off" value to a new variable, removedFromMyArray.
```const myArray = [["John", 23], ["dog", 3]];
const removedFromMyArray = myArray.shift()
```
# Manipulate Arrays With unshift()
Add ["Paul", 35] to the beginning of the myArray variable using unshift().
```const myArray = [["John", 23], ["dog", 3]];
myArray.shift();
myArray.unshift(["Paul", 35]);
```
# Shopping List

Create a shopping list in the variable myList. The list should be a multi-dimensional array containing several sub-arrays.

The first element in each sub-array should contain a string with the name of the item. The second element should be a number representing the quantity i.e.

```const myList = [
  ["Chocolate Bar", 1],
  ["Cookies", 2],
  ["Protein", 15],
  ["Coconut Water", 15],
  ["Oat Milk", 15],
];
```
# Write Reusable JavaScript with Functions
Create a function called reusableFunction which prints the string Hi World to the dev console.
Call the function.
``` function reusableFunction(){
  console.log("Hi World");
}
reusableFunction();
```
# Passing Values to Functions with Arguments
Parameters are variables that act as placeholders for the values that are to be input to a function when it is called. When a function is defined, it is typically defined along with one or more parameters. The actual values that are input (or "passed") into a function when it is called are known as arguments.

Here is a function with two parameters, param1 and param2:

function testFun(param1, param2) {
  console.log(param1, param2);
}
Then we can call testFun like this: testFun("Hello", "World");. We have passed two string arguments, Hello and World. Inside the function, param1 will equal the string Hello and param2 will equal the string World. Note that you could call testFun again with different arguments and the parameters would take on the value of the new arguments.

Create a function called functionWithArgs that accepts two arguments and outputs their sum to the dev console.
Call the function with two numbers as arguments.
```function functionWithArgs(a,b) {
console.log(a+b);
}
functionWithArgs(1,2);
functionWithArgs(7,9);
```
# Return a Value from a Function with Return
We can pass values into a function with arguments. You can use a return statement to send a value back out of a function.

Example

function plusThree(num) {
  return num + 3;
}

const answer = plusThree(5);
answer has the value 8.

plusThree takes an argument for num and returns a value equal to num + 3.

Create a function timesFive that accepts one argument, multiplies it by 5, and returns the new value.

```function timesFive(num){
return num * 5;
}
const answer = timesFive(7);
```
# Local Scope and Functions
Variables which are declared within a function, as well as the function parameters, have local scope. That means they are only visible within that function.

Here is a function myTest with a local variable called loc.

function myTest() {
  const loc = "foo";
  console.log(loc);
}

myTest();
console.log(loc);
The myTest() function call will display the string foo in the console. The console.log(loc) line (outside of the myTest function) will throw an error, as loc is not defined outside of the function.

The editor has two console.logs to help you see what is happening. Check the console as you code to see how it changes. Declare a local variable myVar inside myLocalScope and run the tests.

Note: The console will still display ReferenceError: myVar is not defined, but this will not cause the tests to fail.

```function myLocalScope() {
  // Only change code below this line
let myVar
  console.log('inside myLocalScope', myVar);
}
myLocalScope();

// Run and check the console
// myVar is not defined outside of myLocalScope
console.log('outside myLocalScope', myVar);
```
