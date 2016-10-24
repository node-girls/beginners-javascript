# Step 2: Data Types

If you played around with `console.log()` in the last step, you might have noticed that words always have to be inside quotes or else the code breaks, whereas numbers can work without quotes. Why is this? Well these are different data types in JavaScript. You'll need to learn the three main data types to get started coding.

## Strings

Strings are simple text, ranging anywhere from a single character to lengthy paragraphs. A string is always written inside a pair of quotes (single or double).

```js
'node girls'
```

## Integers

Numbers are known as "integers" in JavaScript. They do not need to be wrapped in quotes like strings, and can just be written as is.

```js
100
```

## Booleans

There is a special data type in JavaScript known as a "boolean" value. A boolean is either `true` or `false`, and can be written without quotes.

```js
true
```

### Try it out

You've seen what they look like, now make sure they are what you think they are. There is a built-in feature in JavaScript which allows you to check the type of a particular value: `typeof`.

Write this bit of code in your `script.js` file, refresh your browser and take a look in the console:

```js
console.log(typeof 'Hello world!');
```

You should see `string` printed to the console.

### Mini challenge

Now try that three times, once for each data type. Log the `typeof` for three different values: `"node girls"`, `1234` and `false`. You should get different output for each one.

### [Go to Step 3 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step03.md)
