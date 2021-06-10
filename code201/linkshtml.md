#HTML Links, JS Functions, and Intro to CSS Layout

## HTML Chapter 4: Ch.4 “Links” (pp.74-93)
Webistes on the internet are navigating through the use of links. A link is created by using the `<a>` tag. An example of a link is the following:

> `<a href="thisisalink.com">Link</a>`

Within a website there are many internal links that can be created. These will all use the relative path of the HTML page as the link. An example of an internal link is the following:

> `<a href="myfolder/hobbies.html">Hobbies</a>`


## HTML Chapter 15: “Layout” (pp.358-404)
CSS has the following positioning schemes that allow you to control the layout of the page (Duckett 363):

* Normal Flow
* Relative Positioning
* Absolute Positioning
* Fixed Positioning
* Floating Elements

In **normal flow** each HTML element appears on its own new line; this causes each element to appear further down the page than the previous one. This is the default way that HTML appears.

In **relative positioning** an element is shifted from where it would be normally be placed. This does not affect the position of the other elements.

In **absolute positioning** the element is positioned in relation to its containing element. It is taken out of normal flow, which means that it no longer affects the position of the other elements; thus elements will appear under it. These elements move as the user scrolls on the webpage.

In **fixed positioning** the elements are positioned in relation to the browser window. They do not affect the position of the other elements and do not move when the user scrolls on the webpage.

A **floating element** take the element out of the normal flow and place it to the far left or right of a containing box. Other content will flow around it.

## Javascript Chapter 3: “Functions, Methods, and Objects” (pp.86-99)

A function is a group of statements that are grouped together and meant to execute a specific task. It allows code to be more by dry by reducing the amount of times a code block is written out. If a programmer needs to use the function multiple times it is possible to just call the function instead of writing new code.

A function declaration must consist of the function keyword and the following three things:

* The name of the function
* Parameters, enclosed in parentheses
* Javascript statements that define the function, enclosed in curly braces

> `function square(number) {return number * number;}`
- source W3 Schools

In the function example above the name of the function is `square`, the parameter is `number` and the Javascript statement is `{return number * number;}`.

To call the above function one would type the following:

> `square(5)`

This would execute the function and send the number 5 to be processed by it. After processing the function would then return the value 25.

## Pair Programming