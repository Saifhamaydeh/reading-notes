# Layout
Key Concepts in Positioning Elements
Building Blocks
CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box.

Containing Elements
If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.

## Controlling the Position of Elements
CSS has the following positioning schemes that allow you to control 
the layout of a page: normal flow, relative positioning, and absolute 
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

## normal flow
In normal flow, each block-level element sits on top of the next 
one. Since this is the default way in which browsers treat HTML elements, you do not 
need a CSS property to indicate that elements should appear in normal flow, but the syntax 
would be:position: static; I have not specified a width property for the heading 
element, so you can see how it stretches the width of the entire browser window by default.
The paragraphs are restricted to 450 pixels wide. This shows how the elements in normal flow 
start on a new line even if they do not take up the full width of the browser window.
All of the examples that demonstrate positioning will use a similar HTML structure. 

## position:relative

Relative positioning moves an element in relation to where it would have been in normal flow.
For example, you can move it 10 
pixels lower than it would have 
been in normal flow or 20% to 
the right.

## position:absolute
When the position property 
is given a value of absolute, 
the box is taken out of normal 
flow and no longer affects the 
position of other elements on 
the page. (They act like it is not 
there.) 
The box offset properties (top or bottom and left or right) specify where the element 
should appear in relation to its containing element.
In this example, the heading has been positioned at the top of the 
page and 500 pixels from its left edge. The width of the heading is set to be 250 pixels wide.

## z-index
When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the 
elements that appear later in the HTML code sit on top of those that are earlier in the page. 

### float
The float property allows you to take an element in normal 
flow and place it as far to the left or right of the containing element as possible.
Anything else that sits inside the containing element will 
flow around the element that is floated.
### Clearing float
The clear property allows you to say that no element (within the same containing element) 
should touch the left or righthand sides of a box. It can take 
the following values:
1. right
2. left
3. none
4. both

## Creating Multi-Column Layouts with Floats
Many web pages use multiple columns in their design. This 
is achieved by using a <div> element to represent each 
column. The following three CSS properties  are used to
 position the columns next to each other:
width
This sets the width of the 
columns.
float
This positions the columns next 
to each other.
margin
This creates a gap between the 
columns.

## screen Sizes
Different visitors to your site will have different sized screens that show 
different amounts of information, so your design needs to be able to 
work on a range of different sized screens.

## Screen Resolution
Resolution refers to the number of dots a screen shows per inch. Some 
devices have a higher resolution than desktop computers and most 
operating systems allow users to adjust the resolution of their screens.

## Page Sizes
Because screen sizes and display resolutions vary so much, web 
designers often try to create pages of around 960-1000 pixels wide 
(since most users will be able to see designs this wide on their screens).

### Fixed Width Layouts
Fixed width layout designs do not change size as the 
user increases or decreases the size of their browser window. 
Measurements tend to be given in pixels.
Advantages
● Pixel values are accurate 
at controlling size and 
positioning of elements.
Advantages
● Pixel values are accurate 
at controlling size and 
positioning of elements.

## Liquid Layouts
Liquid layout designs stretch and contract as the user increases 
or decreases the size of their browser window. They tend to use percentages
The liquid layout uses 
percentages to specify the width of each box so that the design 
will stretch to fit the size of the screen.

## Layout Grids
Composition in any visual art (such as design, painting, or photography) 
is the placement or arrangement of visual elements — how they are 
organized on a page. Many designers use a grid structure to help them 
position items on a page, and the same is true for web designers.