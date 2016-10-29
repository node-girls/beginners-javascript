# Step 5: If/Else Statements

Now we're going to start adding in some logic. So far we have been logging the same thing every time we run the code, but what if we want to log according to different conditions? In programming there is something called an "if/else statement". It tests conditions, and will perform different actions based on the outcome of these tests.

The structure of an if/else statement in JavaScript is as follows:

```js
if (condition) {
  // do something
} else {
  // do something else
}
```

It basically translates to "if this condition is true, do this - or else do something else".

### Try it out

What if we want to `console.log()` "Hello world!" if we're feeling happy, and something else if we're sad?

Let's define a variable called `happy`, and assign it a boolean value of `true` or `false` (depending on how happy you're feeling).

```js
var happy = true;
```

Then let's write our if/else statement. In our condition, we want to test if the variable `happy` is equal to `true`. Note that in JavaScript, to test if two things are equal you need to use a triple equals (`===`) rather than just one (`=`). Read more about that [here](http://www.w3schools.com/js/js_operators.asp) if you're curious.

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
  // if I am happy, print "Hello world!"
  console.log('Hello world!');
} else {
  // if I am sad, print a frowny face
  console.log(':(');
}
```

Now run this code (not forgetting to put the variable at the top of the Repl), and see what happens! Try changing the value of your variable from `true` to `false`.

### Mini challenge

Write an if/else statement that evaluates if a number is even or odd. If it is even, it will print the string `'even'`, and if it is odd, it will print `'odd'`.

For this challenge, you might find it useful to use the "modulo" operator, which looks like this: `%`. The modulo operator finds the remainder after division of one number by another. For example:

```js
13 % 2 === 1 // 13 divided by 2 leaves a remainder of 1
100 % 10 === 0 // 100 divided by 10 leaves a remainder of 0
```

Read more about the modulo operator [here](http://www.w3schools.com/js/js_operators.asp).

### [Go to Step 6 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step06.md)
