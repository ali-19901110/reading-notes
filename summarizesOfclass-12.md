# HTML Canvas
> The `<canvas>` element has only two attributes, width and height. These are both optional 
> The `<canvas>` element is only a container for graphics. You must use JavaScript to actually draw the graphics
>  When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.The element can be sized arbitrarily by CSS.
> The `<canvas>` element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas.

Example:
```
<canvas id="tutorial" width="150" height="150"></canvas>
```
*Note: If your renderings seem distorted, try specifying your width and height attributes explicitly in the <canvas> attributes, and not using CSS.*

![](https://developer.apple.com/library/archive/documentation/AudioVideo/Conceptual/HTML-canvas-guide/art/splash.jpg)

> Browsers that do support <canvas> will ignore the content inside the container, and just render the canvas normally

Example:
```
<canvas id="stockGraph" width="150" height="150">
  current stock price: $3.15 + 0.15
</canvas>

<canvas id="clock" width="150" height="150">
  <img src="images/clock.png" width="150" height="150" alt=""/>
</canvas>
```


### A skeleton template
Example:
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8"/>
    <title>Canvas tutorial</title>
    <script type="text/javascript">
      function draw() {
        var canvas = document.getElementById('tutorial');
        if (canvas.getContext) {
          var ctx = canvas.getContext('2d');
        }
      }
    </script>
    <style type="text/css">
      canvas { border: 1px solid black; }
    </style>
  </head>
  <body onload="draw();">
    <canvas id="tutorial" width="150" height="150"></canvas>
  </body>
</html>
```
> The script includes a function called draw(), which is executed once the page finishes loading; this is done by listening for the load event on the document.
This function, or one like it, could also be called using window.setTimeout(), window.setInterval(), or any other event handler, as long as the page has been loaded first.


### Drawing shapes with canvas
> Before we can start drawing, Our HTML skeleton had a canvas element 150 pixels wide and 150 pixels high.

![](https://lh3.googleusercontent.com/proxy/lViuzrC9LaZMvTJkBIyKSr8r9bF3AgEo5gw4Cyi6-FG2beozVCQJo_nTnvZomLAiFhsBJHLWoCdfmnseogXbXEYsTELAqFvfNz8ly7HTTLGYxq2nesGmZEJ5JcOBWj5Aa8pDFfpGQUGveZPJct9HP4Gv6rJYb3cnxPYA-3XBzOdZ5twUflnSIKrMHACPkghIlJ923QQumjEHLXU)

 Drawing rectangles
First let's look at the rectangle. There are three functions that draw rectangles on the canvas:
- `fillRect(x, y, width, height)` Draws a filled rectangle.
- `strokeRect(x, y, width, height)` Draws a rectangular outline.
- `clearRect(x, y, width, height)` Clears the specified rectangular area, making it fully transparent

Example :
```
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.fillRect(25, 25, 100, 100);
    ctx.clearRect(45, 45, 60, 60);
    ctx.strokeRect(50, 50, 50, 50);
  }
}
```
There is a lot of function to use it to draw anything we want for example:
1. beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
2. Path methods
Methods to set different paths for objects.
3. closePath()
Adds a straight line to the path, going to the start of the current sub-path.
4. stroke()
Draws the shape by stroking its outline.
5. fill()
Draws a solid shape by filling the path's content area.

> Cubic Bezier curves
This example draws a heart using cubic Bézier curves
```
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    // Cubic curves example
    ctx.beginPath();
    ctx.moveTo(75, 40);
    ctx.bezierCurveTo(75, 37, 70, 25, 50, 25);
    ctx.bezierCurveTo(20, 25, 20, 62.5, 20, 62.5);
    ctx.bezierCurveTo(20, 80, 40, 102, 75, 120);
    ctx.bezierCurveTo(110, 102, 130, 80, 130, 62.5);
    ctx.bezierCurveTo(130, 62.5, 130, 25, 100, 25);
    ctx.bezierCurveTo(85, 25, 75, 37, 75, 40);
    ctx.fill();
  }
}
```

![](https://i.stack.imgur.com/At7W8.png)
