## Day 3 notes

### When shoud you use an unordered list in your html document?
    - whenever you have of a group of items that dont need to be in a particular order

### How do you change the bullet style of unordered list items?
    - alter the list-style property 

### When should you use an ordered list vs an unordered list in your html document?
    - When your items need to be in a specific order or you want to emphasize the importance of the order


### Describe two ways you can change the numbers on list items provided by an ordered list?
    you can change it to roman numerals by changing the type attribute to "i"
    You can also change the start attribute to a number other than 1


### Describe the CSS properties of margin and padding as characters in a story.  What is their role in a story titled: The Box Model?
    Margin is the security guard outside the element.  It decides how close or far other elements can be.  Padding is the person in the story that controls how close people can get to the inner boundary

### List and describe the four parts of an html element box as referred to by the box model

    margin - the outermost layer wrapping the content. 
    padding - sits around the content as white space
    border - wraps the content and any padding
    content - the area where your content is displayed

    source: https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model

### What data types can you store inside of an array?
    all data types

### Is the people array a valid js array? if so, how can i access the values stored? If not, why?

    const people = [
            ['pete', 32, 'librarian', null], 
            ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]
        ];
    yes it is valid.  You can access them individually by index or you can loop through them and access them at their index

### List five shorthand operators for assignment in javascript and describe what they do
    1. =    this is just assigning a variable to a vallue
    2. +=   this is adding directly to variable instead of reassigning and adding to it
    3. -=   this is doing the same as above but subtracting instead
    4. %=   this assigns the remainder 
    5. /=   this is the same as above but with division

### Read the code below and evaluate the last expression and explain what the the result would be and why

        let a = 10;
        let b = 'dog';
        let c = false;

        // evaluate this
        (a + c) + b;

        it will output 10dog

### Describe a real world example of when a conditional statement should be used in a js program
    - if you want to double a number in an array, but only if you want to double even numbers

### Give an example of when a loop is useful in javascript
    - When you need to perform an operation to an array.  for example, if you want to add a 1 to every number in array