# Unhandled Promise Rejection in Express.js Async Route

This repository demonstrates a common error in Express.js applications: unhandled promise rejections in asynchronous routes.  The `bug.js` file contains an Express.js application with an asynchronous route that lacks proper error handling. This can lead to unexpected crashes and unhandled promise rejections, making your application unstable.

The `bugSolution.js` file shows how to properly handle such errors using `try...catch` blocks or `.catch()` on promises.  Always ensure your asynchronous operations are appropriately handled to prevent these issues.

## How to reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `npm install express`
4. Run `node bug.js`
5. Observe the server behavior and potential crashes. Repeat several times to see the error.
6. Run `node bugSolution.js` to see the corrected version.

## License

MIT