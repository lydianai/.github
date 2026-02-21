# Contributing

Thank you for your interest in contributing. Most repositories under this account are proprietary software. Please read this guide before submitting any contributions.

## Proprietary Repositories

Repositories without an open-source license (e.g., `borsa`, `Payream`) are **proprietary**. By submitting a pull request to a proprietary repository, you agree that:

1. Your contribution becomes the property of the repository owner.
2. You grant a perpetual, worldwide, royalty-free license to use, modify, and distribute your contribution.
3. You have the right to submit the contribution and it does not violate any third-party rights.

## Open-Source Repositories

Repositories with an explicit open-source license (e.g., `newsai-earth` under MIT) accept contributions under the terms of that license.

## How to Contribute

### Reporting Bugs

1. Check existing issues to avoid duplicates.
2. Use the **Bug Report** issue template.
3. Include steps to reproduce, expected behavior, and actual behavior.
4. Add screenshots or logs if applicable.

### Suggesting Features

1. Use the **Feature Request** issue template.
2. Describe the problem the feature would solve.
3. Propose a solution if you have one.

### Submitting Code

1. Fork the repository.
2. Create a feature branch from `main`: `git checkout -b feature/your-feature`
3. Write tests for your changes.
4. Ensure all tests pass: `npm test` or the equivalent.
5. Follow existing code style and conventions.
6. Sign your commits (GPG or SSH signing required).
7. Submit a pull request with a clear description.

### Commit Messages

Follow conventional commit format:

```
type(scope): short description

Longer description if needed.
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, `perf`, `ci`

### Code Standards

- TypeScript: strict mode, no `any` types
- Tests: minimum 80% coverage for new code
- Security: no hardcoded secrets, validate all inputs
- Linting: zero warnings before submitting

## Code Review

All pull requests require at least one review before merging. Reviews focus on:

- Correctness and logic
- Security implications
- Test coverage
- Performance impact
- Code readability

## Security Issues

**Do NOT open public issues for security vulnerabilities.** See [SECURITY.md](SECURITY.md) for responsible disclosure instructions.
