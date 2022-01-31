1. Convert the function below into different forms of function expression.
```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
2. Write Function Declaration or Function Expression next to the function.
```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```
```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```
```js
let percentage = (marks, total) => (marks * 100) / total;
```
3. Why is a function definition an expression in JavaScript? Give one example of function expression.
   //function defination wwhere u declare your function to perform perticular task
   //function expression is nothing but the statement whree all the steps of functions are included
4. Why is a function call an expression in JavaScript?
   //
5. Write VALID and INVALID next to each example below with the reason.
```js
function add(a, b) {
  return a + b;
}
let five = add(2, 3); // undefined
five = add; // function add(a, b) {
//return a + b;
//}
five = five(10, 11); // 21
five = function () {
  return "Hello";
}; // five = function () {
//return "Hello";
//};
```
6. What is the difference between function definition and function call? Explain with an example.
<!-- A function call means invoking or calling that function. Unless a function is called there is no use of that function. ... So the difference between the function and function call is, A function is procedure to achieve a particular result while function call is using this function to achive that task. -->
7. What is the similarities between function definition and function call?
8. Is the code below valid or invalid. Explain with reason.
```js
function hello() {
  console.log("Hello World!");
}
hello.user = "Sam"; // invalid
```
9. What is higher order function explain with an example.
   //A “higher-order function” is a function that accepts functions as parameters and/or returns a function.
10. Explain what is callback function. Why you can pass a function inside a function?
    //cb function is used as a parameret to a different finction where the defination of its ids utilized to get yhe result