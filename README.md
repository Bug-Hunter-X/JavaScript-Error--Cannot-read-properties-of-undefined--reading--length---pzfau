# JavaScript Uncommon Bug: Handling Undefined in Length Checks

This repository demonstrates a common yet easily overlooked JavaScript error: attempting to access the `length` property of an undefined value.

The `bug.js` file contains a function `foo` that attempts to return the length of an input. It correctly handles `null` but fails when given `undefined`.

The `bugSolution.js` file showcases a corrected version that explicitly handles both `null` and `undefined` values, preventing the error.

This example highlights the importance of robust error handling when dealing with potentially undefined values in JavaScript.