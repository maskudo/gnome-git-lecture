---
title: Intermediate Git/Github
author: Manuj Babu Karki
theme:
  name: dark
---

# .gitignore

<!-- pause -->
<!-- incremental_lists: true -->

- When you dont want to store some files/folders in git
- e.g .env files, .exe files, large non text files, etc.
<!-- pause -->

## Ignoreing files

<!-- pause -->

- Create a .gitignore file
- put file/folder name (one per line)
- To ignore a pattern. e.g all .exe files `*.exe`

<!--end_slide-->

# Reverting chenges

<!-- pause -->

<!-- incremental_lists: true -->

- To undo a commit: `git revert <commit>`
- To reset a commit: `git reset HEAD~1 `, `git reset --hard HEAD~1`

<!-- pause -->

| Reset                                  | Revort               |
| -------------------------------------- | -------------------- |
| - Move the branch to a previous commit | Undo a commit        |
| - Doesn't create a new commit          | Creates a new commit |

<!--end_slide-->

# Restoreing deleted commits and branches

<!-- pause -->
<!-- incremental_lists: true -->

- Git doesn't truly delete commits
- See all recent actions: `git reflog`
- To restore a deleted commit `C1`: `git cherry-pick C1`
- To restore deleted branch `<branch>` : `git checkout -b <branch> C1`
<!--end_slide-->

# Adding files interactively

<!-- pause -->
<!-- incremental_lists: true -->

- You can add parts of a file to be staged interactively
- `git add -p`
<!--end_slide-->

# Reporeting issues and Requesting Features

- Report typos on this repo
- Improv documantation
