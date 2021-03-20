# Text
Headings
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>
HTML has six "levels" of 
headings:
<h1> is used for main headings
<h2> is used for subheadings If there are further sections 
under the subheadings then the <h3> element is used,

## paragraph <p>
To create a paragraph, surround 
the words that make up the 
paragraph with an opening <p>
tag and closing </p> tag

## White Space
When the browser comes across two or more spaces next to each 
other, it only displays one space. Similarly if it comes across a line 
break, it treats that as a single space too. This is known as 
white space collapsing.

<br />
As you have already seen, the 
browser will automatically show 
each new paragraph or heading 
on a new line. But if you wanted 
to add a line break inside the 
middle of a paragraph you can 
use the line break tag <br />.

## Introducing CSS
### What CSS does
Cascading Style Sheets (CSS) styles HTML elements with greater control 
than just using HTML. CSS can style almost any HTML tag that creates a 
visible element on the page, including all the HTML tags used to create 
headings,paragraphs, links, images, lists, and tables t.

Understanding CSS: 
Thinking Inside the Box
The key to understanding how CSS works is to 
imagine that there is an invisible box around 
every HTML element.

## How CSS works
The browser loads the HTML (e.g. receives it from the network). 
It converts the HTML into a DOM (Document Object Model). ... 
The browser parses the fetched CSS, and sorts the different rules 
by their selector types into different "buckets", 
e.g. element, class, ID, and so on.

## Rules, properties, and values
A CSS rule is a grouping of one or more CSS properties which are to
 be applied to one or more target HTML elements. A CSS rule consists
 of a CSS selector and a set of CSS properties. The CSS selector determines
 what HTML elements to target with the CSS rule.

### CSS Properties Affect How Elements Are Displayed
CSS declarations sit inside curly brackets and each is made up of two 
parts: a property and a value, separated by a colon. You can specify 
several properties in one declaration, each separated by a semi-colon.
CSS Properties Affect 
How Elements Are 
Displayed
h1, h2, h3 {
 font-family: Arial;
 color: yellow;}
color :proparity
yellow :value

# basic java script
## STATEMENTS 
A script is a series of instructions that a computer can follow one-by-one. 
Each individual instruction or step is known as a statement. 
Statements should end with a semicolon. 

## COMMENTS 
You should write comments to explain what your code does. 
They help make your code easier to read and understand. 
This can help you and others who read your code. 

### WHAT IS A VARIABLE? 
A script will have to temporarily 
store the bits of information it 
needs to do its job. It can store this 
data in variables. 

### DATA TYPES 
JavaScript distinguishes between numbers, 
strings, and true or false values known as 
Booleans.

#  Decisions and Loops
Refer to previous lessons for review.
Welcome back to our tutorial, in this lesson, we will be exploring how to 
control the flow of your program using conditional statements and loops. 
Here are the concepts that we will be using:

If statements - If a condition is true, then run the code in that block.
If...Else statements - If a condition is true, then run the code in that block. 
Otherwise, run the code in the else block.
For loops - Run the code in this block based on a set number of iteration.
 This is known.
While loops - Run the code in this block while a condition is true. 
The number of iterations is unknown.

We will also need 6 relational operators for our condition:

(==) - equal to - Compares two items to see if they are equal
(!=) - not equal to - Compares two items to see if they are not equal
(>) - greater than - Compares the first item to see if it is greater than the second item
(<) - less than - Compares the first item to see if it is less than the second item
(>=) - greater than or equal to - Compares the first item to see if it is greater than or equal to the second item
(<=) - less than or equal to - Compares the first item to see if it is less than or equal to the second item