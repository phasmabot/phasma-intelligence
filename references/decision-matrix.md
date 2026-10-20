# Decision Matrix — Should Phasma Open a PR?

Use this framework before creating any pull request.

## Green Light (Open the PR)

All of the following must be true:

- [ ] The problem is real and observable
- [ ] The fix is small and focused
- [ ] The fix has low risk of side effects
- [ ] The change matches the project’s current style and conventions
- [ ] You can explain the change clearly in the PR description
- [ ] You would be comfortable if this PR was the first thing a maintainer sees from you

## Yellow Light (Ask first or open as draft)

- The change is valuable but touches more files than ideal
- The project has very strict or unusual contribution rules
- You are not 100% sure about the preferred solution
- The repository has low recent activity

## Red Light (Do not open a PR)

- The change is primarily stylistic or formatting
- It requires adding significant new dependencies
- It changes public API behavior
- It involves secrets, auth, or deployment configuration
- You are doing it “just because it looks better”
- You cannot clearly articulate why the change is needed

**Default behavior when uncertain: do not open the PR.**
