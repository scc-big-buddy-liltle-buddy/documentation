# Git Branch Naming Convention

Thanks for tutorial article from [Git Branch Naming Conventions](https://graphite.dev/guides/git-branch-naming-conventions) that we apply in our projet at Saigonchildren M2M version control system.

## Git branch name restrictions

- Characters: Branch names can include letters, numbers, dashes (-), underscores (\_), and dots (.), but they cannot begin with a dot or end with a slash (/).
- Case sensitivity: Git is case-sensitive, so Feature and feature are considered different branches.
- Reserved names: Names like HEAD, FETCH_HEAD, ORIG_HEAD, and others are reserved by Git and cannot be used as branch names.
- Length: While there's no strict limit on the length of branch names, it's practical to keep them concise to make them easier to manage.

## Git branch prefixes

We use the stratedy to categorize branches based on their purpose:

- Feature branches: Prefixed with feature/, these branches are used to develop new features.
- Bugfix branches: Prefixed with bugfix/, these branches are used to make fixes.
- Release branches: Prefixed with release/, these branches prepare a codebase for new releases.
- Hotfix branches: Prefixed with hotfix/, these branches address urgent issues in production.

## Git Flow branch naming conventions

Git Flow is a branching model that outlines a strict branching strategy designed for managing releases. The main branches in Git Flow include:

- Main branch: Serves as the primary branch where the codebase's current production state is reflected.
- Develop branch: Aggregates developments and features before they are released to the main branch.
- Feature branches: Typically follow the naming pattern feature/\*, these branches are used to develop new features.
- Release branches: Named like release/\*, these branches help manage the release process.
- Hotfix branches: Named hotfix/\*, these branches are created to quickly patch production releases.
