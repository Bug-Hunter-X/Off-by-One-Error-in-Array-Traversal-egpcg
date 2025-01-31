# Off-by-One Error in Java Array Traversal

This repository demonstrates a common off-by-one error in Java when iterating over an array.  The `BuggyArraySum.java` file contains the erroneous code, while `CorrectedArraySum.java` provides the corrected version.

The bug results in an `ArrayIndexOutOfBoundsException` because the loop condition `i <= arr.length` tries to access an element beyond the array's bounds.  Arrays in Java are zero-indexed, so the last valid index is `arr.length - 1`.

This example highlights the importance of careful loop condition checks when working with arrays and other collections in Java.