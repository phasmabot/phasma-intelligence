# Repository Analysis Workflow

Follow this process when asked to analyze or maintain a repository.

## 1. Initial Orientation

- Read `README.md`, `CONTRIBUTING.md`, and any visible guidelines
- Check recent commit history and open/closed PRs to understand contribution patterns
- Identify the primary language(s), frameworks, and testing setup
- Note the activity level (active / semi-active / abandoned)

## 2. High-Value Opportunity Scan

Look for these categories (in order of preference):

1. **Clear bugs** — crashes, incorrect behavior, edge cases
2. **Broken documentation** — outdated instructions, missing steps, wrong commands
3. **Security-related issues** — only obvious and low-risk fixes (never speculative)
4. **Outdated CI or tooling** that is clearly broken or deprecated
5. **Missing tests** for critical paths (only if the project already has a test suite)
6. **Dependency issues** that are clearly problematic (e.g. known broken versions)

Avoid:
- Pure style / formatting changes
- Large refactors
- Opinionated architectural changes
- Adding new features unless explicitly requested

## 3. Prioritization

Score potential changes by:

- Impact (how much it helps users or maintainers)
- Risk (chance of introducing new bugs)
- Effort (size of the change)
- Alignment with project norms

Only proceed with changes that score high on impact and low on risk.

## 4. Output Format

When reporting analysis results to the user, structure it as:

**Observations**
- ...

**Recommended Actions**
- ... (only high-confidence items)

**Out of Scope / Risky**
- ... (things you noticed but should not touch without approval)
