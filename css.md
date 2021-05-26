# CSS

## What is CSS?

CSS stands for Cascading Style Sheet. It allows one to style HTML web pages to create beautiful look pages that incorporate fonts, colors, borders and even animation. CSS uses rules that essentially tell HTML elements what to look like. An example of CSS is:

> `h1 {color: red; font-size: 5em;}`

The first part of this statement, the `h1` tag, is known as a selector. Inside the curly braces are 3 declartions which consists of property and value pairs. These designate which property one wants to change and gives a value for it.

A typical CSS Style Sheet will contain numerous rules, each adding rules to different HTML tags.

## How to Use CSS

There are three ways to insert a style sheet:

* External CSS
* Internal CSS
* Inline CSS

### External CSS

An external style sheet allows one to change the look of a website by changing a single file. It is important to reference the external style sheet by using the `<link>` element in the inside the head section of the HTML page. An external style sheet should not contain any HTML tags. The following is an example of how to use an external style sheet:

> `<head> <link rel="stylesheet" href="mystyle.css"> </head>`

