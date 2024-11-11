# NODE JS REPL(READ,EVAL, PRINT LOOP)
Node.js REPL (Read-Eval-Print Loop) is an interactive shell that allows you to execute JavaScript code line-by-line and see immediate results.
Quick Testing and debugging.

***REPL stands for:***

Read: The REPL reads user input (JavaScript code).
Eval: The input is evaluated (executed) by the JavaScript engine.
Print: The result of the evaluation is printed to the screen.
Loop: The process repeats (loops), waiting for the next input.
**Executing JS Code in Terminal**
```
const x = 10;
> const y = 20;
> x + y
30
```
```
> function add(a, b) {
...   return a + b;
... }
> add(5, 10)
15
```
***. Underscore (_) Variable***
The REPL provides a special variable _ (underscore) that stores the result of the last evaluated expression.
```
> 3 + 3
6
> _ * 2
12
```
***Saving and Loading REPL Sessions***
The REPL allows you to save the session output to a file and load previously saved sessions, making it easier to keep track of the code you’ve tested.
****Saving a Session****: To save your REPL session to a file, use the .save command:
```
.save ./repl_session.js
```
****Loading a Session****: You can load the saved session into a new REPL session using .load:
```
 .load ./repl_session.js
```
***. Accessing Node.js Core Modules***
The REPL environment allows you to load and use Node.js core modules, such as fs, path, http, etc., without needing to exit the REPL or write an entire script.

```
 const fs = require('fs');
 fs.readFileSync('test.txt', 'utf8');
```

***Error Handling in REPL***
The REPL is forgiving of errors and will display helpful error messages without crashing the entire session. This makes it a safe environment for testing.
```
console.log(foo);
ReferenceError: foo is not defined
```
# Built-in REPL Commands
```.help```: Displays a list of all available REPL commands.
```.break```: Breaks out of multi-line input or clears the current input.
```.clear```: Resets the REPL context by clearing all declared variables.
```.exit```: Exits the REPL session.



