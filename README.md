# Login Page Automated Tests

This repository contains automated tests for a login page using Playwright.

## Setup

1. Clone the repository: `git clone https://github.com/tasnintania/login-test.git` and go to directory : `cd login-test`
2. Install dependencies: `npm install`
3. Install: `npx playwright install`
4. Run tests: `npx playwright test`
5. Run tests with HTML report: `npx playwright test --reporter=html`
6. To show report: `npx playwright show-report`


## Branching Strategy

- `main`: Contains all merged test scenarios


Each feature was developed in its own branch and merged to main after review.

## Test Approach

Tests follow the Page Object Model pattern for better maintainability. 
Playwright was chosen for its excellent cross-browser support and built-in assertions.


