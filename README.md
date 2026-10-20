<p align="center">
  <img src="https://i.imgur.com/JPYTVi6.jpeg" alt="Phasma Intelligence" width="140" />
</p>

<h1 align="center">Phasma Intelligence</h1>

<p align="center">
  <strong>Autonomous open-source maintainer</strong><br>
  Watches repositories · Opens high-quality PRs · Sustains itself
</p>

<p align="center">
  <a href="https://x.com/phasmalabs">Twitter / X</a> ·
  <a href="https://github.com/phasmabot/phasma-intelligence">GitHub</a>
</p>

---

## Overview

Phasma is a self-sustaining AI agent built to maintain open-source repositories.

It monitors projects, identifies real issues, and submits focused, high-quality pull requests — while remaining quiet and respectful of existing maintainers and contribution norms.

The goal is simple: reduce maintenance debt without creating noise.

## Key Principles

- **Quality over quantity** — One excellent PR is better than many mediocre ones
- **Minimum viable change** — Smallest correct fix preferred
- **Respect the project** — Follow existing style, conventions, and guidelines
- **Safety first** — Strict rules against force-pushes, secrets, and breaking changes
- **No noise** — If the value is unclear, Phasma does not act

## Install as Bankr Skill

```text
install the phasma skill from https://github.com/phasmabot/phasma-intelligence
```

## Repository Structure

```text
phasma-intelligence/
├── SKILL.md                  # Core agent instructions
├── catalog.json              # Bankr catalog metadata
├── logo.png                  # Official logo
├── references/               # Detailed workflows & safety rules
│   ├── safety.md
│   ├── pr-standards.md
│   ├── analysis-workflow.md
│   ├── decision-matrix.md
│   └── examples.md
└── templates/                # PR & commit templates
    ├── pr-body.md
    ├── commit-message.md
    └── issue-comment.md
```

## Safety

Phasma operates under strict safety constraints documented in `references/safety.md`.

It will never:
- Force-push to protected branches
- Touch secrets or credentials
- Open low-value or purely stylistic pull requests
- Make breaking changes without explicit approval

## Links

- **X**: [phasmalabs](https://x.com/phasmalabs)
- **Repository**: [phasmabot/phasma-intelligence](https://github.com/phasmabot/phasma-intelligence)

---

<p align="center">
  <sub>Built in the shadows.</sub>
</p>
```
