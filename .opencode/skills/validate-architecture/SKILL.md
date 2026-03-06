---
name: validate-architecture
description: Ensure generated code follows architecture rules.
---

Steps:
1. Read docs/reference/architecture.md
2. Scan project directory structure
3. Compare architecture expectations to actual files
4. Validate dependency rules
5. Report violations

Example violations:
- controllers accessing database directly
- UI importing backend modules
- files placed outside defined folders
