# CSS Transforms, Transitions, and Animations

## Transforms 
> It is a property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements.

- Transform Syntax
> syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount 
inside parentheses

Example:
```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```

1. 2D Transforms:
> Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes

Look at this pictures how will are changing  by values of transforms
![](https://res.cloudinary.com/dno0vkynk/image/upload/v1475392871/CSS3Transforms2D.png)

#### Combining Transforms
> multiple transforms can be combined together. To combine transforms

Example:
```
HTML
<figure class="box-1">Box 1</figure>
<figure class="box-2">Box 2</figure>
```
```
CSS
.box-1 {
  transform: rotate(25deg) scale(.75);
}
.box-2 {
  transform: skew(10deg, 20deg) translateX(20px);
}
```

#### Transform Origin
> The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are
  specified, the first is used for the horizontal axis and the second is used for the vertical axis.
  
  2. 3D Transforms
  > Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.
  3D transforms have the same properties of 2D transforms but different affect on z-axis
  
  Look at this pictures how will are changing by values of transforms especially on x-axis 
  ![](https://st.quantrimang.com/photos/image/2019/05/07/3d-transform-css-2.jpg)
  
  ## Transitions & Animations
  > transitions allows you to change property values smoothly, over a given duration.
  
  To create a transition effect, you must specify two things:
  - the CSS property you want to add an effect to
  - the duration of the effect
  
  In the example below the box will change its background color over the course of 1 second in a linear fashion
  Example :
  ```
  .box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}
```

- Transitional Property
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties
within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any
transitions

![](https://www.educative.io/api/edpresso/shot/5230996540620800/image/5980796563226624)

> **Animations**
- An animation lets an element gradually change from one style to another.
- You can change as many CSS properties you want, as many times you want.
- To use CSS animation, you must first specify some keyframes for the animation.

> Animations Keyframes :
 Keyframes hold what styles the element will have at certain times
 
 To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints,
 and the properties intended to be animated.
 ```
 @keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
```

![](https://stuyhsdesign.files.wordpress.com/2017/03/animation-properties.png)

Animation Name :

```
.stage:hover .ball {
  animation-name: slide;
}
```
Animation Duration, Timing Function, & Delay:
```
.stage:hover .ball {
  animation-name: slide;
  animation-duration: 2s;
}
```









