# Uncommon HTML Bug: Accessing Non-Existent Property

This repository demonstrates a subtle bug in HTML where JavaScript attempts to access a property of an HTML element that doesn't exist. This can lead to unexpected errors and silent failures, making it difficult to debug.

## Bug Description
The `bug.html` file contains a simple HTML structure with a `div` element. The JavaScript code attempts to access a non-existent property (`nonExistentProperty`) of this `div` element and then modify its `style` property.  This action throws a JavaScript error and prevents subsequent code from running properly.

## Solution
The `bugSolution.html` file demonstrates the correct way to handle potential non-existent properties. It uses a conditional check to verify that the property exists before accessing it, preventing the error from happening. 

This example highlights the importance of robust error handling and careful property access in JavaScript when interacting with the DOM.