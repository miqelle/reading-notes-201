# Problem Domain, Objects, and the DOM

*References are from Jon Duckett "JavaScript & JQuery" (pp.100-105; 183-242) & w3schools*

# What is inside of an object?

- Inside of an object variables become properties, and functions become methods.
- Objects contain a set of variables and functions that create a model of something in the real world.




# How do you create an object?

You define and create a JavaScript object with an object literal:
`const person = {firstName:"John" , lastName:"Doe", age:50, eyeColor:"blue"};`

Space and line breaks don't matter!! An object can be on multiple lines in your code editor like this:

`const person = {`
    `firstName: "John",`
    `lastName: "Doe",`
    `age: 50,`
    `eyeColor: "blue"`
`};`

- Separate each key from its value using a colon
- Separate each property and method with a comma (but not after the last value)


# What are some object rules?

- An object cannot have two keys with the same name, because keys are used to access their corresponding values.
- The value of a property can be a string, number, Boolean, array, or even another object
- The value of a method is always a function

*Instead of name/value pairs objects have key/value pairs (the key is the same as a variable name or function name)*

# What is the object?

- Ojects are the curly braces and their contents
- Objects are stored in a variable

*this*: is a keyword used to indicate that you ARE using a property of the object you're currently in. 

# How to access an object?

- Use dot notation:

`var mallName = mall.name;` (In this example mall is the object & *name* is the property)

`var mallName = mall.checkStoreHours();` (In this example mall is the object & checkStoreHours(); is the method aka function)


- You can also use square brackets:

`var hotelName = hotel['name'];`
`var roomsFree = hotel['checkAvailability']();`

- Square brackets are only used to access an object if: name or method contains special characters, the name is a number, or if a variable is being used instead of a property name



