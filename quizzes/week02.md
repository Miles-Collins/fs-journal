# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, or const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
S — Single responsibility principle
O — Open closed principle
L — Liskov substitution principle
I — Interface segregation principle
D — Dependency Inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2. First, it is an array. Second, the first index of an array start at 0. So apple is 0, banana is 1, and lastly that makes pineapple 2.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
"if", "else", "else if"
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for Document Object Model. HTML
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Primitive values, Boolean, Null, Undefined, Number, String, Symbol, Objects and BigInt
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Function parameters are the names listed in the function's definition.
Function arguments are the real values passed to the function.
Parameters are initialized to the values of the arguments supplied.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
You can add, change, or delete properties to a reference value, whereas you cannot do it with a primitive value. 
```