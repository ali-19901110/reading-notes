# LOCAL STORAGE FOR WEB APPLICATIONS
>  The operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state.These values may be 
stored in the registry, INI files, XML files,or some other place according to platform convention.

### What we really want is

- a lot of storage space
- on the client
- that persists beyond a page refresh
- and isn’t transmitted to the server
Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.

## INTRODUCING HTML5 STORAGE
it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, 
close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually).

> HTML5 STORAGE SUPPORT

             IE            FIREFOX          SAFARI        	CHROME	      OPERA	           IPHONE	        ANDROID
            8.0+          	3.5+	            4.0+	         4.0+	       10.5+          	2.0+	          2.0+
            
            
 > ↶ check for HTML5 Storage
```
function supports_html5_storage() {
  try {
    return 'localStorage' in window && window['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}
```

### USING HTML5 STORAGE
> HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. 
The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. 
If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data 
into the expected JavaScript datatype.

```
interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};
```

#### TRACKING CHANGES TO THE HTML5 STORAGE AREA
> The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener 
(although that will finally be added in IE 9). Therefore, to hook the storage event, you’ll need to check which event mechanism the browser supports.
(If you’ve done this before with other events, you can skip to the end of this section. Trapping the storage event works the same as every other event you’ve ever trapped.
If you prefer to use jQuery or some other JavaScript library to register your event handlers, you can do that with the storage event, too.)
![](https://image.slidesharecdn.com/html5localstorage-140511235722-phpapp01/95/html5-local-storage-12-638.jpg?cb=1399852926)
```
if (window.addEventListener) {
  window.addEventListener("storage", handle_storage, false);
} else {
  window.attachEvent("onstorage", handle_storage);
};
```

![](https://docs.microsoft.com/en-us/azure/storage/blobs/media/storage-blob-event-overview/event-grid-functional-model.png)
