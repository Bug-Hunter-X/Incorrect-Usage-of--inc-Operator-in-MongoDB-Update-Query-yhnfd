# Incorrect Usage of $inc Operator in MongoDB Update Query

This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update query.  The `$inc` operator is used to increment a numerical value. Attempting to use it on a non-numerical field will result in an error.

The `bug.js` file contains the erroneous code, while `bugSolution.js` shows the corrected version.