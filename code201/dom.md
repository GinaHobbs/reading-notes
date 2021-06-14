# Problem Domain, Objects, and the DOM

## Understanding the problem domain

The problem domain refers to the "big picture" idea of what one is trying to code. It is often the most difficult part of programming because it entails breaking an often inscrutable problem down into manageable pieces. Without fully understaning the problem domain it will be impossible to write the code because the feature isn't fully hashed out and understoof yet; it's like writing code before one understants the full scope of the problem.

## Javascript Chapter 3: “Object Literals” (pp.100-105)

Objects are groups of **variables** and **functions**, howver in an object these two things take on new names. Variables become known as **properties** and functions become known as **methods**. Properties and methods have a name and a valuel in an object that name is called a **key**. Each key name must be different because keys are used to access their corresponding values. 

## Javascript Chapter 5: “Document Object Model” (pp.183-242)

The browser represents the page using a DOM tree (Duckett 242). DOM trees have 4 types of nodes:

* document nodes
* element nodes
* attribute nodes
* text nodes

Element nodes can be selected by their **id** or **class** attributes, by **tag name** or by using CSS selector syntax (Duckett 242). From an element node you can access and update its content using properties such as **textContent** and **innterHTML** or using DOM manipulation techniques (Duckett 242). An element node can contain multiple text nodes and child elements that are siblings of each other (Duckett 242).