# MongoDB $inc operator error with string value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error arises from providing a non-numeric value to the `$inc` operator, which expects a number for incrementing a counter.

## Bug
The `bug.js` file contains a MongoDB update query that attempts to increment the `count` field with a string value. This results in a runtime error.

## Solution
The `bugSolution.js` file shows the corrected version where a numeric value is used for incrementing the counter.  The solution handles type checking for robustness.
