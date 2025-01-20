# branches-and-commits
Help-files for conventional commits and branch-naming

## Conventional commit

Types:
- API relevant changes
- feat Commits, that adds or remove a new feature
- fix Commits, that fixes a bug
- refactor Commits, that rewrite/restructure your code, however does not change any API behaviour
- perf Commits are special refactor commits, that improve performance
- style Commits, that do not affect the meaning (white-space, formatting, missing semi-colons, etc)
- test Commits, that add missing tests or correcting existing tests
- docs Commits, that affect documentation only
- build Commits, that affect build components like build tool, ci pipeline, dependencies, project version, ...
- ops Commits, that affect operational components like infrastructure, deployment, backup, recovery, ...
- chore Miscellaneous commits e.g. modifying .gitignore

- Exempel på commit: "feat(shopping cart): add the amazing button"

## Create branches

Use appropiate prefix and describe the purpose of the branchens

Exampel--> "feature/add-user-authentication"

- feature/: För nya funktioner eller förbättringar.
- bugfix/: För att fixa buggar.
- hotfix/: För akuta ändringar i produktion.
- experiment/: För att testa idéer eller nya tekniker.
- chore/: För underhåll eller ändringar som inte påverkar funktionaliteten, som uppdateringar av dependencies eller dokumentation.
- release/: För att förbereda en release.
