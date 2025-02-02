# Assembly Overflow Bug

This repository demonstrates a common error in assembly programming: integer overflow.  The `bug.asm` file contains code that adds two 16-bit values without checking for overflow.  This can lead to unexpected and incorrect results.

The solution, provided in `bugSolution.asm`, demonstrates how to check for overflow before performing the addition, thus preventing unexpected behavior.

This example highlights the importance of handling potential overflow conditions when working with integer arithmetic in low-level programming languages like assembly.