# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The code attempts to access an array element beyond the array's valid index range. This example highlights the importance of careful index management when working with arrays in Java.

## How to reproduce:

1. Clone this repository.
2. Compile and run the `bug.java` file.
3. Observe the `ArrayIndexOutOfBoundsException`.

## Solution:

The provided `bugSolution.java` file demonstrates the corrected code.  The key change is modifying the loop condition to ensure that the loop iterates only within the valid index range of the array (0 to arr.length - 1).