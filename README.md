# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input.  The example shows a route that retrieves a user by ID.  The original code fails to handle cases where the provided ID is not a valid number, potentially leading to unexpected behavior or crashes.

The solution demonstrates how to add robust error handling using `isNaN` to check for non-numeric IDs and how to handle this gracefully.