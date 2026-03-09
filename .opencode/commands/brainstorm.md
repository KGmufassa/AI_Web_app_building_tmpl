---
description: Interactive product discovery and idea refinement
agent: plan
subtask: false
---

# Brainstorm Command

Use the text provided with the command as the initial brain dump.

Brain dump input:
$ARGUMENTS

If no arguments are provided, use the current terminal context as the idea.

---

# Step 1 — Analyze the Idea

Extract the following from the input:

- problem being solved
- target user
- proposed solution
- assumed features
- technical hints
- industry domain

---

# Step 2 — Research the Domain

Identify common industry patterns for this type of application.

Examples:

- SaaS platforms
- AI tools
- marketplaces
- mobile applications
- internal enterprise tools

Identify typical:

- features
- architecture patterns
- integrations
- risks

---

# Step 3 — Interactive Question Loop

Ask **one question at a time**.

After asking a question:

STOP.

Wait for the user's response before continuing.

Questions should cover:

• product definition  
• user definition  
• feature set  
• platform decisions  
• integrations  
• AI usage  
• security considerations

Continue asking questions until sufficient information is collected.

---

# Step 4 — Challenge Layer

Once enough context exists, challenge the idea by questioning:

- assumptions
- adoption barriers
- technical feasibility
- scalability risks
- competitive alternatives

Ask challenge questions one at a time.

---

# Step 5 — Generate Brainstorm Document

When questioning is complete, generate:

docs/reference/brainstorm.md

Include:

Problem  
Target Users  
Industry Context  
Product Concept  
Core Features  
Secondary Features  
Platform  
Data Sources  
AI Requirements  
Integrations  
Risks  
Open Questions


---

# Update Project State

Update the following file:

docs/reference/project-state.md

Modify:

Phase: [CURRENT_COMMAND_PHASE]
Last Updated: [CURRENT_TIMESTAMP]

Save changes.
