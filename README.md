# Ada Off-by-One Error
This repository demonstrates a common off-by-one error in Ada programming, specifically related to array indexing. Ada arrays are 1-based, unlike some languages that use 0-based indexing.  Failing to account for this can result in runtime errors or incorrect program behavior.

The `bug.ada` file contains the erroneous code, and `bugSolution.ada` provides the corrected version.  The error involves attempting to access an array element at an index that is outside the valid range.

## How to Reproduce
1. Compile and run `bug.ada`.  You will likely encounter a runtime error due to the array bounds violation.
2. Compile and run `bugSolution.ada` to see the corrected code in action.