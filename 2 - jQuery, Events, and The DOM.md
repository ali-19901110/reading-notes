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
