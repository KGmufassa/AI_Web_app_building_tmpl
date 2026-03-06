---
description: Generate the frontend architecture specification from design exports
agent: build
subtask: true
---

# Extract Design Specification

Generate the **frontend architecture document** using the provided design exports and the frontend architecture template.

This command converts design artifacts into a structured UI architecture specification.

---

# Inputs

The following design artifacts should exist in the repository:

design/

Possible files include:

- design/figma/layout-tree.json
- design/figma/components.json
- design/figma/tokens.json
- design/stitch/component-map.json
- design/stitch/styles.json

If design files are missing, report the missing artifacts.

---

# Template

Use the following template to generate the architecture file:

@docs/templates/FRONTEND_ARCHITECTURE_TEMPLATE.md

---

# Output

Generate the file:

docs/reference/frontend-architecture.md

---

# Generation Rules

When generating the frontend architecture:

1. Extract the page structure from the design layout tree.
2. Extract the component hierarchy from design components.
3. Extract design tokens (colors, spacing, typography).
4. Identify layouts such as AuthLayout or MainLayout.
5. Define reusable components and UI modules.
6. Define hooks and state management layers.

Ensure the output contains:

- framework configuration
- page map
- component architecture
- layouts
- hooks
- API client layer
- design tokens
- UI data flow

---

# Validation

Before completing:

- ensure pages map to design layouts
- ensure components are modular
- ensure tokens are referenced
- ensure file structure is defined

---

# Completion

Write the generated architecture document to:

docs/reference/frontend-architecture.md

Output confirmation only:

"Frontend architecture successfully generated."
