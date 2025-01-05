# Unresponsive Node.js Server

This repository demonstrates a common issue in Node.js applications where a long-running synchronous operation blocks the event loop, causing the server to become unresponsive.  The `bug.js` file shows the problematic code, while `bugSolution.js` provides a solution using asynchronous operations.