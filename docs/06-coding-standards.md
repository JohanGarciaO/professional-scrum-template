# Coding Standards

Define the coding principles and development conventions that ensure consistency, readability, and maintainability across the project.

---

## About this document

This document serves both as a learning guide and as a project template.

If this is your first time defining Coding Standards, read the explanatory sections before filling out the template.

Once you understand how to use it, feel free to remove the explanatory sections and keep only the completed Coding Standards for your project.

---

## Purpose

Coding Standards establish a shared set of conventions that guide how software is written throughout the project.

Their purpose is not to restrict developers, but to improve collaboration by making the codebase easier to read, review, maintain, and extend.

Consistent code reduces cognitive load, simplifies onboarding, and allows the team to focus on solving business problems instead of debating formatting or style preferences.

Whenever possible, coding conventions should be enforced automatically through linters, formatters, and static analysis tools.

---

## Who is responsible?

Coding Standards are defined collaboratively by the development team.

Every developer is responsible for following the agreed conventions and contributing to their continuous improvement.

The team should periodically review these standards as the project evolves.

---

## When should it be created?

Coding Standards should be established before development begins.

They should be reviewed whenever the team adopts new technologies, tools, or architectural practices.

Changes should be discussed collaboratively to maintain consistency across the codebase.

---

## How to define good Coding Standards

Focus on principles that improve code quality rather than personal preferences.

Whenever possible, prefer objective and enforceable conventions.

Typical Coding Standards include:

- Naming conventions.
- File and folder organization.
- Formatting rules.
- Error handling practices.
- Documentation guidelines.
- Testing expectations.
- Code review requirements.

Avoid creating rules that cannot be objectively verified or that provide little practical value.

---

## Template

### General Principles

- Write code that is easy to read before optimizing for brevity.
- Prefer simplicity over unnecessary complexity.
- Keep functions and classes focused on a single responsibility.

### Naming Conventions

- Use descriptive names.
- Follow the language's standard naming conventions.
- Avoid abbreviations unless they are widely recognized.

### Code Formatting

- Use an automatic code formatter whenever possible.
- Follow consistent indentation and spacing.
- Avoid manual formatting when tooling can enforce consistency.

### Documentation

- Document public APIs and complex business logic.
- Keep documentation synchronized with implementation.

### Error Handling

- Handle expected errors explicitly.
- Provide meaningful error messages.
- Avoid silently ignoring exceptions.

### Testing

- Every new feature should include appropriate tests.
- Existing tests should remain passing after changes.

### Code Review

- Every contribution should be reviewed before being merged.
- Review readability, maintainability, correctness, and adherence to project standards.

---

## Example

### General Principles

- Prioritize readability over clever solutions.
- Apply the Single Responsibility Principle whenever appropriate.
- Prefer composition over unnecessary inheritance.

### Naming Conventions

- Classes use PascalCase.
- Functions use camelCase.
- Constants use UPPER_SNAKE_CASE.

### Code Formatting

- Formatting is enforced automatically using Prettier.
- Linting is enforced through ESLint.

### Documentation

- Public functions include documentation comments.
- Business rules are documented when implementation alone is insufficient.

### Error Handling

- Exceptions include meaningful messages.
- Errors are logged when appropriate.

### Testing

- New features require unit tests.
- Critical workflows require integration tests.

### Code Review

- Every Pull Request requires at least one approval before merging.

---

## Common Mistakes

### ❌ Confusing Coding Standards with personal preferences

Bad:

> Always use my preferred code style.

Good:

> Follow conventions agreed upon by the entire team.

---

### ❌ Creating rules that cannot be enforced

Bad:

> Write beautiful code.

Good:

> Use the project's formatter and linting tools.

---

### ❌ Allowing inconsistent patterns

Bad:

> Different naming conventions across the same project.

Good:

> Apply naming conventions consistently throughout the codebase.

---

## References

- Robert C. Martin. _Clean Code._
- Robert C. Martin. _Clean Architecture._
- Steve McConnell. _Code Complete._
- Martin Fowler. _Refactoring._

---

> 💡 **Engineering Tip**
>
> Good developers write code that computers can execute.
>
> Great developers write code that other developers can understand.
