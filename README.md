# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB.  The `$inc` operator is designed to increment a numeric field, but attempting to increment it with a string value will result in an error. The solution provides the corrected code.

## Bug
The original code incorrectly uses a string value '1' instead of a number 1.  This leads to an error in the update operation. 

## Solution
The corrected code replaces the string '1' with the numeric value 1, ensuring the `$inc` operator works correctly.