# MongoDB $inc Operator with String Value
This repository demonstrates an uncommon error in MongoDB when using the `$inc` operator with a string value instead of a numeric value.  The incorrect usage can lead to unexpected behavior and data corruption if not caught early.

The `bug.js` file shows the incorrect implementation, while `bugSolution.js` provides the correct implementation.

## Bug
The `$inc` operator is used to increment a numeric field in a MongoDB document. However, if you use a string value with the `$inc` operator, it won't increment the value as expected.

## Solution
Ensure that you use a numeric value with the `$inc` operator to increment the field correctly.