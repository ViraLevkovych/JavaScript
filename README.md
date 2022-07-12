# 0. Links
[JSFiddle](https://jsfiddle.net/)  
[CodeCamp](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures)


# 1. Comments
```js
// this is in-line comment
/* this is a
multi-line comment */
```


# 2. Variables
```js
var a;
a = 5;
a = a + 1;
```


# 3. Fortune Teller
```js
/*

The Fortune Teller
Why pay a fortune teller when you can just program your fortune yourself?

Store the following into variables: number of children, partner's name, geographic location, job title.
Output your fortune to the screen like so: "You will be a X in Y, and married to Z with N kids."

*/

var numberOfChildren = 4;
var partnersName = "Queen Elizabeth";
var geographicLocation = "Willow Creeck";
var jobTitle = "Letsplayer";
alert ("You will be a " + jobTitle + " in " + geographicLocation + ", and married to " + partnersName + " with " + numberOfChildren + " kids." );
```




# Task 1.
```js
/*
Створити дві змінні - імя та прізвище.
Створити третю змінну - яка буде мати в собі імя і прізвище.
Створити змінну вік.
Створити змінну теперішній рік.
Вивести алерт : Імя та прізвище, рік народження.
*/

var name = "Vira ";
var surname = "Levkovych";
var n_s = name  + "та " + surname;
var age = 16;
var year = 2022;
alert(n_s + ", " + (year - age));
```



# How to create variables
You can create variables by using: 
* var (basic creation);
* let (try to use this, it check whether the variable has been used before);
* const (cannot be changed)

* **The best practice is to use CAPSLOCK for const names**
* **camelCase for let**


# Increment a Number with JavaScript
i++ is the same as i = i + 1  


# Decrement a Number with JavaScript
i-- is the same as i = i - 1



# Finding a Remainder in JavaScript
17 % 2 = 1 (17 is Odd)  
48 % 2 = 0 (48 is Even)  
**const remainder = 11 % 3;**


# Escaping Literal Quotes in Strings
```js
const sampleStr = "Alan said, \"Peter is learning JavaScript\".";
Alan said, "Peter is learning JavaScript".
```


# Escape Sequences in Strings
***Code	Output***
* ```\'	single quote```
* ```\"	double quote```
* ```\\	backslash```
* ```\n	newline```
* ```\r	carriage return```
* ```\t	tab```
* ```\b	word boundary```
* ```\f	form feed```

# Task 2.Assign the following three lines of text into the single variable myStr using escape sequences.
```js
FirstLine
    \SecondLine
ThirdLine
```


```const myStr = "FirstLine\n\t\\SecondLine\nThirdLine";```

# Find the Length of a String
```js
Use the .length property to set lastNameLength to the number of characters in lastName.


// Setup
let lastNameLength = 0;
const lastName = "Lovelace";

// Only change code below this line
lastNameLength = lastName.length;
alert(lastNameLength);
```



# Use Bracket Notation to Find the First Character in a String
```js
const firstName = "Charles";
const firstLetter = firstName[0];
```



# Task 3.
```js

/*
1. Створити константу name.
create variable age.
2. Створити константу surname.
3. Cтворити константу fullname using the previous variable.
4. Create variable, lengthOfFullName.
5. Create variable, third character in fullname.
6. Create variable, остача від ділення довжини імя на 2.
7. вивести

My name is 'name'.	I am from Lodz.
	I am 'age' years alt.
My name length is 'length'.
My name length remainder / 2 is 'value'\.
*/

const NAME = "Angelina";
let age = 47;
const SURNAME = "Jolie";
const FULLNAME = NAME + SURNAME;
let lengthOfFullName = FULLNAME.length;
let thirdCharInFullname = FULLNAME[2];
let nameLength = NAME.length;
let remainderName_2 = nameLength % 2;
alert(remainderName_2);
let all = "My name is " + NAME + "." + "\tI am from Los Angeles." + "\n\tI am " + age + " years old." + "\nMy name length is " + nameLength + "." + "\nMy name length remainder / 2 is "  + remainderName_2 + "\\" + "."; 
alert(all);
```
