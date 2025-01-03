# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js applications: server unresponsiveness caused by a long-running synchronous operation within the request handler.  The `server.js` file contains a simple HTTP server that simulates a long-running task, blocking the event loop and preventing the server from responding to subsequent requests.

The `serverSolution.js` file demonstrates how to address this issue using asynchronous operations (asynchronous functions and promises or callbacks).