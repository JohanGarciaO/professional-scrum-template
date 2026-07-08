# Git Strategy

Define the branching model, commit conventions, and collaboration workflow used throughout the project.

---

## About this document

This document serves both as a learning guide and as a project template.

If this is your first time defining a Git Strategy, read the explanatory sections before filling out the template.

Once you understand how to use it, feel free to remove the explanatory sections and keep only the completed Git Strategy for your project.

---

## Purpose

A Git Strategy establishes a consistent workflow for managing source code throughout the project's lifecycle.

Its purpose is to improve collaboration, maintain a clean commit history, and reduce integration conflicts by defining clear rules for branching, committing, reviewing, and merging code.

A well-defined Git Strategy allows every contributor to understand how changes should be proposed, reviewed, and integrated into the project.

---

## Who is responsible?

The Git Strategy is defined collaboratively by the development team.

Every contributor is responsible for following the agreed workflow and keeping the repository history clean and consistent.

Changes to the Git Strategy should be discussed and approved by the team.

---

## When should it be created?

The Git Strategy should be established before development begins.

It should be reviewed whenever the team's workflow changes or the project reaches a level of complexity that requires adjustments to the branching model or collaboration process.

---

## How to define a good Git Strategy

A good Git Strategy should answer the following questions:

- Which branching model will be used?
- How should branches be named?
- What commit message convention should contributors follow?
- When should Pull Requests be created?
- Who is responsible for reviewing changes?
- Under which conditions can code be merged?

Whenever possible, automate repository policies using branch protection rules, status checks, and continuous integration.

---

## Template

### Branching Strategy

> Describe the branching model used by the project.

### Branch Naming Convention

> Define how feature, bugfix, hotfix, and release branches should be named.

### Commit Convention

> Describe the commit message convention adopted by the project.

### Pull Requests

> Define when Pull Requests are required and the minimum approval criteria.

### Merge Strategy

> Specify the merge strategy adopted by the repository.

### Protected Branches

> List the branches protected against direct commits.

---

## Example

### Branching Strategy

The project follows a simplified GitHub Flow.

Development starts from the `main` branch through short-lived feature branches.

### Branch Naming Convention

- `feature/user-authentication`
- `feature/pdf-generation`
- `bugfix/login-validation`
- `hotfix/security-patch`
- `docs/update-readme`

### Commit Convention

The project follows the Conventional Commits specification.

Examples:

- `feat: add Google authentication`
- `fix: validate expired session tokens`
- `docs: update Product Vision`
- `refactor: simplify authentication service`

### Pull Requests

- Every code change must be submitted through a Pull Request.
- At least one approval is required before merging.
- All automated checks must pass successfully.

### Merge Strategy

Use **Squash and Merge** to keep the commit history concise and easy to understand.

### Protected Branches

- `main`

Direct commits are not allowed.

---

## Common Mistakes

### ❌ Working directly on the main branch

Bad:

> Commit directly to `main`.

Good:

> Create a feature branch and submit a Pull Request.

---

### ❌ Writing unclear commit messages

Bad:

> Update.

> Fix.

> Changes.

Good:

> feat: implement Google authentication

---

### ❌ Merging unreviewed code

Bad:

> Merge immediately after pushing commits.

Good:

> Wait for code review and successful automated checks before merging.

---

## References

- Chacon, S.; Straub, B. _Pro Git._
- Conventional Commits Specification.
- GitHub Docs – About Pull Requests.
- GitHub Docs – Branch Protection Rules.

---

> 💡 **Engineering Tip**
>
> Your Git history is part of your project's documentation.
>
> A clean, consistent commit history makes it easier to understand how the software evolved over time.
