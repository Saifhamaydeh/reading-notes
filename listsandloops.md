# lists 
## Definition : a number of connected items or names written in
html page consecutively, typically one below the other.
there is two type of list:
1. Ordered lists : each item in the list is numbered 1. 2. 3. ...
using to do it <ol> tage inside it <li>

2. unOrdered lists : are lists that begin with a bullet point for each item
using to do it <ul> tage inside it <li>

The definition list is created with the <dl> element and usually
consists of a series of terms and their definitions.
inside <dl> we put <dt> like a title(term) for all <dd> definition

Nested List
thats mean put list inside another list
ex :<ul>
<li>a</li>
<li>b
 <ul>
 <li>b1</li>
 <li>b2</li>
 <li>b3</li>
 </ul>
</li>
<li>c</li>
</ul>

# Boxes
## a box is sized just big enough to hold its contents.
the do this we determen the height and width 
ex : div.box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}
maybe we cam Limiting width by using min-width, max-width
and we can Limiting hight by using min-height, max-height
These are very helpful properties to ensure that the content of
pages are legible

why we using Overflowing Content 
The overflow property tells the
browser what to do if the contentcontained within a box is larger
than the box itself. It can have one of two values:
1. hidden using it to hide the scroll  
2. scroll using it to adds a scrollbar to the box 

## Border, Margin , Padding
Every box has a border The border separates the edge of one boxfrom another.
Margins sit outside the edge of the border
Padding is the space between the border of a box and any content contained within it.

Border Style
You can control the style of a border using the border-style property
using keywords : solid , dotted , dashed , groove .....

 Shorthand border
we can do all proparites in same sentances
ex : p {border: 3px dotted red;}

# Basic JavaScript Instructions of arrys
An array is a special type of variable. it stores a list of values. 
ex :var colors;
colors =['white', 'black', ' custom'];

VALU ES IN ARRAYS
Values in an array are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one). 
INDEX VALUE
o 'white '
1 'black'
2 'blue' 

IF ... ELSE STATEMENTS
two answer of if statment maybe true or false
if the answer was true the first block will excuded 
if the answer was false the secand block will excuded
ex : var pass = 50;
var score = 75;
if (score >= pass) { console.log('passed'); }
else{console.log('Have another chance');}

SWITCH STATEMENTS
A switch statement starts with a variable called the switch value.
Each case indicates a possible value for this variable and the
code that should run if the variable matches that value.

## loops
The purpose of loops is to repeat the same, or similar, code a number of times. 
This number of times could be specified to a certain number, 
or the number of times could be dictated by a certain condition being met
# why we need to loops
replace of write the code more times 
we do the loop to repeat the code

types of loops
1. for loop
2. WHILE LOOP
3. do WHILE LOOP
 

# quez
1. the  lists that begin with a bullet point
(rather than characters that indicate order).
1. order list
2. defintion list
3. unorder list
4. Nested List

2.the space between the border of a box and any
content contained within it
1. Border
2. Margin
3. Padding
4. box

3. the numbering of list starts at one (array)
1. true
2. false

4. we using *break ;* in
1.switch
2. if..else
3. array

5. What is the output of the following program fragment?
for ( int j = 0;  j <  5; j++ )
{
  console.log(j)
}

a. 0 1 2 3 4 5
b. 0 1 2 3 4
c. 0 1 2 3 4 5
d. j j j j j
