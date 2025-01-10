# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the MongoDB `$inc` operator, leading to an unexpected behavior. The `$inc` operator should take a numerical value, not a string.  This repo provides both buggy and corrected code.

## Bug
The original code attempts to increment the `field` value with a string, resulting in an error or unexpected output.

## Solution
The corrected code uses a numerical value for `$inc` resulting in the correct field increment.
