---
name: run-tests
description: Execute automated tests and automatically configure the correct test framework if necessary.
---

# Run Tests

Run the automated test suite for the project.

---

# Step 1 — Detect Project Stack

Inspect:

docs/reference/stack.md  
package.json  
project files

Determine:

language  
framework

---

# Step 2 — Detect Test Framework

Select correct framework.

Node → Vitest  
Python → Pytest  
React Native → Jest  
Flutter → Flutter test

---

# Step 3 — Setup Framework (if missing)

Check if configuration exists.

If missing, generate:

test configuration file  
tests/setup file  
.env.test  

Ensure package scripts exist.

---

# Step 4 — Execute Test Suite

Run the appropriate command.

Examples:

npm test  
pytest  
go test ./...

---

# Step 5 — Capture Results

Record:

number of tests  
pass/fail results  
error logs

---

# Step 6 — Return Result

Provide test summary.
