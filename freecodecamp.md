# 	1

```js
// This is an in-line comment.
/* This is a
multi-line comment */

```

#	2

```js
// Example
var ourName;

// Declare myName below this line
var myName;

```

#	3

```js
// Setup
var a;
var b = 2;

// Only change code below this line
a = 7;
b = a;

```

#	4

```js
// Example
var ourVar = 19;

// Only change code below this line
var myVar = 0;
var a = 9;

```

#	5

```js
// Initialize these three variables
var a;
var b;
var c;

// Do not change code below this line

a = a + 1;
b = b + 5;
c = c + " String!";

a = 6;
b = 15;
c = "I am a String!";

```

#	6

```js
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;

```

#	7

```js
var sum = 10 + 10;

```

#	8

```js
var difference = 45 - 33;

```

#	9

```js
var product = 8 * 10;

```

#	10

```js
var quotient = 66 / 33;

```

#	11

```js
var myVar = 87;

// Only change code below this line
var myVar = 87;myVar++;

```

#	12

```js
var myVar = 11;

// Only change code below this line
var myVar = 11;myVar--;

```

#	13

```js
var ourDecimal = 5.7;

// Only change code below this line
var myDecimal = 3.2;

```

#	14

```js
var product = 2.0 * 0.0;

var product = 2.0 * 2.5;

```

#	15

```js
var quotient = 4.4 / 2.0; // Fix this line

```

#	16

```js
// Only change code below this line

var remainder;
remainder = 71 % 3;

```

#	17

```js
var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line

a += 12;
b += 9;
c += 7;

```

#	18

```js
var a = 11;
var b = 9;
var c = 3;

// Only modify code below this line

a -= 6;
b -= 15;
c -= 1;

```

#	19

```js
var a = 5;
var b = 12;
var c = 4.6;

// Only modify code below this line

a *= 5;
b *= 3;
c *= 10;

```

#	20

```js
var a = 48;
var b = 108;
var c = 33;

// Only modify code below this line

a /= 12;
b /= 4;
c /= 11;

```

#	21

```js
// Example
var firstName = "Alan";
var lastName = "Turing";

// Only change code below this line
var myFirstName = "Yousef"; 
var myLastName = "Katat";

```

#	22

```js
var myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line

```

#	23

```js
var myStr = '<a href="http://www.example.com"target="_blank">Link</a>';

```

#	24

```js
var myStr = "FirstLine\n\t\\SecondLine\nThirdLine"; 
// Change this line

```

#	25

```js
// Example
var ourStr = "I come first. " + "I come second.";

// Only change code below this line

var myStr = "This is the start. " + "This is the end.";

```

#	26

```js
// Example
var ourStr = "I come first. ";
ourStr += "I come second.";

// Only change code below this line

var myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";

```

#	27

```js
// Example
var ourName = "freeCodeCamp";
var ourStr = "Hello, our name is " + ourName + ", how are you?";

// Only change code below this line
var myName = "Yousef";
var myStr = "My name is " + myName + " and I am well!";

```

#	28

```js
// Example
var anAdjective = "awesome!";
var ourStr = "freeCodeCamp is ";
ourStr += anAdjective;

// Only change code below this line

var someAdjective = "awesome!";
var myStr = "Learning to code is ";
myStr += someAdjective;

```

#	29

```js
// Example
var firstNameLength = 0;
var firstName = "Ada";

firstNameLength = firstName.length;

// Setup
var lastNameLength = 0;
var lastName = "Lovelace";

// Only change code below this line.

lastNameLength = lastName.length;

```

#	30

```js
// Example
var firstLetterOfFirstName = "";
var firstName = "Ada";

firstLetterOfFirstName = firstName[0];

// Setup
var firstLetterOfLastName = "";
var lastName = "Lovelace";

// Only change code below this line
firstLetterOfLastName = lastName[0];

```

#	31

```js
// Setup
var myStr = "Jello World";

// Only change code below this line

myStr = "Hello World"; // Fix Me

```

#	32

```js
// Example
var firstName = "Ada";
var secondLetterOfFirstName = firstName[1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var thirdLetterOfLastName = lastName[2];

```

#	33

