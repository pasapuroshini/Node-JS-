# NODE JS
Node.js is an open-source server environment that uses JavaScript on the server.
**Key features of Node.js**
1.Non-blocking I/O: Node.js is asynchronous, enabling efficient handling of concurrent requests.
2.Event-driven architecture: Developers can create event-driven applications using callbacks and event emitters.
3.Extensive module ecosystem: npm (Node Package Manager) provides access to thousands of reusable packages.
4.Single-threaded Model: Node js runs on a single thread despite being asynchronous, it uses an event loop to handle requests.
**Core Modules**
Node.js includes several core modules for essential functionality. Some commonly used ones are:

fs (File System): Read/write files and directories.
http: Create HTTP servers and clients.
path: Manipulate file paths.
events: Implement custom event handling.
***Datatypes in Node.js***
Node.js contains various types of data types similar to JavaScript.

1.Boolean
2.Undefined
3.Null
4.String
5.Number

**String Functions ,String in Node js**
```
let x = "Welcome to Github ";

let y = 'Node.js Tutorials';

let z = ['Geeks', 'fw3', 'hackerearth'];

console.log(x);

console.log(y);

console.log("Concat Using (+) :", (x + y));

console.log("Concat Using Function :", (x.concat(y)));

console.log("Split string: ", x.split(' '));

console.log("Join string: ", z.join(', '));

console.log("Char At Index 5: ", x.charAt(5));
```
***Buffer in Node.js***
In node.js, we have a data type called “Buffer” to store binary data and it is useful when we are reading data from files or receiving packets over the network. 


























