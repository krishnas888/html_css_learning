-> The Css Box Model is a series of positioning properties designed to help with layout.

->Each property works in a different way, and positions the item with different spacing.

->The Box model is the most commonly used way to position items.

-> Each layer represents a different part of the model.

->Each layer can be streched and sized either symmetrically or asymmetrically.

![alt text](image.png)

 we have in image Content wrap by Padding ->border->Margin

 Padding:
 Padding represents the space between the conteent and the border.

 Border:
 -> the border is the divider between the padding and margin.

 -> It can be styled using a CSS property called border.

 Margin:
 The Margin is the space between the border and all the other content.

-> So padding is the internal space and Margin is the external space.


content size and shape

-> best way to use size for height need to use px and width use relative data like vw

.image-body{
    height:400px;
    width: 70vw;
}

Border Styles

maily border gave size,style,color

{
    border: size style color
}
here spacing between the is separtion no need of comas(,)

Solid Border
{
    border: 1px solid green;
}

Dotted Border
{
    border: 1px dotted red;
}

Dashed Border
{
   border: 1px dashed blue; 
}

Double Border
{
    border: 4px double black;
}

Groove Border
{
    border: 2px groove gray;
}

Ridge Border
{
   border: 2px ridge brown; 
}

Inset Border
{
    border: 2px inset purple;
}

Outset Border
{
    border: 2px outset orange;
}

None Border
{
    border: none;
}

Hidden Border
{
    border: hidden;
}


Float and Display types

inline and block elimints

Float:

The float property is used to position an element to the left or right of its container, allowing text and inline elements to wrap around it. Floats are commonly used for layout purposes but can lead to layout issues if not used carefully.

1. left

.float-left {
  float: left;
}

2. right
.float-right {
  float: right;
}

3. none
The element does not float, and it will be displayed in the normal flow of the document.

.float-none {
  float: none;
}

4. inherit
The element inherits the float value from its parent.

.float-inherit {
  float: inherit;
}

note:
clear: both; — Clears both left and right floats.
clear: left; — Clears left floats.
clear: right; — Clears right floats.
clear: none; — No clearing (default).

Display:

The display property controls the display behavior of an element, such as block, inline, or none. It affects how elements are rendered and interact with other elements on the page.

1. block
The element is displayed as a block-level element, taking up the full width available, with a line break before and after it.

.block-element {
  display: block;
}

2. inline
The element is displayed as an inline element, only taking up as much width as necessary, and does not break the line.

.inline-element {
  display: inline;
}

3. inline-block
 The element is displayed as an inline-level block container, allowing for width and height to be set but still appearing inline with other elements.

 .inline-block-element {
  display: inline-block;
}

4. none
The element is not displayed and does not take up any space in the layout.

.hidden-element {
  display: none;
}

5. flex

The element becomes a flex container, enabling the use of Flexbox layout properties.

.flex-container {
  display: flex;
}

6. grid
The element becomes a grid container, allowing the use of CSS Grid layout properties.

.grid-container {
  display: grid;
}

grid-template-columns: repeat(3, 2fr);
gap: 10px; /* Optional: space between columns */

grid-template-columns: This property specifies the size of the columns in a grid container.

repeat(3, 2fr):

A. repeat(): This function allows you to repeat a specific pattern for a given number of columns. It helps to avoid redundancy when you want multiple columns of the same size.

B. 3: This number indicates how many times the column pattern (in this case, 2fr) should be repeated.

C. 2fr: This specifies that each column should take up 2 fractions of the available space.
 and also we can deifine un even space like this grid-template-columns: 1fr 3fr 1fr;

for row we can specify row insted of column
 grid-template-rows: 1fr 2fr 1fr;

 
7. list-item
The element is displayed as a list item, usually used within <ul> or <ol> elements.

.list-item {
  display: list-item;
}

8. table
The element is displayed as a table element (like <table>), allowing for table-specific layout properties.

.table-element {
  display: table;
}

9. table-row
The element is displayed as a table row (like <tr>).
.table-row {
  display: table-row;
}

10. table-cell
he element is displayed as a table cell (like <td>).
.table-cell {
  display: table-cell;
}