```js
// Example
var firstName = "Ada";
var lastLetterOfFirstName = firstName[firstName.length - 1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var lastLetterOfLastName = lastName[lastName.length - 1];

```

#	34

```js
// Example
var firstName = "Ada";
var thirdToLastLetterOfFirstName = firstName[firstName.length - 3];

// Setup
var lastName = "Lovelace";

// Only change code below this line
var secondToLastLetterOfLastName = lastName[lastName.length - 2];

```

#	35

```js
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
  // Your code below this line
  var result = "";
  result = "My " + myNoun + " is " + myAdjective + " and " + myVerb + " " + myAdverb + "!";

  // Your code above this line
  return result;
}

// Change the words here to test your function
wordBlanks("dog", "big", "ran", "quickly");

```

#	36

```js
// Example
var ourArray = ["John", 23];

// Only change code below this line.
var myArray = ["Yousef", 69];

```

#	37

```js
// Example
var ourArray = [["the universe", 42], ["everything", 101010]];

// Only change code below this line.
var myArray = [["Hi", 11], ["Hello", 7]];

```

#	38

```js
// Example
var ourArray = [50,60,70];
var ourData = ourArray[0]; // equals 50

// Setup
var myArray = [50,60,70];

// Only change code below this line.
var myData = myArray[0];


```

#	39

```js
// Example
var ourArray = [18,64,99];
ourArray[1] = 45; // ourArray now equals [18,45,99].

// Setup
var myArray = [18,64,99];

// Only change code below this line.
myArray[0] = 45; 


```

#	40

```js
// Setup
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];

// Only change code below this line.
var myData = myArray[2][1];


```

#	41

```js
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.push(["happy", "joy"]); 
// ourArray now equals ["Stimpson", "J", "cat", ["happy", "joy"]]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
myArray.push(["dog", 3]);


```

#	42

```js
// Example
var ourArray = [1,2,3];
var removedFromOurArray = ourArray.pop(); 
// removedFromOurArray now equals 3, and ourArray now equals [1,2]

// Setup
var myArray = [["John", 23], ["cat", 2]];

// Only change code below this line.
var removedFromMyArray = myArray.pop();


```

#	43

```js
// Example
var ourArray = ["Stimpson", "J", ["cat"]];
var removedFromOurArray = ourArray.shift();
// removedFromOurArray now equals "Stimpson" and ourArray now equals ["J", ["cat"]].

// Setup
var myArray = [["John", 23], ["dog", 3]];

// Only change code below this line.
var removedFromMyArray = myArray.shift();

```

#	44

```js
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.shift(); // ourArray now equals ["J", "cat"]
ourArray.unshift("Happy"); 
// ourArray now equals ["Happy", "J", "cat"]

// Setup
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();

// Only change code below this line.
myArray.unshift("Paul", 35);

```

#	45

```js
var myList = [["Chocolate Bar", 15],["Chocolate Bar", 15],["Chocolate Bar", 15],["Chocolate Bar", 15],["Chocolate Bar", 15]];

```

#	46

```js
// Example
function ourReusableFunction() {
  console.log("Heyya, World");
}

ourReusableFunction();

// Only change code below this line
function reusableFunction() {
    console.log("Hi World");
}

reusableFunction();

```

#	47

```js
// Example
function ourFunctionWithArgs(a, b) {
  console.log(a - b);
}
ourFunctionWithArgs(10, 5); // Outputs 5

// Only change code below this line.
function functionWithArgs (x, z) {
  console.log(x + z);
}
functionWithArgs (7, 12);

```

#	48

```js
// Declare your variable here
var myGlobal = 10;

function fun1() {
  // Assign 5 to oopsGlobal Here
  oopsGlobal = 5;
}

// Only change code above this line
function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}

```

#	49

```js
function myLocalScope() {
  'use strict'; // you shouldn't need to edit this line
  
  console.log(myVar);
}
myLocalScope();
var myVar;
// Run and check the console
// myVar is not defined outside of myLocalScope
console.log(myVar);

// Now remove the console log line to pass the test

```

#	50

```js
// Setup
var outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
  var outerWear = "sweater";
  
  
  // Only change code above this line
  return outerWear;
}

myOutfit();

```

#	51
