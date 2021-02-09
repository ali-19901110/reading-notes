# Definition Lists
> The `<dl>` tag defines a description list.

> The `<dl>` tag is used in conjunction with `<dt>` (defines terms/names) and `<dd>` (describes each term/name)

## Nested lists
> A nested list or a sublist is a list within a list.
  The trick to marking nested lists up correctly in HTML is to recognize that the sublist is actually a child of a list item and not of a list
  
  ![](http://tutzi.com/wp-content/uploads/2013/07/nested-list.jpg)
  
  ### linkes 
  > are found in nearly all web pages. Links allow users to click their way from page to page.
  
  > Links - Syntax  `<a href="url">link text</a>`  
 
 > This example shows how to create a link to Google.com:`<a href="https://www.google.com/">`Visit Google!`</a>`
 
 #### Directory Structure
   > On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a
     website are sometimes referred to as directories.
     
 # Layout
 - Controlling the position of elements
 - Creating site layouts
 - Designing for different sized screens
## The `position`
> property specifies the type of positioning method used for an element (static, relative, fixed, absolute or sticky)
![](https://www.hostmystory.com/uploads/larg/5dfb4e547b331CSS_layout_porperty.jpg)

### Floating Elements.
> The `float property` is used for positioning and formatting content e.g. let an image float left to the text in a container.
> The `clear property` specifies what elements can float beside the cleared element and on which side.

The float property can have one of the following values:
1. left - The element floats to the left of its container
2. right - The element floats to the right of its container
3. none - The element does not float (will be displayed just where it occurs in the text). This is default
4. inherit - The element inherits the float value of its parent

![](https://codebridgeplus.com/wp-content/uploads/float.png)

#### Screen Sizes
> Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most
operating systems allow users to adjust the resolution of their screens.

#### Fixed Width Layouts
> Fixed width layout
designs do not change size as the user increases or decreases the size of their browser window. Measurements tend to be given in pixels.
##### Layout Grids
> The Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning
> Example Grid
![](https://blogs.igalia.com/mrego/files/2016/02/example-grid-areas.svg)

# Function
> A function is a block of code designed to perform a particular task.
> A function is executed when "something" invokes it (calls it).
- Why Functions?
1. You can reuse code: Define the code once, and use it many times.
2. You can use the same code many times with different arguments, to produce different results

### Function Syntax
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
![](https://www.bookofnetwork.com/images/javascript-images/JS_Function---example-02_04Oct16_1344.png)
