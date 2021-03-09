# Forms

## Why Forms?
In HTML , forms are used in Web pages to make the pages structural and also it changes the look of those pages. Even, 
they add a new excellent outlook to the normal web pages.
Forms can resemble paper or database forms because web users fill out the forms using check boxes, 
radio buttons, or text fields.

The HTML <form> element defines a form that is used to collect user input:

<form>

.

form elements

.

</form>

An HTML form contains form elements.

Form elements are different types of input elements, like text fields, check boxes, radio buttons, 
submit buttons, and more.

## Form Controls
There are several types of form controls that 
you can use to collect information from visitors 
to your site.
1. ADDING TEXT: like Text input 
2. Making Choices: like Radio buttons
3. Submitting Forms: like Submit buttons

## Form Structure
Form controls live inside a <form> element. This element 
should always carry the action attribute and will usually have a 
method and id attribute too.
# action # method

## Text input
The <input> element is used to create several different form 
controls. The value of the type attribute determines what kind 
of input they will be creating.
ex: <input type="text" name="username" />

## Password Input
When the type attribute has a value of password it creates 
a text box that acts just like a single-line text input, except 
the characters are blocked out. They are hidden in this way so 
that if someone is looking over the user's shoulder, they cannot 
see sensitive data such as passwords.
some examples of format inputs

- < textarea name="comments" cols="20" rows="4">Enter 
 your comments...</textarea>
- radio Button
<input type="radio" name="genre" value="rock" 
 checked="checked" />
-Checkbox
<input type="checkbox" name="service" 
 value="itunes" checked="checked" />
- Drop Down List Box 
<select name="devices">
 <option value="ipod">iPod</option>
 <option value="radio">Radio</option>
 <option value="computer">Computer</option>
 </select>
- Submit button
<input type="submit" name="submit"/>
- hidden content
<input type="hidden" name="bookmark" 
 value="lyrics" />

# Lists, Tables and Forms 
## list-style-type
It can be used on rules that 
apply to the <ol>, <ul>, and <li>
elements.
two types of list
1. Unordered Lists
For an ordered (unnumbered) list

2. Ordered Lists
For an ordered (numbered) list

### list-style
As with several of the other CSS properties, there is a property 
that acts as a shorthand for list styles. It is called list-style, 
and it allows you to express the markers' style, image and 
position properties in any order.

# <table>: The Table element
The HTML <table> element represents tabular data — that is, information presented in 
a two-dimensional table comprised of rows and columns of cells containing data.

## table Properties
You have already met several properties that are commonly 
used with tables. Here we will put them together in a single .

#  EVENT
What is an Event ?
JavaScript's interaction with HTML is handled through events that occur when 
the user or the browser manipulates a page.

When the page loads, it is called an event. When the user clicks a button,
 that click too is an event. Other examples include events like pressing any key,
 closing a window, resizing a window, etc.

Developers can use these events to execute JavaScript coded responses, 
which cause buttons to close windows, messages to be displayed to users, 
data to be validated, and virtually any other type of response imaginable.

Events are a part of the Document Object Model (DOM) Level 3 and every HTML
 element contains a set of events which can trigger JavaScript Code.

Please go through this small tutorial for a better understanding HTML Event Reference.
 Here we will see a few examples to understand a relation between Event and JavaScript −

onclick Event Type
This is the most frequently used event type which occurs when a user clicks
 the left button of his mouse. You can put your validation, warning etc., against this event type.

Example
<html>
   <head>   
      <script type = "text/javascript">
         <!--
            function sayHello() {
               alert("Hello World")
            }
         //-->
      </script>      
   </head>
   
   <body>
      <p>Click the following button and see result</p>      
      <form>
         <input type = "button" onclick = "sayHello()" value = "Say Hello" />
      </form>      
   </body>
</html>

## HOW EVENTS TRIGGER JAVASCRIPT CODE
When the user interacts with the HTML on a web page, there are three 
steps involved in getting it to trigger some JavaScript code. 
Together these steps are known as event handling. 
1. Select t he element node(s) you want the 
script to respond to. 
2. Indicate which event on the selected node(s) will 
trigger the response.
3. State the code you want to run when the event occurs. 

## EVENT LISTENERS 
Event listeners are a more recent approach to handling events. 
They can deal with more than one function at a time 
but they are not supported in older browsers. 
format : element .addEventlistener('event', functionName [, Boolean]) ; 
## THE EVENT OBJECT 
When an event occurs, the event object tells 
you information about the event, and the 
element it happened upon. 
## FORM EVENTS 
There are two events that are commonly used with forms. 
In particular you are likely to see submit used in form validation. 

## MUTATION EVENTS & OBSERVERS
The MutationObserver interface provides the ability to watch for changes being made to the DOM tree.
 It is designed as a replacement for the older Mutation Events feature, 
which was part of the DOM3 Events specification.
MutationObserver
The MutationObserver interface provides the ability to watch for changes 
being made to the DOM tree. It is designed as a replacement for the older
 Mutation Events feature, which was part of the DOM3 Events specification.