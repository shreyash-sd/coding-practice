# Basic HTTP Server Template

This is a basic HTTP server template using Express.js. Use this template whenever you need to create a simple HTTP server.

```javascript
const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => {
    res.send('Hello World!');
});

app.listen(port, () => {
    console.log(`Server running at http://localhost:${port}/`);
});

To run this server, save the code in a file named server.js, then run node server.js in your terminal. Open a web browser and navigate to http://localhost:3000/ to see the server in action.

```

This Markdown content includes a title, a brief description, a code block with JavaScript code, and instructions on how to run the server. The code block is denoted by triple backticks (```) with the language identifier (javascript), which helps with syntax highlighting in Markdown viewers that support it.