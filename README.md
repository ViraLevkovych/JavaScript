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
