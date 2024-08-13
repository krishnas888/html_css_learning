 what is a selector?

    Selector are ways of grabbing and manipulating HTML.

    there are many different ways to select, however they all  turn out the same way.

    Different selectors have different applications.

 The Elemnt Selector:

    you can select entire elements without any special characters.

    This applies to all of the elemnts with that tag on the page.

    It ranks on the bottom of the specificity scale.

    ex:
    <h1> we can use </h1>
    <p> css base on </p>
    <h1> tags</h1>

    based on usin in style sheet
    h1{
        color:red; --> it chnage font default color black to red
    }

The class Selector

    this is used to select elements with a certain class name.

    Can be used on any and all elements with that class.

    Can be used multiple times, and is select with the ".symbol.

    We can also use this class for specific cases which specific content or table like that.

    ex:
    <h2 class="hclass"> this hclass is </h2>
    <p class="pclass"> to design in css</p>

    css class:
    .hclass{
        color:red
    } 
    .p{
        color:blue
    }

The ID Selector:

    this is used to select elements with a certain ID name.

    Can be used on any and all elements with that ID

    Unlike classes, it can only be used on one element at a time, and is selected with the # symbole. However, it is possible to use more than onec

    ex:
    <p id="p-id-selector> this is is </p>
    <p id="p-id-selector> reference to create style </p>

    css class:
    #p-id-selector{
        color:red;
    }