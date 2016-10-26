# Step 4: Variables

When you code, you'll want to create shortcuts so you can easily refer to things without writing out the value every time. In JavaScript we have "variables", which allow us to store values to use later.

## Try it out

You create a variable using the keyword `var`, which lets the console know that you're about to store a value. You also have to give a name to your variable, which can be anything you like, so long as it doesn't include spaces.

Here's an example of creating a variable called "artist", which is storing a string called "Beyoncé Knowles".

```js
var artist = 'Beyoncé Knowles';

console.log(artist);
```

You'll notice that once you've created the variable, you can then simply write the name of the variable wherever you want to refer to it, rather than writing out Beyoncé's full name every time. You don't ever need quotes around a variable name.

Try to run the above code, and see what is printed to the console.

### Mini challenge

You should have some code left over from step 2 which looks something like this (maybe even with comments):

```js
console.log(typeof 'node girls');
console.log(typeof 1234);
console.log(typeof false);
```

Now that you know how to create variables, rewrite this code. This time, define these values as variables at the top of the file. Then refer to them by their variable names inside the `console.log()` statements, instead of writing out the whole values.

Is your output the same?

### [Go to Step 5 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step05.md)
