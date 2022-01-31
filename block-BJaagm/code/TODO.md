1. What does thread of execution means in JavaScript?

2. Where the JavaScript code gets executed?

   //global execution context
3. What does context means in Global Execution Context?

   //it is the enviroment here you can execute the code
4. When do you create a global execution context.

   //when we run the program for the first time
5. Execution context consists of what all things?

   //memory part where all the variables gets memmory allocation and the other part is execution part
6. What are the different types of execution context?

   //global and function execution context
7. When global and function execution context gets created?

   //when we run the code for first time the gec will get created and when we call the function aur create a function //then fec will get created
8. Function execution gets created during function execution or while declaring a function.


   //both the times

 
9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";
function sayHello(){
function sayHello() {
  return `Hello ${user}`;
}
@@ -33,13 +30,11 @@ var userMsg = sayHello(user);

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;
function getPercentage(amount, totalAmount){
function getPercentage(amount, totalAmount) {
  return (amount * 100) / totalAmount;
}
@@ -51,15 +46,13 @@ var percentageProfit = getPercentage(400, 200);

![](./img/image-name.jpg)



```js
var age = 21;
function customeMessage(userAge){
  if(userAge > 18){
function customeMessage(userAge) {
  if (userAge > 18) {
    return `You are an adult`;
  }else {
  } else {
    return `You are a kid`;
  }
}
@@ -70,4 +63,4 @@ var whoAmIAgain = customeMessage(12);

<!-- Put your image here -->

![](./img/image-name.jpg)
![](./img/image-name.jpg)