# Polynomial Calculator

This Java program reads polynomial expressions from an input file, evaluates them, calculates their derivatives, and writes the results to an output file. It also handles invalid polynomial expressions gracefully.

## How it works

1. The program reads polynomial expressions from the `input.txt` file, one expression per line.

2. It evaluates each expression, simplifies it (if possible), calculates its derivative, and writes the results to the `output.txt` file.

3. If an expression is not a valid polynomial or cannot be processed, the program writes "Invalid polynomial" in the output file.

## Input Format

The input file (`input.txt`) should contain polynomial expressions, one expression per line. Each expression should adhere to the following format:

- Use 'x' as the variable.
- Use '^' for exponentiation, e.g., 'x^2' for x squared.
- Use '+' and '-' for addition and subtraction.
- Use '*' for multiplication.
- Use double type coefficients.
- 
