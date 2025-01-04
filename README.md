# MongoDB $inc Operator Error with String Value
This example demonstrates an incorrect usage of the MongoDB $inc operator, resulting in an unexpected error.  The $inc operator requires a numerical value for incrementing; attempting to use a string will cause an error.

**Bug:** Incorrect usage of $inc operator leads to a failure during update.

**Solution:** Correctly use $inc with a numerical value to increment a field.