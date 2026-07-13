# Research Documents

This directory contains the project's **Research Documents**.

A Research document records an investigation performed to reduce uncertainties, evaluate alternatives, and support future technical or business decisions.

Unlike an Architecture Decision Record (ADR), which documents the final decision, a Research document captures the investigation that led to that decision.

Over time, Research documents become a valuable knowledge base, helping current and future contributors understand **what was investigated**, **which alternatives were considered**, and **what conclusions were reached**.

---

## When should a Research document be created?

Create a Research document whenever an investigation is required before making an important implementation or business decision.

Typical examples include:

- Evaluating alternative technologies.
- Comparing software libraries or frameworks.
- Investigating architectural approaches.
- Assessing performance trade-offs.
- Studying external APIs or services.
- Exploring possible solutions before implementation.

As a general rule:

> If the team needs to investigate before deciding, the work probably deserves a Research document.

---

## When should a Research document NOT be created?

Avoid creating Research documents for routine development activities or investigations that do not produce reusable knowledge.

Examples include:

- Simple implementation questions.
- Minor debugging activities.
- Code refactoring.
- Routine feature development.
- Temporary experiments with no relevant conclusions.

A Research document should capture knowledge that may benefit future contributors.

---

## How to create a new Research document

1. Copy `RESEARCH-0000-template.md`.
2. Rename the file using the next available number.
3. Replace the placeholder content with your investigation.
4. Reference the corresponding Research Issue whenever applicable.
5. Commit the completed Research document together with the related Research Issue whenever possible.

Example:

```text
RESEARCH-0001-evaluate-authentication-strategies.md

RESEARCH-0002-compare-testing-frameworks.md

RESEARCH-0003-evaluate-postgresql-indexes.md
```

---

## Naming Convention

Use the following format:

```text
RESEARCH-XXXX-short-description.md
```

Examples:

```text
RESEARCH-0001-evaluate-authentication-strategies.md

RESEARCH-0002-compare-testing-frameworks.md

RESEARCH-0003-investigate-caching-strategies.md
```

---

## Best Practices

- Keep Research documents concise and objective.
- Clearly describe the investigation.
- Record the alternatives that were evaluated.
- Document the conclusions reached.
- Reference related ADRs whenever applicable.
- Preserve Research documents as historical knowledge.

---

> 💡 **Engineering Tip**
>
> Code explains _how_ a system works.
>
> ADRs explain _why_ decisions were made.
>
> Research documents explain _how the team reached those decisions_.
