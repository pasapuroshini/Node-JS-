# Import required Modules
```
var http = require("http");
```
# Creating a server in Node
```
http.createServer().listen(8080);
```
# Read request and return response in Node
```
http.createServer(function (request, response) {...}).listen(8080);

```

## Example Code:
```
// Require http header
var http = require('http');
 
// Create server
http.createServer(function (req, res) {

    // HTTP Status: 200 : OK
    // Content Type: text/html
    res.writeHead(200, {'Content-Type': 'text/html'});
    
    // Send the response body as &quot;Hello World!&quot;  
    res.end('Hello World!');

}).listen(8080);


```
