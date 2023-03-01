Implementing controlled components will be useful and give us more control over our data.  I think ternary operators are cool but they definitely cut down on the readability of the code

### What is a ‘Controlled Component’?
    - is a component in which the data is controlled by the component's state.

### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
    - we should store it as they enter data because we may want to display it in another tag or component or we may to clear it  or change it from a different event handler

### How do we target what the user is entering if we have an event handler on an input field?
    - using event.target and if we gave the input a name, event.target.name

### Why would we use a ternary operator?
    - to turn multiple lines of code into 1 line of code

### Rewrite the following statement using a ternary statement:
if(x===y){
  console.log(true);
} else {
  console.log(false);
}

x === y ? console.log(true) : console.log(false)

