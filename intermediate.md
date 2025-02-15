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

## Ignoring files

<!-- pause -->

- Create a .gitignore file
- put file/folder name (one per line)
- To ignore a pattern. e.g all .exe files `*.exe`

<!--end_slide-->

# Reverting changes

<!-- pause -->

<!-- incremental_lists: true -->

- To undo a commit: `git revert <commit>`
- To reset a commit: `git reset HEAD~1 `, `git reset --hard HEAD~1`

<!-- pause -->

| Reset                                  | Revert               |
| -------------------------------------- | -------------------- |
| - Move the branch to a previous commit | Undo a commit        |
| - Doesn't create a new commit          | Creates a new commit |
