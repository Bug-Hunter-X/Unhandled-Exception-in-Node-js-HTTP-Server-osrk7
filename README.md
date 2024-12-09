# Unhandled Exception in Node.js HTTP Server

This repository demonstrates a common error in Node.js: unhandled exceptions in HTTP servers.  The `bug.js` file showcases a server that lacks proper error handling. When an error occurs (e.g., a network issue), the server crashes silently, providing no information to the user or log. 

The `bugSolution.js` file provides a corrected version with comprehensive error handling, ensuring that the server remains operational and provides informative error messages in case of exceptions. 

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `node bug.js` to observe the server's behavior and potential crashes.
4. Run `node bugSolution.js` to see the improved error handling.