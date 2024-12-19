# Off-by-One Error in Java Array

This repository demonstrates a common off-by-one error in Java when iterating through an array. The error occurs because the loop condition `i <= arr.length` attempts to access an index that is out of bounds. Arrays in Java are zero-indexed, so the last valid index is `arr.length - 1`.

The `Bug.java` file contains the buggy code.  The `BugSolution.java` file provides a corrected version.  Understanding this type of error is crucial for writing robust Java applications.