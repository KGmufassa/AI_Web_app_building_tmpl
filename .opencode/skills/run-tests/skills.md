---
name: run-tests
description: Execute the project's automated tests and report results
---

# Run Tests

Execute the project's automated test suite.

---

## Step 1 — Detect Test Framework

Inspect the stack configuration and package files to determine the test runner.

Possible frameworks:

Jest  
Vitest  
Pytest  
Mocha  
Playwright  

---

## Step 2 — Execute Tests

Run the appropriate command.

Examples:

npm test  
pytest  
npx playwright test  

---

## Step 3 — Capture Results

Record:

total tests  
passed tests  
failed tests  

---

## Step 4 — Report Failures

If failures occur:

- identify failing files
- show error messages
- identify failing modules

---

## Step 5 — Provide Summary

Example output:

Tests executed: 42  
Passed: 39  
Failed: 3
