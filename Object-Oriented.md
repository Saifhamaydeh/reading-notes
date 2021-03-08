# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. 
A model describes the various entities, their attributes and behaviors, as well as 
the constraints that govern the problem domain. An entity that stores data in properties 
and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific
problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within
 and between both technical and business teams.

# What's a Table?
A table represents information in a grid format. 
Examples of tables include financial reports, TV 
schedules, and sports results

## Basic Table Structure
<table>
The <table> element is used 
to create a table. The contents 
of the table are written out row 
by row.
<tr>
You indicate the start of each 
row using the opening <tr> tag. 
(The tr stands for table row.) 
It is followed by one or more 
<td> elements (one for each cell 
in that row). 
At the end of the row you use a 
closing </tr> tag.
<td>
Each cell of a table is 
represented using a <td>
element. (The td stands for 
table data.)
At the end of each cell you use a 
closing </td> tag.
## Long Tables
These elements help people 
who use screen readers and also 
allow you to style these sections 
in a different manner than the 
rest of the table (as you will see 
when you learn about CSS).
<thead>
The headings of the table should 
sit inside the <thead> element. 
<tbody>
The body should sit inside the 
<tbody> element. 
<tfoot>
The footer belongs inside the 
<tfoot> element.

# WHAT IS AN OBJECT?
Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. 

## WAYS TO CREATE OBJECTS 
1. LITERAL NOTATION 
ex:var hotel = {} 
hotel .name= 'Quay'; 
hotel .rooms = 40; 
hotel.booked = 25; 
hotel.checkAvailabil ity =function() 
return this.rooms - this .booked; 
} ;
2. OBJECT CONSTRUCTOR NOTATION 
ex:var hotel = new Object(); 
hotel.name = 'Quay'; 
hotel .rooms = 40; 
hotel . booked= 25; 
hotel.checkAvailability =function() 
return this .rooms - this.booked; 
} ; 

### THIS (IT IS A KEYWORD) 
The keyword this is commonly used inside functions and objects. 
Where the function is declared alters what this means. It always refers 
to one object, usually the object in which the function operates. 
### RECAP: STORING DATA 
In JavaScript, data is represented using name/value pairs. 
To organize your data, you can use an array or object to group a set of 
related values. In arrays and objects the name is also known as a key. 
## GLOBAL OBJECTS: STRING OBJECT 
Whenever you have a value that is a string, you can use the properties 
and methods of the String object on that value. This example stores the 
phrase "Home sweet home " in a variable. 

## DATA TYPES REVISITED 
In JavaScript there are six data types: 
Five of them are described as simple (or primitive) data types. 
The sixth is the object (and is referred to as a complex data type). 
### avaScript has five simple 
1. String 
2. Number 
3. Boolean 
4. Undefined
5. Null
JavaScript also defines a complex data type: 
6.0bject 

## GLOBAL OBJECTS: 
MATH OBJECT 
The Math object has properties and methods 
for mathematical constants and functions. 
PROPERTY DESCRIPTION 
Math.PI Returns pi (approximately 3.14159265359) 
Math. round() Rounds number to the nearest integer 
Mat h. sqrt (n) Returns square root of positive number, e.g., Math. sqrt (9) returns 3 