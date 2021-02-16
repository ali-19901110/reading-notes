# Forms
> Are used to collect user input. The user input is most often sent to a server for processing.
> The HTML `<form>` element is used to create an HTML form
## Example: 
![](https://www.htmlgoodies.com/img/2010/06/HTML-Forms-From-Basics-to-Style-Layouts-Figure2.gif)
> The HTML `<input>` element is the most used form element
> An <input> element can be displayed in many ways, depending on the type attribute

> The <input type="text"> defines a single-line input field for text input
#### The `<label>` Element
- The `<label>` tag defines a label for many form elements.
- The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element
#### The Submit Button
- The <input type="submit"> defines a button for submitting the form data to a form-handler.
- The form-handler is typically a file on the server with a script for processing input data.
- The form-handler is specified in the form's action attribute

> Password Input:
type="password" When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except
the characters are blocked out.They are hidden in this way so that if someone is looking over
the user's shoulder, they cannot see sensitive data such as passwords.


Example (LISTS, TABLES AND FORM)

> <!DOCTYPE html>
<html>
<head>
 <title>Lists, Tables and Forms</title>
 <style type="text/css">
 body {
 font-family: Arial, Verdana, sans-serif;
 font-size: 90%;
 color: #666;
 background-color: #f8f8f8;}
 li {
 list-style-image: url("images/icon-plus.png");
 line-height: 1.6em;}
 table {
 border-spacing: 0px;}
 th, td {
 padding: 5px 30px 5px 10px;
 border-spacing: 0px;
 font-size: 90%;
 margin: 0px;}
 th, td {
 text-align: left;
 background-color: #e0e9f0;
 border-top: 1px solid #f1f8fe;
 border-bottom: 1px solid #cbd2d8;
 border-right: 1px solid #cbd2d8;}
 tr.head th {
 color: #fff;
 background-color: #90b4d6;
 border-bottom: 2px solid #547ca0;
 border-right: 1px solid #749abe;
 border-top: 1px solid #90b4d6;
 text-align: center;
 text-shadow: -1px -1px 1px #666;
 letter-spacing: 0.15em;}
 td {
 text-shadow: 1px 1px 1px #fff;}
 
 #  EVENT
 > An HTML event can be something the browser does, or something a user does
 > Often, when events happen, you may want to do something.
 
 ![](https://slideplayer.com/slide/16279608/95/images/7/Common+HTML+Events+Event+Description+onchange.jpg)
 
HOW EVENTS TRIGGER JAVASCRIPT CODE
1. Select t he element node(s) you want the script to respond to. 
2. Indicate which event on the selected node(s) will trigger the response. 
3. State the code you want to run when the event occurs. 



 
