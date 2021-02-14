# Table 
allow web developers to arrange data into rows and columns.
- The `<table>` tag defines an HTML table.
- Each table row is defined with a `<tr>` tag. Each table header is defined with a `<th>` tag. Each table data/cell is defined with a `<td>` tag.
- By default, the text in <th> elements are bold and centered.
- By default, the text in <td> elements are regular and left-aligned.

**Example**

![](https://www.guru99.com/images/image029.png)

## HTML Table - Add a `Border`
`To add a border to a table, use the CSS border property:`
> Example
`table, th, td {
  border: 1px solid black;
}`

#### Spanning ColumnS
> The `column-span` property specifies how many columns an element should span across.

#### The `rowspan` attribute specifies the number of rows a cell should span.

#### Long Tables :
> There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content).
> These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table (as you will see
when you learn about CSS).
- `<thead>` The headings of the table should sit inside the `<thead>` element.
- `<tbody>` The body should sit inside the
- `<tbody>` element.
- `<tfoot>`The footer belongs inside the
- `<tfoot>` element.

> `Objects` group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names. 
Example:
`var person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};`
#### The this Keyword
1. In a function definition, `this` refers to the "owner" of the function.
2. In the example above, `this` is the person object that "owns" the fullName function.
3. In other words, `this`.firstName means the firstName property of this object.

> JavaScript Methods
- JavaScript methods are actions that can be performed on objects.
- A JavaScript method is a property containing a function definition.

### Accessing Object Methods
 > `syntax` objectName.methodName()
 
### STORING DATA
> In JavaScript, data is represented using name/value pairs. To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key. 
> ARRAYS
Arrays can store multiple pieces of information.Each piece of information is separated by a comma.The order of the values is important because items
in an array are assigned a number (called an index). 

