# Step 7: Functions

We've been writing code that performs different actions, but sometimes you want to group code together to achieve a particular end. This is where functions come in.

A function is a block of code designed to perform a particular task. A function is executed when it is "invoked".

The syntax of a function looks like this:

```js
function functionName (parameters) {
  // code to be executed
}
```

You can call a function whatever you want, just like a variable. You can also give a function different values every time you run it which are called "parameters".

To make the function run, we invoke it like so:

```js
functionName();
```

### Try it out

Let's write a function that adds two numbers together. We'll call it `add`. We want to add together two different numbers every time, so let's define two parameters to represent this, `x` and `y`.

```js
function add (x, y) {
  // code to be executed
}

add(2, 3);
```

Notice I've invoked the function underneath, with the parameters `2` and `3`. Inside the function, try to `console.log()` both `x` and `y` and see what happens. Try logging them outside the function too. They will be undefined, because we can only access these parameters from inside the function.

```js
function add (x, y) {
  console.log(x);
  console.log(y);
}

add(2, 3);
```

Now, we want to add these two numbers together, but it isn't enough just to write `x + y`, since we haven't told the function to actually return anything. It's time for a `return` statement. This is usually how you end a function. The return statement specifies the value to output to the console.

```js
function add (x, y) {
  return x + y;
}

add(2, 3);
```

Run this code, and hopefully you get the right answer!

### Mini challenge

Write a function called `multiply` that multiplies two numbers together. It should take two numbers as parameters and return the answer.

### [Go to Step 8 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step08.md)
