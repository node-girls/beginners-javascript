# Step 5: If/Else Statements

Now we're going to start adding in some logic. Right now we are always logging the same thing every time, but what if we want to log according to different conditions? In programming there is something called an "if/else statement". It tests conditions, and will perform different actions based on the outcome of these tests.

The structure of an if/else statement in JavaScript is as follows:

```js
if (condition) {
  // do something
} else {
  // do something else
}
```

### Try it out

What if we want to `console.log()` "Hello world!" if we're feeling happy, and something else if we're sad?

Let's define a variable called `happy`, and assign it a boolean value of `true` or `false` (depending on how happy you're feeling).

```js
var happy = true;
```

Then let's write our if/else statement. In our condition, we want to test if the variable `happy` is equal to `true`. Note that in JavaScript, to test if two things are equal you need to use a triple equals (`===`) rather than just one (`=`).

```js
if (happy === true) {
  // do something
} else {
  // do something else
}
```

Now let's add in what will happen if the conditions are met. The comments are there to explain what is happening.

```js
if (happy === true) {
  // if you are happy, print "Hello world!"
  console.log('Hello world!');
} else {
  // if you are sad, print a frowny face
  console.log(':(');
}
```

Run this code (not forgetting the variable at the top of the file), and see what happens!

### Mini challenge

Write an if/else statement that evaluates if a number is even or odd. If it is even, it will print the string `'even'`, and if it is odd, it will print `'odd'`.

For this challenge, you might find it useful to use the "modulo" operator, which looks like this: `%`. The modulo operator finds the remainder after division of one number by another. For example:

```js
13 % 2 = 1 // 13 divided by 2 leaves a remainder of 1
100 % 10 = 0 // 100 divided by 10 leaves a remainder of 0
```

### [Go to Step 6 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step06.md)
