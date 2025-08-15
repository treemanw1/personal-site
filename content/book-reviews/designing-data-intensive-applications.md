---
title: "Designing Data Intensive Applications"
date: 2025-2-27
---

# 1. Reliability, Scalability & Maintainability

Scalability - Balancing Load and Performance

# 2. Data Models

One-to-many relationship: Foreign key versus multi-valued data

Document databases offer flexibility and work well for one-to-many relationships
but are not as good for capturing many-to-many relationships. Tech is a circle:
application developers of the 70s struggled with these issues of document
databases in _hierarchical models_, which are similar to the JSON model used by
document data, leading to the eventual development of SQL.

## Document vs Relational Model

It depends on the interconnectedness of the data. Relational models are built to
handle Many-to-many relationships whereas additional cumbersome application code
is needed in Documents models to handle those relationships.

The nature of data: Does it adhere to a rigid schema? If not enforcing one via
the Relational model may do more harm than good.
