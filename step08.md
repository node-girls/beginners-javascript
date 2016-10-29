# Step 8: Arrays

It was mentioned earlier that there are data types other than strings, integers and booleans. An array is one of these. Arrays allow you to easily store multiple values together.

The syntax is to list the values separated by commas, inside square brackets:

```js
[value1, value2, value3]
```

You can store any type of value inside an array: strings, numbers, booleans. You can even store other arrays, or objects (which you will learn about next).

## Try it out

Defining an array as a variable looks something like this:

```js
var animals = ["tiger", "puppy", "snake", "llama"];
```

Pretty neat! Now you have all the animals grouped together rather than having to define them separately. You can see how many animals there are by using `.length`:

```js
console.log(animals.length);
```

If you want to refer to one specific member of the array, you can do so by using their "index number" like so.

```js
console.log(animals[1]);
```

Take a guess at which animal that will print out, and see if you're right.

Spoiler alert, it will print out "puppy". That might seem weird, until you learn that JavaScript is a "0-index" language. What that means is that counting in JavaScript starts at 0. So `animals[0]`will print out "tiger". We don't make the rules...

## Mini challenge

How would you `console.log()` the name of every animal in the array?

If you're thinking a for loop, you're right. This is the perfect opportunity to use our newfound for loop skills for a higher purpose.

Try googling to find the answer if you're stuck. Google skills are an essential part of being a developer.

### [Go to Step 9 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step09.md)
