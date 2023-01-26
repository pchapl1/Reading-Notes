## Class 6 reading

### How would you describe an object to a non-technical friend you grew up with?
    - a way to keep and store data in a dictionary like collection

### What are some advantages to creating object literals?
    - good to use when you want to transfer data in a request to a server.  its more efficient that sending several single items
    source: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics

### How do objects differ from arrays?
    - they store data as key, value pairs

### Give an example for when you would need to use bracket notation to access an objects property instead of dot notation.
    - when an object property name is held in a variable

### Evaluate this code below. What does the term "this" refer to and what is the advantage to using "this"?

    const dog = {
    name: 'Spot',
    age: 2,
    color: 'white with black spots',
    humanAge: function (){
        console.log(`${this.name} is ${this.age*7} in human years`);
    }
    }

    - this refers to the object itself.  the advantage to using it comes in when you have more than one object and it allows you to use the same method definition for every object created


### What is the DOM?
    - The dom is the document object model. It is a programming interface for web documents. It represents the page so that programs can change the document structure style and content.
    source: https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction

### Briefly describe the relationship between the DOM and javascript
    - you can access and manipulate things in the dom using javascript.  

