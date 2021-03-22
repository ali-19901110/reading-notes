# Flexbox and Templating
## Javascript Templating : Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source.
- `mustache.js` : is an implementation of the mustache template system in JavaScript. It is often considered the base for JavaScript templating. And, since mustache supports various languages, we don’t need a separate templating system on the server side.

![](https://www.elated.com/res/Image/articles/development/easy-html-templates-with-mustache/simple-demo.png)

- `Mustache-Express` :lets you use Mustache and Express (at least version 3) together, including auto-loading partials.

* To install With Yarn: `$ yarn add mustache-express` Or `$ npm install mustache --save`
* Configure mustache-express in your server.js/app.js/index.js file:
 ![](https://miro.medium.com/max/700/1*ES10lxr7tdRFVEKcRAgLEw.png)
 
 
2 - Create a views folder and add some html view templates (e.g. hello.html).

3 - Then in the router configuration, use res.render(TEMPLATE_NAME, JSON_DATA) `res.render('hello', {"name": "Sherlynn"})`

4 - The second parameter would be the JSON data itself. We can also pass in a variable representing the data, for example:
```
var nameObject = {"name": "Sherlynn"}
res.render('hello', nameObject)
```


## Flexbox :

