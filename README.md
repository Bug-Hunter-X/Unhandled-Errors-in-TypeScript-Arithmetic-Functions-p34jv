# Unhandled Errors in TypeScript Arithmetic Functions

This repository demonstrates a common error in TypeScript: insufficient error handling in arithmetic functions.  The provided `bug.ts` file contains a set of basic arithmetic functions (`add`, `subtract`, `multiply`, `divide`). While the `divide` function handles division by zero, the others lack error handling for potential issues such as invalid input types.

The solution, `bugSolution.ts`, addresses this by adding robust type checking and error handling to each function. This makes the code more resilient and reliable.

## How to Run

1. Clone this repository.
2. Navigate to the repository directory.
3. Compile the TypeScript code using `tsc bug.ts` and `tsc bugSolution.ts`
4. Run the compiled JavaScript files (bug.js and bugSolution.js) using Node.js.

## Learning Points

* Importance of comprehensive error handling in functions.
* Using TypeScript's type system to prevent runtime errors.
* Writing robust and reliable code.