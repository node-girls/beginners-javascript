# Challenge 1: Needle in a Haystack

- Give an array of objects (people), console.log the same sentence for all of them, only console.log if they are alive

Did you know you can also have an array of objects? We've created one for you here. Loop through the array, and for each object, `console.log()` out the sentence:

```js
"Hi, my name is {firstName} {lastName}. I am {age} years old, and work as a {occupation}."
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

### [Go to Challenge 2 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/challenge02.md)
