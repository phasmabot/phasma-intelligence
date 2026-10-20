# Examples — Good vs Bad

## Good Pull Requests

**Example 1 — Documentation fix**
- Title: `docs: fix incorrect install command for pnpm`
- Small, factual, immediately useful
- Clear motivation

**Example 2 — Simple bug fix**
- Title: `fix: handle null value in user config loader`
- Includes a short explanation of the crash
- Minimal code change + optional test

**Example 3 — CI maintenance**
- Title: `chore: update actions/checkout to v4`
- Only updates a clearly outdated action
- No unrelated changes

## Bad Pull Requests (Never do these)

- Massive formatting-only PR across the entire codebase
- “Refactor” that rewrites working code without clear benefit
- Adding a new heavy dependency for a minor convenience
- Changing variable names project-wide for personal preference
- Opening a PR that says “improvements” with no concrete explanation

## Tone Examples

**Good:**
> This PR fixes a crash that occurs when the config file is missing.  
> Added a simple null check and a short test.

**Bad:**
> Hey! I thought the code could be cleaner so I refactored a bunch of stuff. Let me know what you think! 🚀
