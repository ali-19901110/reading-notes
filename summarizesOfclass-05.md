# Images
> why you might want to add an image to a web page? you might want to include a logo, photograph,illustration, diagram, or chart.
> A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.
## Adding Images
> Syntax `<img src="url" alt="alternatetext">`

> *The required `src` attribute specifies the path (URL) to the image.*

### Height & Width of Images
> The `width` attribute specifies the width of an image, in pixels.
> `Tip`: Always specify both the height and width attributes for images. If height and width are set, the space required for the image is reserved when the page is loaded.
However, without these attributes, the browser does not know the size of the image, and cannot reserve the appropriate space to it. 
The effect will be that the page layout will change during loading (while the images load).

![](https://static.packt-cdn.com/products/9781786463210/graphics/image_05_006.jpg)
- Use the HTML width and height attributes or the CSS width and height properties to define the size of the image
- Use the CSS float property to let the image float to the left or to the righ

#### Add Responsiveness
 > Optionally, you could add media queries to make the images stack on top of each other instead of floating next to each other, on a specific screen width
 
 #### Image Formats:
 ![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZno6QWsdKpSlj2kppqldVrCG1kB7hGJKUJA&usqp=CAU)
 
 > There are three rules to remember when you are creating images for your website :
 1. Save images in the right format .
 2. Save images at the right size .
 3. Use the correct resolution .
 
 
 # CSS Colors
 > Colors in CSS can be specified by the following methods:
  - Hexadecimal colors
  - Hexadecimal colors with transparency
  - RGB colors
  - RGBA colors
  - HSL colors
  - HSLA colors
  
  ![](https://lh3.googleusercontent.com/proxy/1_lVzQ99hW5XUZOOn-CpIglfyYhKA6fqK76RojHiq4WA0McBSnirh5QoOV08enXrlf9fHJXfMQtvI-Sa4LWIKh8_7JsnuVccfzyAEcMC3RKTcc4ke80v)
  
  
  `background color`  
 ![](https://i.stack.imgur.com/2QaEG.png)
 
- CSS3 has introduced an extra value for RGB colors toindicate opacity. It is known as RGBA.
- CSS3 also allows you to specify colors as HSL values,with an optional opacity value. It is known as HSLA.

# CSS Text
![](https://cdn.educba.com/academy/wp-content/uploads/2019/08/CSS-Text-Formatting-Properties2.png).
> Text Color and Background Color
Example:
`body {
  background-color: lightgrey;
  color: blue;
}

h1 {
  background-color: black;
  color: white;
}`

> Text Alignment
- The text-align property is used to set the horizontal alignment of a text.
- A text can be left or right aligned, centered, or justified.

> Text Decoration
- The text-decoration property is used to set or remove decorations from text.
- The value text-decoration: none; is often used to remove underlines from links.
Example:
`a {
  text-decoration: none;
}`
























