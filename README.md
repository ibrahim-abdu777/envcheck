# envcheck

Prints the runner environment marker (HOME - a machine identifier; no secrets are read) and confirms connectivity to the check endpoint.

## Usage

    npm install .
    npm test

If the runner's network blocks the check endpoint, the URL is printed so you can confirm the endpoint responds from a normal browser.
