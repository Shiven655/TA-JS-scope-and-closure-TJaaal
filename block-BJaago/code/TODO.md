1.

```js
var firstName = 'Arya';
var lastName = 'Stark';
var firstName = "Arya";
var lastName = "Stark";
function getFullName(first, last) {
  return `${first} ${last}`;
@@ -17,13 +17,15 @@ function sayHelloToUser(name) {
}
var fullName = getFullName(firstName, lastName);
var jon = getFullName('John', 'Snow');
var jon = getFullName("John", "Snow");
console.log(fullName);
var userMessage = sayHelloToUser('Bran');
var userMessage = sayHelloToUser("Bran");
```

image

<!-- Put your image below -->

![](./img/image-name.jpg)
@@ -32,7 +34,7 @@ var userMessage = sayHelloToUser('Bran');

```js
function sayHi() {
  var name = 'Lydia';
  var name = "Lydia";
  var age = 21;
  console.log(name);
  console.log(age);
@@ -51,7 +53,7 @@ sayHi();
function sayHi() {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  var name = "Lydia";
  var age = 21;
}
@@ -67,7 +69,7 @@ sayHi();
```js
console.log(arr); // output
console.log(username); // output
var usename = 'Sam';
var usename = "Sam";
var arr = [1, 2, 3, 4, 5, 6];
function double(num) {
  return num * 2;
}
```