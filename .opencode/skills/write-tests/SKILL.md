---
name: write-tests
description: Generate tests covering backend services, APIs, and UI interactions.
---

# Write Tests

---

## Step 1 — Unit Tests

Test service layer functions.

Example:

tests/unit/userService.test.ts

---

## Step 2 — API Tests

Test endpoints.

Example:

tests/api/users.test.ts

---

## Step 3 — Integration Tests

Test complete workflows.

Example:

create project → add task → retrieve tasks

---

## Step 4 — Validation

Ensure:

- endpoints return expected responses
- database interactions succeed
- frontend calls correct APIs
