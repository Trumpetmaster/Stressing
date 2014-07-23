Stressing JS Lesson
=======================
This will teach you how to create your own anime character.  

# Installation

### On runnable.com:
Create a new node app, and from the terminal, enter or cut and paste the following commands, then press enter or return:
    
    git clone https://github.com/Trumpetmaster/Stressing.git spark && spark/setup.sh
    
...some text will fly by as the repository is cloned locally and the project is setup.

Great, you're set to roll!

 
# Lets give out anime character some idenity!

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

Often after you've explain the concept, shown code examples, then given some code the student needs to 
add in a TODO step, the student should be able to run the app so they can see the concept in action.
Remember that if, as in the example below, you want to run the app as an executable,
you'll need to ensure at the outset you've run `chmod u+x my-lesson.js` on the file to change 
its permissions to executable. We have already given executable permissions to the my-lesson.js files
included within the lesson plan template, but you should be aware of this caveat if you delete, add, 
or start from scratch.  Also, remember that if you do create your own files, _if_ they are the main 
entry point for your app and you entend them to run as executables,
you'll need to add the
<a href="https://github.com/jfraboni/simple-node-app/wiki/Shebang" target="_blank">Shebang</a> 
for node at the top of the file.  See the top of my-lesson.js for an example.

**Run the App** Switch to the command line, and go ahead and run the app like so:
And this is how you put a box around your text:

    # ./my-lesson.js


&copy; John Fraboni 2014