# MongoDB $inc operator error with string value
This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value.  However, if you provide a string value instead of a number, MongoDB will throw an error.

The `bug.js` file shows the incorrect usage, resulting in an error. The `bugSolution.js` file shows the correct implementation.

## How to reproduce
1. Clone this repository.
2. Run `mongo` to connect to your MongoDB instance.
3. Execute the code in `bug.js`.
4. Observe the error message.
5. Execute the code in `bugSolution.js` to see the correct usage.