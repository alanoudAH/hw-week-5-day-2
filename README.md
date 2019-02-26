# Javascript Homework

1.  Variables
    - https://www.youtube.com/watch?v=cXUWYZXru6o (7 min video)
    - https://www.codeanalogies.com/jsconstruction/ (interactive game)

2.  Conditions
    - https://blog.codeanalogies.com/2018/06/18/javascript-booleans-explained-by-going-to-court/

3.  Functions
    - https://www.codeanalogies.com/javascript-functions-explained

## Activity Assignment
Without running the following code, try to determine:

```js
let a = 1;
let b = 'bongos';
let c = true;

a = b;
b = c;
c = a;
```

### Your solution here:
1.  What is `a`?
```
a is .'bongos'..
```
2.  What is `b`?
```
b is ..true.
```
3.  What is `c`?
```
c is ..1.
```

## Activity Concatenation
Use the `+` operator to concatenate these strings together within a `console.log()`: "Please", "squeeze", "the", "cheese". Make sure there are spaces in-between each word.

```js
const firstWord = "Please";
const secondWord = "squeeze";
const thirdWord = "the";
const fourthWord = "cheese";
```
Result should be:
```js
"Please squeeze the cheese"
```

### Your solution here:
4.  Fill in the `console.log()`?
```js
console.log("Please"+""+"squeeze"+""+"the"+""+"cheese")
console.log (firstWord +""+secondWord+""+thirdWord+""+fourthWord);
```

Output a console log `The sum of 5 and 10 is 15` where the values for 5 and 10 are saved to variables, and where 15 comes from those variables being summed.
```js
const num1 = 5;
const num2 = 10;
```

### Your solution here:
5.  How can we make `num3` equal to the sum of `num1` and `num2`?
```js
// your solution here
var num1 =2;
var num2 =2 ;
num3 = num1+ num2 ;
```
6.  Use variables `num1`, `num2` and `num3` to fill in the `console.log()` to complete the sentence:

>The sum of 5 and 10 is 15

```js

console.log("The sum of 5 and 10 is = " + num3)
```

## Activity Comparisons
By just looking at the following expressions, determine in your mind whether or not each will evaluate to true or false
```
a) 999 > 999
b) 999 === 999
c) 999 !== 999
d) -5 >= -4
e) 100 <= -100
f) 20 + 5 < 5
g) 81 / 9 === 9
h) 9 !== 8 + 1
```
### Your solution here:
7.  Write `true` or `false` based on the list above
```
a) false
b) true  
c) false
d) false
e) false
f) false
g) true
h) false
```

## Activity Conditionals
Declare a variable equal to a number 0 to 100

Write a conditional statement that...
- If it is a multiple of 3, print “Fizz” instead of the number.
- If it is a multiple of 5, print “Buzz” instead of the number.
- If it is a multiple of both 3 and 5, print “FizzBuzz” instead of the number.
- Otherwise, print the number

### Your solution here:
8.  Write your javascript solution below
```js
// your answer here
```
let numbers >= 0 && numbers <= 100 ;
if (numbers * 3 ){
  console.log("Fizz");}
else if (numbers * 5) {
  console.log("Buzz");
}
else if (numbers * 3 && numbers * 5 ){
  console.log("FizzBuzz") ;
}
else {
  console.log(numbers)
}
let num = 0 ;
for (let num = 0 ; num <=100 ; num ++){
    if (num * 3 ){
        console.log("Fizz");}
    else if (num * 5) {
        console.log("Buzz");}
    else if (num * 3 && num * 5 ){
         console.log("FizzBuzz");}
    else {
         console.log(num);}
#### BONUS
9.  Research a [loop](https://javascript.info/while-for) so that your condition runs on every number from 0 to 100
```js
// your answer here
let  i = 0 ;
for (let i = 0 ; i <= 100 ; i++){
  alert (i)
}
```
10.  Research a [function](https://javascript.info/function-basics) so that your condition runs on every number from 0 to whatever number is passed into the function
```js
// your answer here
```
let num = 0;
function myFunction (num){
  return num
}

if  (num >=0 )
{
  function myFunction (num){
    return num
  }  
}

# Additional Resources
For more practice read about...
- https://javascript.info/variables
- https://javascript.info/types
- https://javascript.info/operators
- https://javascript.info/comparison
- https://javascript.info/ifelse
- https://javascript.info/logical-operators
