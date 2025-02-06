### ***Image Maps***

- The HTML <map> tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more <area> tags.

- Try to click on the computer, phone, or the cup of coffee in the image below

- The image is inserted using the <img> tag. The only difference from other images is that you must add a usemap attribute.

**Create Image Map**
- Then, add a <map> element.

- The <map> element is used to create an image map, and is linked to the image by using the required name attribute
`<map name="workmap">`
- The name attribute must have the same value as the <img>'s usemap attribute .

**The Areas**
- Then, add the clickable areas.A clickable area is defined using an <area> element.

**Shape**

You must define the shape of the clickable area, and you can choose one of these values:
- rect - defines a rectangular region
- circle - defines a circular region
- poly - defines a polygonal region
- default - defines the entire region

You must also define some coordinates to be able to place the clickable area onto the image. 

```Shape="rect"
The coordinates for shape="rect" come in pairs, one for the x-axis and one for the y-axis.

So, the coordinates 34,44 is located 34 pixels from the left margin and 44 pixels from the top
![workspace top](assets\workplace1.jpg)
The coordinates 270,350 is located 270 pixels from the left margin and 350 pixels from the top:
![workspace left](assets\workplace1.jpg)


