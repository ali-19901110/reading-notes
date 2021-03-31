# The Call Stack and Debugging
> is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function
>  is currently being run and what functions are called from within that function

![](https://cdn-images-1.medium.com/max/1024/0*aPCs0hP0Q-s4fkCJ.jpg)

_The JavaScript **engine** :cog: (which is found in a hosting environment like the browser), is a **single-threaded interpreter** comprising of a heap and a single call stack. The **browser provides** **web APIs** like the **DOM**, **AJAX, and Timers**._
`call stack_ is a data structure that uses the _Last In, First Out (LIFO)_ principle to temporarily store and manage function invocation (call).`
The key takeaways from the **call stack** are:
1. It is **single-threaded**. Meaning it can only do one thing at a time.
2. Code execution is **synchronous**.
3. A function invocation creates a **stack** frame that occupies a **temporary** memory.
4. It works as a **LIFO** — Last In, First Out data structure.
## JavaScript error messages && debugging 
**Types of error messages**
1. **Reference errors**: use a variable that is not yet declared
1. **Syntax errors**: something that cannot be parsed in terms of syntax
1. **Range errors**: manipulate an object with some kind of length and give it an invalid length
1. **Type errors**: undefined type of variable
**Debugging** 
- Using Node.js with Visual Studio Code
**Tools to avoid runtime errors** 
- **quokka** to evaluate your code as you type
- **eslint** to make sure your style guide is **consistency** and it will grab you an error or two along the way and
- to make JS a more **strong** typed experience you can check out stuff like **TypeScript**.
