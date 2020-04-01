# class-03.md

# LISTS
1. list can be ordered < ol>  or < ul> (bullet lists) both have < li> within them.<br>
 < dl> or defined list will have < dt> defintion term followed < dd>which give the defintion info of < dt>.
<br>You can nest list and make sublist. 

# BOXES
1. Box dimenisions - width and height. you will set both with **pixel**, **percentage**, or **EM**. EM is size of text wintin the box. 
<br>
you can limit width with *min-width* and *max-width*, you can limit height with *min-height* and *max-height*. 
<br>
**overflow**- can use property *hidden* and *scroll* with CSS code overflow:hidden and overflow: scroll
<br>
## Border, margin, padding
3 box properties that are important
Can add white space (space between items on the page) or just stack the boxes.
### border: 
*border-width-thin, thick, medium;* as well as border-top-width,border-right-width,border-bottom-width, border-left-width.
<br> <br>
border-style- can be solid, dotted, dashed, double, groove, ridge, insert, outset, hidden (no borders shown)
<br><br>
border-color- can create colors or for all or 1 side of box.

### Padding
adjusts your padding to border

### Margin
can be used to offset boxes

### Display
inline, block, inline block, none (hides and element from page)

### visibilty
-use hidden or visibile

# Javascript
example 
cost msg; //message
<br>
const level; //level
 
switch(level) {
    case 1: 
        msg = 'good job this time';
        break;    
    case 2:
        msg = 'let's try harder';
        break;
    default
        msg = 'good job'
        break;
}



kinda like a if else statement.
if...else -no else needed, all checks are done regardless if matched on first try
switch -default option, if match found it will end statment