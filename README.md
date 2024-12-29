# Unexpected Null Handling in JavaScript Function

This repository demonstrates a common issue in JavaScript related to unexpected behavior when handling null values in functions.  The `foo` function in `bug.js` shows a scenario where the function correctly handles null inputs by returning null.  However, this simple return may not always be desired depending on the specific requirements.

The `bugSolution.js` file offers alternative solutions to handle these null values more robustly.

## How to reproduce:

1. Clone the repository
2. Navigate to the directory
3. Run `node bug.js` in your terminal to see the current behavior.
4. Run `node bugSolution.js` to see the improved handling of null values.