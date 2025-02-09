# Java ArithmeticException: Division by Zero

This repository demonstrates a common Java error: the `ArithmeticException` caused by division by zero. The `bug.java` file contains the erroneous code, while `bugSolution.java` provides a corrected version that handles potential division by zero.

**Problem:** The original code attempts to divide an integer by zero, resulting in an `ArithmeticException`. This is a runtime exception that halts program execution.

**Solution:** The corrected code includes a check to prevent division by zero. If the divisor is zero, an appropriate message is printed; otherwise, the division is performed normally.