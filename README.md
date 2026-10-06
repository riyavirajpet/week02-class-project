The application reads two numbers, a voltage V in volts and a resistance R in ohms, and prints the current I = V /
R. If the input is not numeric or the resistance is zero or negative, it prints "Invalid input". These two cases are
the acceptance criteria the program must pass.

Each test is a pair of files: the input typed by the user and the exact output expected.
tests/input1.txt -> 12 4
tests/expected1.txt -> Current: 3 A

Because of set -eu, the script stops with a nonzero exit code at the first failing test. 

Debugging: 
This code was given, however overall debugging involved adding newlines into the test files in order to match the output of the program
in main. 
