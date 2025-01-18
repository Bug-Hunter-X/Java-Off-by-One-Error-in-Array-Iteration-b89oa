# Java Off-by-One Error in Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over arrays.

The `BuggyArray.java` file contains code with the error.  The loop condition `i <= arr.length` incorrectly includes the index that is out of bounds.

The `FixedArray.java` file provides a corrected version using `i < arr.length`.

This example highlights the importance of careful array index management to prevent runtime exceptions.