# Workflow Versioning

## Problem

Workflows evolve over time.

Changing a workflow definition can affect existing customers and
existing executions.

## Proposed Model

Each workflow has:

- Draft version
- Published version
- Previous versions

Example:

```text
Workflow 1
├── v1 — Published
├── v2 — Draft
└── v3 — Draft
