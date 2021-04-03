# EJS

>`EJS` is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript

![](https://images.g2crowd.com/uploads/product/image/social_landscape/social_landscape_f9dd821cb48125c63c64b6f5c7552372/ejs.png)

*How To Install EJS *
>`$ npm install ejs`

*How To Use EJS to Template Your Node Application*
- File Structure
```
- views
----- partials
---------- footer.ejs
---------- head.ejs
---------- header.ejs
----- pages
---------- index.ejs
---------- about.ejs
- package.json
- server.js
 ```
- package.json
```
{
  "name": "node-ejs",
  "main": "server.js",
  "dependencies": {
    "ejs": "^3.1.5",
    "express": "^4.17.1"
  }
}
```
