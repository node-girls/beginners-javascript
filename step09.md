# Step 9: Objects

Now for the final data type: objects. Like arrays, they can store multiple bits of information, except objects store the properties of something. For example, you might want to save the name, model and colour of a car. Or the name, time and location of a film playing at the cinema.

The syntax looks like this:

```js
{
  property1: "value1",
  property2: "value2",
  property3: "value3"
}
```

The names on the left ("property1") are known "keys". You can call them whatever you want, and any values can be given to them: strings, booleans, integers.

## Try it out

Let's define an object that represents a person:

```js
var person = {
  firstName: "Virginia",
  lastName: "Woolf",
  occupation: "writer",
  age: 59,
  alive: false
};
```

We can of course `console.log()` the entire object, but you can also reference just one of the properties. Run this code:

```js
console.log(person.firstName);
```

## Mini challenge

Using an object representing a person, `console.log()` a sentence introducing the person. Print out the following:

```js
"Hi, my name is {firstName} {lastName}. I am {age} years old, and work as a {occupation}."
```

Hint: you can construct a string by adding different strings and values together using the <strong>concatenation</strong> operator `+`. This includes the keys and values of objects. For example:

```js
var animal = {
    species: "cat", 
    name: "Tabitha"
};
console.log("My " + animal.species + "is called " + animal.name + ".");
```

Don't forget, you might need to include spaces.

### [Go to Challenge 1 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/challenge01.md)
