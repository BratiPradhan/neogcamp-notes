**CONSOLE** - IT IS A **REPL** - 
**R**EAD, **E**VALUATE, **P**RINT, AND **L**OOP

- It reads the javascript that you type into it
- evaluates your code
- prints out the result of your expression
- then loops back to the first step


#### CHROME DEV TOOLS 

- view and change the page's JS or DOM
- run arbitrary JS that is not related  to the page


#### CONSOLE
The CONSOLE has a set of functions that make it easier to interact with a page.

- alias of document.querySelector() is --> $()
- debug(function) effectively sets a breakpoint on the first line of that function.
- keys(object) returns an array containing the keys of the specified object


## LOGGING MESSAGES IN THE CONSOLE

** STACK TRACE ** - THE CALL that happened first is at the bottom of the stack trace.
Log Stack traces - ** console.trace()


#### STYLING CONSOLE
const spacing = '2px'
const styles = `padding: ${spacing}; border: ${spacing}; background: gray; color: maroon;`
console.log('%cSTYLING CONSOLE...', styles)


### MESSAGES LOGGED BY THE BROWSER
####1. 404 -
The browser logs a 404 network error because the page's JAVASCRIPT tried to fetch a file that doesn't exist.

####2. TypeError -
The browser logs an uncaught TypeError because the JavaScript is trying to update a DOM node that doesn't exist.
