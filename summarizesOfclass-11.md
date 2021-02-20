# Video and Audio
- Controlling size of images in CSS
- Aligning images in CSS
- Adding background images

 ## Images Syntax:
 > The HTML `<img>` tag is used to embed an image in a web page
 > ```<img src="url" alt="alternatetext">```
 
 > The `<img>` tag has two required attributes:
1. src - Specifies the path to the image
2. alt - Specifies an alternate text for the image

## Image Size - Width and Height
> we can use the CSS to specify the width and height of an image.

HTML                                                  
```<img src="images/magnolia-large.jpg"                 
 class="large" alt="Magnolia" />
<img src="images/magnolia-medium.jpg"
 class="medium" alt="Magnolia" />
<img src="images/magnolia-small.jpg"
 class="small" alt="Magnolia" />

CSS
img.large {
width: 500px;
height: 500px;}
img.medium {
width: 250px;
height: 250px;}
img.small {
width: 100px;
height: 100px;}
```
### Aligning images in CSS
> By default, images are inline elements. This means that they flow within the surrounding text.In order to center an image, itshould be turned into a blocklevel element using
the display property with a value of block.

Example :

```img.align-center {
display: block;
margin: 0px auto;}
img.medium {
width: 250px;
height: 250px;}
```
![](https://blog.hubspot.com/hs-fs/hubfs/an%20image%20centered%20horizontally%20with%20the%20CSS%20flex%20property.png?width=800&name=an%20image%20centered%20horizontally%20with%20the%20CSS%20flex%20property.png)

### Background Images
> The background-image property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By
default, a background image will repeat to fill the entire box.
Example:
```body {
background-image: url("images/pattern.gif");}
```

#### Repeating Images:
> background-repeat
The background-repeat property can have four values:
1. `repeat` The background image is repeated both horizontally and vertically (the default way it is shown if the backgroundrepeat property isn't used).
2. `repeat-x` The image is repeated horizontally only (as shown in the first example on the left).
3. `repeat-y` The image is repeated vertically only
4. `no-repeat` The image is only shown once.
Example:
```
body {
background-image: url("images/tulip.gif");
background-repeat: no-repeat;
background-attachment: fixed;}
```

## Video
> HTML5 comes with elements for embedding rich media in documents — <video> and <audio> — which in turn come with their own APIs for controlling playback, seeking, etc.
> The <video> and <audio> elements allow us to embed video and audio into web pages

Example:
```
<video controls>
  <source src="rabbit320.mp4" type="video/mp4">
  <source src="rabbit320.webm" type="video/webm">
  <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
```

# Designing Navigation:
Site navigation not only helps people find where they want to go, but also helps them understand what your site is about and how it is organized.
Good navigation tends to follow these principles
1. `Concise` Ideally, the navigation should be quick and easy to read. It is a good idea to try to limit the number of options in a menu to no more than eight links. These
can link to section homepages which in turn link to other pages
2. `Clear` Users should be able to predict the kind of information that they will find on the page before clicking on the link. Where possible, choose single
descriptive words for each link rather than phrases.
3. `Selective` The primary navigation should only reflect the sections or content of the site. Functions like logins and search, and legal information like terms and
conditions and so on are best placed elsewhere on the page.

![](https://i.stack.imgur.com/j9NzV.png)
