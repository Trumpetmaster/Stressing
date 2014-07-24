Stressing JS Lesson
=======================
This will teach you how to create your own anime character.  

# Installation

### On runnable.com:
Create a new node app, and from the terminal, enter or cut and paste the following commands, then press enter or return:
    
    git clone https://github.com/Trumpetmaster/Stressing.git spark && spark/setup.sh
    
...some text will fly by as the repository is cloned locally and the project is setup.

Great, you're set to roll!

 
# Lets give our anime character some idenity!

**Properties and Behaviors!**

Firstly, we are going to create an object, or body, for our person. Objects are made up of two key things which 
are properties and behaviours. Properties are what the object has. For example, a phone has a battary, a screen,
some bottons, and some other stuff. Bheaviours are the action the phone carries out.They are essentially 
functions or otherwise known as methods. For expample, the phone can turn on, go on the internet, play music,
games, videos, etc. Think of an object as play doe. It has many forms and can be shaped into anything. 
To create one, you can simply do:

var myObject = {};

We are assigning the variable my object to an empty object. Objects are represented with curly brackets, or 
braces. So when we use = {}, we're saying, equals an empty Object. This is an object literal. 


**TODO 1 :** Lets make an object. Go to TODO 1.


```javascript
#!/usr/bin/env node

// TODO 1 : create variables for prompt and fs by calling require in each respective module:
var person = {};
console.log(person);

```
Alright, save and then run the app!


**Run the App** Switch to the command line, and go ahead and run the app like so:

    # ./my-lesson.js
    
    
 And Huston we have a takeoff!!! we have a person Object ...but ...wait, the person is blank! 
 You can see when we logged the person Object using console.log(person);, we were given {}, literally a blank,
 empty Object! Objects store their values by a String key, the key being the name of the property, and we 
 can use that key to look up the value of property. The literal syntax for creating properties on an Object 
 looks like this:
 
 ```
 var myObject = {id: 1, 
                name: "Some Object"};

console.log(myObject.id)   // prints: 1;
console.log(myObject.name) // prints: Some Object;

```
# Now Lets give our homie a name!
### We are going to spice up this pot of soup...

TODO 2: Add firstName and lastName properties to our person:
```
person.firstName = "Berry";
person.lastName = "The Chopper";
console.log("First Name: " + person.firstName);
console.log("Last Name: " + person.lastName);
```

Cool, lets save and run... 
Properties : Array Syntax

TODO 3 : So, because the keys of an Object are actually Strings, we can also use the syntax:

```
myObject["type"] = "Awesome Object"; 

```
to create properties, sometimes called Array syntax. Go ahead and add a 
city property to our person:

```
// TODO 3 : Add the city property using Array syntax:

person["city"] = "Central";
console.log("City: " + person.city);

```
 That's what's up!
 
 Behaviours : Functions as Methods

Okay, so we've given our person a bit more of a personality in that we've added some properties to the person
Object. What about behaviours? Remember we said Objects are made of properties and behaviours. Here we come 
to functions, or otherwise known as in the object oriented world, methods.

Functions are a group of statements executed one after another within their own sort of subprogram or closed 
environment - called a closure - think of them like a program wihtin a program. And we can store them in 
memory by assinging them to a variable or constant so that we can run them again and again. This helps with 
maintainability, but because they kind of have their own private world when they execute, they are extremely
powerful. Instead of passing around a value, we can pass around a whole set of instructions that perform all
kinds of calculations and retrieval of data!

TODO 4 : Object oriented programming tries to model objects in a system like objects in the real world. So,
a car has wheels and an engine, that is, properties, and methods by which we can start it, steer it, and 
stop it - hopefully! We know what properties are, methods are merely functions we attach to objects to act as
methods or behaviours of the object - and here's a tip, methods are most often named using a verb:

// TODO 5 : Create a function that prints the firstName, lastName and city of the person:

person.sayHello = function() {
  console.log("Hello, my name is " + this.firstName + " " + this.lastName + ", I live in " + this.city);  
}
person.sayHello();

&copy; John Fraboni 2014