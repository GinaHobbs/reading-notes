# HTML Lists, Control Flow with JS, and the CSS Box Model

## HTML Chapter 3: Lists (pp.62-73)
HTML provides three different types of lists:

* **Ordered lists**, where each item in the list is numbered
* **Unordered lists**, where each item begins with a bullet point
* **Definition lists**, which are made up of a set of terms and their definitions.

For an ordered list the `<ol>` tag is used and for an unordered list the `<ul>` tag is used. For these types of lists each list item is inserted using an `<li>` tag.

For a definition list the `<dl>` tag is used. Each term being defined is added with the `<dt>` tag and the definition is added with the `<dd>` tag.

To create a nested list one can simply insert an `<li>` tag into another `<li>` tag.


## HTML Chapter 13: Boxes (pp.300-329)
Every HTML element has its own box which can be manipulated with CSS. Using CSS it is possible to control many properties of the box, such as padding, margin size, borders and visibility. Controlling these values is important when desiging webpages that look good across a variety of devices.

## Javascript Chapter 4: “Decisions and Loops” (pp.162-182)
To make a decision in Javascript an `if...else` statement is used. If the statement evaluates to true then the first code block is executed; if it evaluates to false then the second code block is executed. An `if...else` statement looks like the following:

>`if (userAge >= 18) {console.log('You are an adult!)} else {console.log('You are a minor.)}`

A **switch statement** is similiar to an `if...else` statement, but instead of evaluating a statement it evaluates a variable and makes a decision based on it. The following is an example of a switch statement:

>`switch(rating) {case 1: console.log('You give the venue 1 star);break; case 5: console.log('You give the venue 5 stars'); break; default: console.log('No rating was given');}`

A loop is a way for Javascript to repeat a code block. There are three types of loops in Javascript:

* **for** loops
* **while** loops
* **do...while** loops

A **for** loop is best used when one knows how many times a code block should be run; it is especially good for looping through an array. A **while** loops is best used when one does not how many times a code block should be run; it is especially good for validating data. A **do...while** loop is similiar to the while loop, but unlike the while loop it will always run the code block at least once.
