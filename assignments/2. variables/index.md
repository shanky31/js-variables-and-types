1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark"; 
```
Name is Mark

2. Find the error if any
```js
  var product cost = 3.45;
```
Variable name should not have any spaces between them, and should be camel case 
 ```js
 var productCost = 3.45;
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World" Right
  'Hello World" Wrong
  "Hello World' Wrong 
  'Hello World' Right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man; valid
var 1girl; invalid
var woman3; invalid
var -girl; invalid
var blackDog; valid
var 42; invalid
var $42; invalid
var userName; valid
var x, y, z; invalid
var x = 5, y = 6, z = 7; invalid
var x = 5 + 10 + 2; valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var amountTwo = amount-80;

// Define a new variable and store the value that is 200 more then the value of amount.
var amountThree = amount+200;
// Define a new variable and store the value that is 4 times the value of amount.
var amounntFour = amount*4;
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var amountFive = amount%21;
```


Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark
result = johnAge||markAge
// Check who is younger
result = johnAge && markAge
// Check if their age is equal
johnAge == markAge
// Create a new variable and assign the age of john to new variable.
var newJohnAge = johnAge; 
// Check if john is equal to or greater then mark.
newJohnAge >= markAge
// Check if john is less then or equal to mark.
newJohnAge <= markAge
// Calculate the average age of john and mark and assign to a new variable.
var average = johnAge + markAge / 2;
```