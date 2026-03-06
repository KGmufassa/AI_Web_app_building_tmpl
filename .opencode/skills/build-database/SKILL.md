---
name: build-database
description: Generate database schema, migrations, and ORM models from the architecture data model.
---

# Build Database Skill

This skill converts the data model defined in `architecture.md` into a working database layer.

---

# Required Inputs

The following artifacts must exist:

- docs/reference/architecture.md
- docs/reference/stack.md

If missing, stop execution and report the missing artifact.

---

# Step 1: Identify Database Technology

Read `stack.md` to determine the database type.

Examples:

PostgreSQL  
MySQL  
SQLite  
MongoDB

Determine ORM or database toolkit if specified.

Examples:

Drizzle ORM  
Prisma  
SQLAlchemy  
TypeORM

---

# Step 2: Extract Data Model

From `architecture.md`, identify:

- entities
- attributes
- relationships
- indexes
- constraints

Example entity:

User  
Project  
Task

---

# Step 3: Generate Schema

Create schema definitions in the `/db` directory.

Examples:
