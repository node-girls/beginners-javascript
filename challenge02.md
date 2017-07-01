# Challenge 2: Famous Writers

Did you know you can also have an array of objects? We've created one for you here. Loop through the array, and for each object, `console.log()` the following sentence:

```js
"Hi, my name is {firstName} {lastName}. I am {age} years old, and work as a {occupation}."
```

Ignore the brackets. They're just there to let you know a word should be replaced with something else. The sentence you log should look like this:

```js
"Hi, my name is Virginia Woolf. I am 59 years old, and work as a writer."
```

Here is the array:

```js
var writers = [
  {
    firstName: "Virginia",
    lastName: "Woolf",
    occupation: "writer",
    age: 59,
    alive: false
  },
  {
    firstName: "Zadie",
    lastName: "Smith",
    occupation: "writer",
    age: 41,
    alive: true
  },
  {
    firstName: "Jane",
    lastName: "Austen",
    occupation: "writer",
    age: 41,
    alive: false
  },
  {
    firstName: "bell",
    lastName: "hooks",
    occupation: "writer",
    age: 64,
    alive: true
  },
];
```

If you want an extra challenge, only `console.log()` the writers that are alive.

### [Go to Challenge 3 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/challenge03.md)
