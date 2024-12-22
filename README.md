# Unhandled Database Query Error in Express Route Handler

This repository demonstrates a common error in Express.js applications:  lack of proper error handling when interacting with a database.

The `bug.js` file shows a route handler that fetches user data. If the user is not found, it correctly sends a 404 response. However, it lacks error handling for potential database query errors.  This can lead to server crashes or, worse, silent failures, making it difficult to debug.

The `bugSolution.js` file provides a corrected version, demonstrating how to handle database errors gracefully and informatively.