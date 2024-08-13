Hash-code and rgb

.title{
    color: #a5a5a5
}
.title{
color: rgb(200,148,30);
}

Image background

cover: This scales the background image to cover the entire container while 
preserving its aspect ratio. The image will be clipped to fit the container 
if necessary.

.cover-image{
    background: url("../imagepath");
    background-size: cover;
}

contain: This scales the background image to fit within the container while
 preserving its aspect ratio. The entire image will be visible, but there 
 may be empty space in the container.

.contain-image {
  background-image: url('image.jpg');
  background-size: contain;
}

auto: This is the default value. The background image is displayed at its 
original size.

.auto-image {
  background-image: url('image.jpg');
  background-size: auto;
}

100% 100%: This scales the background image to exactly match the width and 
height of the container. This can distort the image if the aspect ratios 
don't match.

.example {
  background-image: url('image.jpg');
  background-size: 100% 100%;
}

width height: You can also specify exact values for width and height, which 
will scale the image accordingly.

.width-height-image {
  background-image: url('image.jpg');
  background-size: 200px 150px;
}

initial: Sets the property to its default value, which is auto

.initial-image {
  background-image: url('image.jpg');
  background-size: initial;
}

inherit: The property value is inherited from its parent element.
.example {
  background-image: url('image.jpg');
  background-size: inherit;
}

opacity of background
0 to 1, here 0 is light and 1 means dark
body{
    background: rgba(128,128,255,1)
}


Gradient
linear-gradient()
radial-gradient()

background: linear-gradient(direction, color1,color2, ...);

linear-gradient:
    In the linear gradient have 4 directions  top, buttom, let and right. and also we can combile 2 (two) directions to create

{
    background: linear-gradient( to right, rgb(94,255,126), rgba(94,255,122,0)
    );
}

for diagnal speficfy the both sides. using to

{
     background: linear-gradient( to bottom top, rgb(94,255,126), rgba(94,255,122,0)
    );
}
using angles You can use angles to specify the direction of the gradient:

0deg: Gradient starts from the left and goes to the right.

{
background: linear-gradient(90deg, rgb(94, 255, 126), rgba(94, 255, 122, 0));

}

radial-gradient : don't support dirction-size, and also it work as persentage not the direction like linear-gradient

background: radial-gradient(shape size at position, start-color, ..., end-color);

normal
{
    background: radial-gradient( red,blue,green);
}

persentages
{
    background: radial-gradient(red 20%, blue 40%, green 55%);
}
shanpe:
by default we have ellipses we can chnage to circle

{
    background: radial-gradient(circle, red 20%, blue 40%, green 55%);
}

