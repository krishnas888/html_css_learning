different types of units, based on desing which one we need to use.

1. absolute units 
2. relative units

3.px is littlebit special.

1. absolute units
cm, mt, inches which are absolute units

centimeter
body{
    font-size:2cm
}
milimeter
body{
    font-size:2mm
}
pt is points it also type different that px little bit greterthan px 
1 pt is approximately 1/72 of an inch.

body{
    font-size:2pt
}
pc is large bigger 1 pc is approximately 12 points.

body{
    font-size:2pc
}


2. relative units
these are a little bit different relative units are usually
relative units are dependent on something.

ex: persentage units are dependent on the parent elements 
if an a image have ing 70% screen the same spacing is view in the mobile web as well. its a responsive design

em is double than every font size
Relative to the font-size of the element. 1em equals the current font-size.

body {
  font-size: 16px; /* base font-size */
}
.text {
  font-size: 2em; /* 32px (2 * 16px) */
}


Percentage (%)
Percentage values are relative to the parent element.
body{
    font-size:20%
}

rem
Relative to the font-size of the root element (<html>). Useful for consistent sizing.

html {
  font-size: 16px; /* base font-size */
}
.text {
  font-size: 2rem; /* 32px (2 * 16px) */
}


3. pixel 
pixel is a little bit different now although it is consider as absolute units, It is actually relatively scale based on what device you're on.

view width and view height.
so in web design and development in general there's this thing called the viewport which is pretty much the dimensions of whatever you're viewing it on.

so in this case our viewport would be the body's width and then the body height so VW and VH view

so one vw or vh is equal to 1 percent of the totalt body width or body height.

vw (Viewport Width)
1vw equals 1% of the viewport's width.
.element {
  width: 50vw; /* 50% of the viewport's width */
}

vh (Viewport Height)
1vh equals 1% of the viewport's height.
.element {
  height: 50vh; /* 50% of the viewport's height */
}

vmin and vmax
vmin is the smaller of vw and vh.
vmax is the larger of vw and vh.
.element {
  font-size: 5vmin; /* 5% of the smaller dimension of the viewport */
}

.element2 {
  font-size: 5vmax; /* 5% of the larger dimension of the viewport */
}

