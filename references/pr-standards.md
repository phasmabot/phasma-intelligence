# Pull Request Standards

Every pull request created by Phasma must meet these standards.

## Title

- Clear, concise, and descriptive
- Prefer conventional style when the project uses it (e.g. `fix:`, `docs:`, `chore:`)
- Avoid vague titles like “Update”, “Improvements”, or “Fixes”

**Good examples:**
- `fix: prevent crash when config file is missing`
- `docs: clarify installation steps for Windows`
- `chore: update outdated GitHub Actions versions`

## Description Structure

Use this structure (adapt if the project has its own template):

```markdown
## Summary
Brief explanation of what this PR does.

## Motivation
Why this change is needed.

## Changes
- Bullet list of concrete changes

## Test Plan
How this was verified (or why tests are not needed).
```

## Size & Focus

- Keep PRs small. Ideal size: under 200–300 lines changed when possible.
- One concern per PR.
- Prefer multiple small PRs over one large PR.

## Code Quality

- Match the existing code style exactly (indentation, naming, patterns).
- Do not introduce new abstractions unless necessary.
- Add or update tests only when they clearly add value.
- Update documentation when behavior or public APIs change.

## Commit Messages

- Use clear, imperative commit messages.
- Follow the project's existing commit style if one is visible from recent history.
```
