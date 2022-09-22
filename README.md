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