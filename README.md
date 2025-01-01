# MongoDB $inc Operator Error
This example demonstrates an incorrect usage of the MongoDB `$inc` operator, specifically when providing a string value instead of a number. The solution shows how to correct the query to increment the field correctly.

## Bug
The original code attempts to increment the `field` value by '1' (a string) which leads to an error.

## Solution
The solution uses a numeric value 1 to correctly increment the `field` value.