# TypeScript Nullable Type and Undefined Values

This repository demonstrates a common issue in TypeScript when dealing with nullable types and the `undefined` value.  The `greet` function expects a string or `null`, but if `undefined` is passed, a runtime error occurs because TypeScript's type guards don't explicitly handle this scenario.

The `bug.ts` file showcases the problem.  The solution, found in `bugSolution.ts`, demonstrates how to handle `undefined` explicitly to prevent the runtime error.