# FRONTEND ARCHITECTURE

This document is generated from the design specification command.

It defines the frontend system architecture derived from design artifacts and project specifications.

---

## Framework

Populate from:

docs/reference/stack.md

Must include:

Frontend framework  
Routing system  
Styling system  
State management approach

---

## Design System

Extract from design sources.

Include:

Styling framework  
Theme strategy  
Typography  
Color tokens  
Spacing system  

---

## Page Map

Populate all discovered pages.

Each page must include:

Page Name  
Route  
Layout  

---

## Layout Architecture

Define shared layout containers.

Each layout must include:

Layout name  
Pages using layout  
Contained components  

---

## Component Architecture

List all components discovered from design sources.

Categorize:

Shared components  
Layout components  
Page components  

---

## Component Graph

Hierarchical structure of UI components.

Must represent parent-child relationships between:

Pages  
Layouts  
Components  

---

## Page Wiring Graph

Define page connections.

Each page must include:

Route  
Layout  
Hooks  
API endpoints  
Components  

---

## UI Dependency Graph

Define deterministic generation order.

Structure must contain:

Layouts  
Shared components  
Nested components  
Hooks  
Pages  

---

## State Management Strategy

Define UI state boundaries.

Include:

Local state  
Shared state  
Server state hooks  

---

## API Integration Layer

Define service layer connecting frontend hooks to backend endpoints.

Include:

Service modules  
Hook-to-endpoint mapping  

---

## File Structure

Define frontend directory layout.

Must include:

components/  
layouts/  
pages/  
hooks/  
services/  
styles/  
lib/  

---

## Validation Checklist

Confirm:

Pages have routes  
Layouts exist  
Components mapped  
Hooks mapped to endpoints  
Dependency graph has no cycles
