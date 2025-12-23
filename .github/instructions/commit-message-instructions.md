---
name: Commit Message Standards
description: Enforce Conventional Commits format for all commit messages
applyTo: '**'
---

# GitHub Copilot Instructions

## Commit Message Standards

### Use Conventional Commits

All commit messages MUST follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

**Format:**

```text
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Required Commit Types:**

- `feat`: New feature
  - For this repo: New evidence documents or significant content additions to existing evidence
  - The documentation IS the product - new evidence documents are features
- `fix`: Bug fix
  - For this repo: Corrections to factual errors, broken citations, or formatting issues in evidence documents
- `docs`: Documentation changes
  - For this repo: Changes to meta-documentation (README, CONTRIBUTING, CODE_OF_CONDUCT)
  - NOT for evidence documents - those are `feat` or `fix`
- `style`: Code style/formatting (no logic changes)
- `refactor`: Code restructuring (no feature/bug changes)
  - For this repo: Reorganizing evidence structure or renaming files without changing content
- `perf`: Performance improvements
- `test`: Adding or updating tests
- `build`: Build system or dependencies
- `ci`: CI/CD configuration changes
- `chore`: Other changes (tooling, maintenance)

**Breaking Changes:**

- Use `!` after type/scope: `feat!:` or `feat(api)!:`
- OR add `BREAKING CHANGE:` footer

**Examples:**

```text
feat(auth): add user login
fix: resolve null pointer in parser
docs: update README
refactor(api)!: remove deprecated endpoints

BREAKING CHANGE: removes v1 API support
```

**Evidence Repository Examples:**

```text
feat(supplements): add bromelain evidence for oral surgery
feat(hormones): add progesterone post-FFS sodium effects
fix(supplements): correct zinc dosage recommendations
fix(diet): update caffeine study citation
docs: clarify contribution guidelines
refactor(supplements): reorganize vitamin documents by category
```

### Commit Message Style

- **Be concise**: Keep descriptions under 50 characters when possible
- **Use imperative mood**: "add" not "added" or "adds"
- **No period at end**: Description should not end with `.`
- **Lowercase description**: Start description with lowercase letter
- **No capitalization**: Type and scope are lowercase
- **Skip body if obvious**: Only add body for complex changes
- **One change per commit**: Each commit should represent one logical change

**Good:**

```text
feat: add password reset functionality
fix: prevent memory leak in cache
docs: clarify API authentication
```

**Bad:**

```text
Added new feature for passwords.
FIX: Fixed the bug
feat: Add, update, and refactor entire authentication system
```
