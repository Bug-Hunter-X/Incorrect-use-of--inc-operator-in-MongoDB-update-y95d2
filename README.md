# Incorrect use of $inc operator in MongoDB update
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation. The `$inc` operator is used to increment a numerical field by a specified value.  However, if a string is provided as the increment value, the operation will fail or produce unintended results.  The solution shows the correct way to use `$inc` with a numerical value.

## Bug
The bug lies in providing a string value ('1') to the `$inc` operator instead of a numerical value (1).  This leads to an error or unexpected behavior within MongoDB.

## Solution
The solution demonstrates the correct way to use the `$inc` operator, providing a numerical value for incrementing the `count` field.