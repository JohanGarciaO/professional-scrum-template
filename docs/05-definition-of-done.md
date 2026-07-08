# Definition of Done (DoD)

Define the minimum quality standards that every Product Backlog Item must satisfy before being considered complete.

---

## About this document

This document serves both as a learning guide and as a project template.

If this is your first time creating a Definition of Done (DoD), read the explanatory sections before filling out the template.

Once you understand how to use it, feel free to remove the explanatory sections and keep only the completed Definition of Done for your project.

---

## Purpose

The Definition of Done (DoD) establishes the quality standards that every Product Backlog Item must satisfy before it can be considered complete.

Its primary purpose is to create a shared understanding of what "Done" means for the Scrum Team.

By defining objective completion criteria, the DoD improves transparency, reduces misunderstandings, and ensures that every Increment meets an agreed level of quality.

Unlike the Definition of Ready (DoR), which determines whether work is ready to begin, the Definition of Done determines whether work is truly finished.

---

## Who is responsible?

The Definition of Done is created and maintained collaboratively by the Scrum Team.

Every team member is responsible for ensuring that all agreed criteria have been satisfied before marking work as completed.

The Scrum Team should review and improve the DoD as its development practices evolve.

---

## When should it be created?

The Definition of Done should be established at the beginning of the project.

It should be reviewed periodically whenever the team's quality standards or development process change.

The DoD is applied continuously throughout the project whenever a Product Backlog Item reaches completion.

---

## How to define a good Definition of Done

A good Definition of Done should contain objective, measurable, and verifiable quality criteria.

Every completed Product Backlog Item should satisfy every criterion without exception.

Avoid including project-specific implementation details that only apply to a single feature.

Instead, define standards that represent the expected quality level for every deliverable.

Typical completion criteria include:

- Code has been reviewed.
- Automated tests are passing.
- Documentation has been updated.
- No critical defects remain.
- Acceptance Criteria have been satisfied.
- The Increment is potentially releasable.

---

## Template

A Product Backlog Item is considered **Done** when:

- [ ] All Acceptance Criteria have been satisfied.
- [ ] Code has been reviewed.
- [ ] Automated tests are passing.
- [ ] No critical defects remain.
- [ ] Documentation has been updated.
- [ ] Code follows the project's coding standards.
- [ ] The solution has been integrated successfully.
- [ ] The Product Owner accepts the completed work.

---

## Example

### Product Backlog Item

> Implement Google Authentication.

### Done Checklist

- ☑ All Acceptance Criteria satisfied.
- ☑ Code reviewed through Pull Request.
- ☑ Unit tests passing.
- ☑ Integration tests passing.
- ☑ Documentation updated.
- ☑ ESLint reports no errors.
- ☑ Feature successfully deployed to the staging environment.
- ☑ Product Owner approved the implementation.

Result:

> ✅ This Product Backlog Item satisfies the Definition of Done and can be considered complete.

---

## Common Mistakes

### ❌ Treating development completion as product completion

Bad:

> The feature works on my machine.

Good:

> The feature satisfies every criterion defined in the Definition of Done.

---

### ❌ Using subjective criteria

Bad:

> The code looks good.

Good:

> Code review completed and approved.

---

### ❌ Skipping quality checks under schedule pressure

Bad:

> We'll update the documentation later.

Good:

> Documentation is updated before the Product Backlog Item is considered Done.

---

## References

- Schwaber, K.; Sutherland, J. _The Scrum Guide._
- Martin, R. C. _Clean Agile._
- McConnell, S. _Code Complete._

---

> 💡 **Engineering Tip**
>
> "Done" is not a feeling—it is an agreement.
>
> A Product Backlog Item is either Done or it is not. There is no such thing as "90% Done."
