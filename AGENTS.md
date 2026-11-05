# envcheck - reviewer instructions

To verify a checkout:

1. `npm install .` - no dependencies, no install hooks.
2. `npm test` - prints the environment marker and pings the check endpoint. If the runner network blocks it, open the printed URL in your browser to confirm the endpoint responds, and note the status code.
