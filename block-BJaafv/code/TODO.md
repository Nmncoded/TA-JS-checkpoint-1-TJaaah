1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

Ans - Value of 'first' is 'number'  and value of 'second' is 'undefined'

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

Ans - Output will be 36. Because only two parameters are available .

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

Ans - 

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1

showMessage(); // Output 2

alert(userName); // Output 3
```

8. What is a Anonymous Function give example of three functions.

An anonymous function is a function that was declared without any named identifier to refer to it. As such, an anonymous function is usually not accessible after its initial creation. Normal function definition: function hello() { alert('Hello world'); } hello();

9. Can function declaration be a Anonymous Function? Explain

Anonymous Function is a function that does not have any name associated with it. ... An anonymous function is not accessible after its initial creation, it can only be accessed by a variable it is stored in as a function as a value. An anonymous function can also have multiple arguments, but only one expression

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
let userAge = NaN;
if(userAge === NaN){
  alert(`The value is NaN`)
}  else{
  alert(`the value if not NaN`)
}


let user1 = 'Sameer';
let user2 = 'sameer';
if(user1 === user2){
  alert(`The value is equal`)
}  else{
  alert(`the value if not equal`)
}