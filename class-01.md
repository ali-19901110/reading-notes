# Class-01 *(HTMLWithCSS&&JS)*
- HTML `Describes the Structure of Pages`.
- CSS  `describes how HTML elements should be displayed`.
- JS   `makes HTML pages more dynamic and interactive`.
## How the Web Works?
![](https://public-archive.web.cern.ch/Objects/About/ClientServer.gif)

### HTML Describes the Structure of Pages
![](https://clearlydecoded.com/assets/images/posts/2017-09-04-anatomy-of-html-tag/simple-p-tag.png)
![](https://lh3.googleusercontent.com/proxy/qeFEG-b9RUgmgMyz1p3tAdnK3QZgyxWqZeVxHeXLgoFh5k1Pv9hyjYVtzpgsQ6xptET9Xs84XE1UNBapvmISGEpo45X7FmDXCydAbYZrQoyyC9kzvJda7UArHM7iLY0vF8Y8q2g)


#### FORMS element
The `<form>` tag in HTML is used to create form for user input. There are many elements which are used within form tag. For example: `<input>, <textarea>, <button>, <select>, <option>, <optgroup>, <fieldset>, <label>`.
Syntax:
`<form> Form Content... </form>`
**`Attributes`**: There are many attributes which are associated with `<form>` tag. Some of them are listed below:

- **input**: It is used to specify the input field for user.
- **textarea**: It is used to specify for multi-line text input field for user.
- **button**: It is used to perform an operation in a form by the user.
- **label**: It is used to give label to any tag like button, input etc.

Example:
> <!DOCTYPE html> 
> <html> 
	<head> 
		<title>form tag</title> 
		<style> 
			body { 
				text-align:center; 
			} 
			h1 { 
				color:green; 
			} 
		</style> 
	</head> 
	<body> 
		<h1>GeeksforGeeks</h1> 
		<h2><form> Tag</h2> 
		<form action="#"> 
			First name: 
			<input type="text" placeholder = "First Name"
			value=""> 
			<br><br> 
			Last name: 
			<input type="text" placeholder = "Last Name"
			value=""> 
			<br><br> 
			<input type="submit" value="Submit"> 
		</form> 
	</body> 
</html>	
 Output:
  
![](https://media.geeksforgeeks.org/wp-content/uploads/form1-1.png)

#### Overview
1. Whenever you want to collect information from visitors you will need a form, which lives inside a `<form>` element.
2. Information from a form is sent in name/value pairs.
3. Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.
4. HTML5 introduces new form elements which make it easier for visitors to fill in forms.

# Html5 Layout Elements:
 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. They are still subject to change, but that has not stopped many web page authors using them already
 
 ![](https://lh3.googleusercontent.com/proxy/5Czm6osxJAPN0E2HWhuc-XdfPv9jtFtwZrMHCZp8rDhJbEd04r0LLiXNAbKkGtMgY4X1jm_CA1DTn7VEE4RTq5Vu2sOb6cmtqmndXDDnw8k9YKQe4CT9Y1LYNz_JSVUyxBNNP9Ac)
 
> Sectioning Elements `<div>`:
* The <div> tag defines a division or a section in an HTML document.

* The `<div>` tag is used as a container for HTML elements - which is then styled with CSS or manipulated with JavaScript.

* The `<div>` tag is easily styled by using the class or id attribute.

* Any sort of content can be put inside the `<div>` tag! 

**Note: By default, browsers always place a line break before and after the `<div>` element**
