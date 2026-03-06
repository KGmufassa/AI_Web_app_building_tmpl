---
description: Execute the project test suite and report results
agent: build
subtask: true
---

Run the project's test suite using the configured test runner.

Detect the correct test framework based on the stack configuration.

Possible test frameworks include:

- Jest
- Vitest
- Pytest
- Mocha
- Playwright
- Cypress

---

# Inputs

docs/reference/stack.md  
tests/ directory

---

# Execution

Run the appropriate test command.

Examples:

Node.js:

npm test

Python:

pytest

Frontend:

npm run test

End-to-end:

npx playwright test

---

# Output

Report:

- number of tests executed
- number passed
- number failed
- failing test names
- error messages

---

# Completion

If all tests pass:

"All tests passed."

If failures exist:

"Test failures detected."
