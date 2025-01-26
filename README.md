# React Native: Unexpected Type Error in Asynchronous Function

This repository demonstrates a common type error in React Native applications that arises from asynchronous operations and unexpected data types.  The `bug.js` file contains the buggy code, while `bugSolution.js` shows the corrected implementation.

The problem occurs because the function expects a number but the promise resolves with a string. This issue is highlighted and resolved by using type guards and/or proper type checking.