# Git Help
Helpful git commands

### Setup without `git clone`
1. `git init`
2. `git remote add origin <origin>`
3. `git branch set-upstream origin/master`

### Revert/reset X commits
`git revert/reset HEAD~X`

### Reset back to hash
`git reset --hard <hash>`

### Remove changes
`git checkout .`

### See untracked files
`git clean -n`

### Remove untracked files
`git clean -f`

### Clearing the local cache
`git rm -r --cached .`
