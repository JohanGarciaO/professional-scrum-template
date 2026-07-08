# Architecture Decision Records (ADRs)

This directory contains the project's **Architecture Decision Records (ADRs)**.

An ADR documents an important architectural decision, the reasoning behind it, the alternatives that were considered, and the consequences of the chosen solution.

Over time, ADRs become a valuable historical record, helping current and future contributors understand **why** decisions were made—not just **what** was implemented.

---

## When should an ADR be created?

Create an ADR whenever a decision has a significant and lasting impact on the project's architecture.

Typical examples include:

- Choosing an architectural pattern.
- Selecting a database technology.
- Defining an authentication strategy.
- Establishing a deployment model.
- Adopting a branching strategy.
- Introducing a new external dependency.
- Changing an existing architectural decision.

As a general rule:

> If future contributors are likely to ask _"Why did we choose this?"_, the decision probably deserves an ADR.

---

## When should an ADR NOT be created?

Avoid creating ADRs for routine development decisions, implementation details, or temporary changes.

Examples include:

- Bug fixes.
- Feature implementations.
- Code refactoring.
- Minor library updates.
- Styling or formatting changes.

An ADR should document **architectural decisions**, not day-to-day development activities.

---

## How to create a new ADR

1. Copy `ADR-0000-template.md`.
2. Rename the file using the next available number.
3. Replace the placeholder content with your project's decision.
4. Commit the ADR together with the implementation whenever possible.

Example:

```text
ADR-0001-adopt-postgresql.md

ADR-0002-use-github-flow.md

ADR-0003-adopt-clean-architecture.md
```

---

## Naming Convention

Use the following format:

```text
ADR-XXXX-short-description.md
```

Examples:

```text
ADR-0001-adopt-postgresql.md

ADR-0002-use-github-flow.md

ADR-0003-adopt-clean-architecture.md
```

---

## ADR Status

Each ADR should include one of the following status values:

| Status     | Description                 |
| ---------- | --------------------------- |
| Proposed   | Under discussion.           |
| Accepted   | Officially adopted.         |
| Rejected   | Considered but not adopted. |
| Deprecated | No longer recommended.      |
| Superseded | Replaced by a newer ADR.    |

---

## Best Practices

- Keep ADRs concise and objective.
- Explain the reasoning behind the decision.
- Document alternatives that were considered.
- Describe both positive and negative consequences.
- Never modify the historical context of an accepted ADR.
- If a decision changes, create a new ADR instead of rewriting the previous one.

---

> 💡 **Engineering Tip**
>
> Code explains _how_ a system works.
>
> ADRs explain _why_ it was designed that way.
