# HTML5 EVENTS
`Events` are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked). 
- DOMContentLoaded :is event fires when the initial HTML document has been completely loaded and parsed, without waiting for stylesheets, images, and subframes to finish loading.
- hashchange :  event is fired when the fragment identifier of the URL has changed 
- beforeun load : event is fired when the window, the document and its resources are about to be unloaded.

![](https://d1dwq032kyr03c.cloudfront.net/upload/images/20171219/20065504och2Xekk7T.png)

### USING HTML5 EVENT
```
function setup() {
var textlnput;
textlnput = document .getElementByld( 'message ');
textlnput.focus(); 
}
window.addEventlistener('DOMContentloaded' , setup, false);
window.addEventlistener('beforeunload', function(event){
return ' You have changes that have not been saved •.• ' ;
}. false); 
```
* The OOMContentloaded event fires before the load event (because the latter waits for all of the page's resources to load). 

## First, you will learn how to select elements using jQuery selectors, and then how to update those elements using the methods and properties of the jQuery object.
```
G) $(' :header').addClass('headline');
@ $(' l i : lt(3) ').hide(). fadeln(lSOO);
$('li').on('click', function() {
$(this) . remove();
} ) ; 
```
1. The first line selects all of the `<hl> - <h6>` headings, and adds a value of headline to their cl ass attributes. 
2. . The second line selects the first three list items and does two things: • The elements are hidden (inorder to allow the next step). • The elements fade into view
3. The last three lines of the script set an event listener on each of the `<l i >`elements. When a user clicks on one, it triggers an anonymous function to remove that element from the page. 

WHY USE JQUERY? 
- jQuery is a lightweight, "write less, do more", JavaScript library.
- The purpose of jQuery is to make it much easier to use JavaScript on your website.



