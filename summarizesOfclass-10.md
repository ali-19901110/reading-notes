# Error Handling & Debugging
Errors, bugs, and therefore debugging are a part of life for a programmer. As the saying goes, if you haven’t made any mistakes, then you aren’t trying hard enough.

Dealing with errors actually involves two very different processes: error handling and debugging. Error handling is a combination of coding and methodology that allows
your program to anticipate user and other errors. It allows you to create a robust program. Error handling does not involve weeding out bugs and glitches in your source code,
although some of the error handling techniques covered in this chapter can be used to great advantage at the debugging stage. In general,
error handling should be part of your overall program plan, so that when you have an error-free script, nothing is going to bring it to a screeching halt.
With some sturdy error handling in place, your program should be able to keep running despite all the misuse that your users can—and certainly will—throw at it

1. THE CONSOLE & DEV TOOLS 
> Tools built into the browser that help you hunt for errors.
2. COMMON PROBLEMS 
> Common sources of errors,and how to solve them. 
3. HANDLING ERRORS 
> How code can deal with potential errors gracefully. 

![](https://static.javatpoint.com/python/images/python-exception-handling.png)

## Types of Errors
- Syntax Errors

![](https://lh3.googleusercontent.com/proxy/BTCdnJthRRagbCBXhEkTzMkomqs0bpllBWZXC4WxfHlRZ7SHa1r4PLbWccZcmUfzCYUHJLPtHI7DrWfPUeHuFtflhM2a5UvsndcHOaufoNMcr_U3VzCgIJDzom2l8dlDHO0BrcIz)

- Runtime Errors

![](https://www.toolsqa.com/wp-content/gallery/javascript/1-Runtime-error-in-JavaScript.png)

- Logic Errors

![](https://images.ctfassets.net/cj4mgtttlyx7/4EEmNj7G9MdsYn1FrKaYyh/cfe042f855745406ec03691ee942ad53/cannot-set-property.png)

### Example
> `<HTML>`
`<HEAD><TITLE>Error Checking</TITLE>`
`<BODY>`
`<SCRIPT LANGUAGE=VBSCRIPT RUNAT=SERVER>`

`Dim n, x`

`n = 10`
`x = Request.Form.Item("txtNumber")`

`If x = 0 Or Not IsNumeric(x) Then`
  `Response.Write "x is an invalid entry"`
`Else`
  `y = n / x`
  `Response.Write y`
`End If`

`</SCRIPT>`

`</BODY>`
`</HTML>`

#### Debugging
You’ve designed your solution and written the code. You start to load it into the browser with high hopes and excitement, only to be faced with an big ugly gray box
telling you that the VBScript engine doesn’t like what you’ve done.So where do you start? Well, I find that another cup of coffee helps,
but most of the time the error’s still there when I rerun the script.

**Syntax errors**
You may have spelled something incorrectly or made some other typographical or syntactical error. When this happens, usually the program won’t run at all.

**Logical errors**
Although syntactically correct, your program either doesn’t function as you expect, or it generates an error message.
