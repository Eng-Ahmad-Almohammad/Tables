# Tables
## Basic Table Structure
* < table >: The < table > element is used to create a table. The contents of the table are written out row by row. 

* < tr >: You indicate the start of each row using the opening < tr > tag. (The tr stands for table row.) 

* < td >: Each cell of a table is represented using a  td > element. (The td stands for table data.)
## Table heading
## < th >
### The < th > element is used just like the < td > element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.) 
## Spanning ColumnS
### The colspan attribute can be used on a < th > or < td > element and indicates how many columns that cell should run across.
![Table](https://user-images.githubusercontent.com/70091044/93024905-71553b00-f602-11ea-83bc-cc03dc299885.PNG)
## Spanning rows 
### The rowspan attribute can be used on a < th > or < td > element to indicate how many rows a cell should span down the table.

## Long tables
### There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content). These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table (as you will see when you learn about CSS).

* < thead >: The headings of the table should sit inside the <thead> element. 
* < tbody >: The body should sit inside the < tbody > element. 
* < tfoot >: The footer belongs inside the < tfoot > element.
