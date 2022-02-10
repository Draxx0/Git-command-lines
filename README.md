# Config git :

```bash
git config --global user.name "usename"
git config --global user.email "monEmail@gmail.com"
```

# Push modifications :

```bash
git add README.md
git commit -m "message"
git push
```

# Create branch :

```bash
git branch [name_of_your_new_branch]
||
git checkout -b [name_of_your_new_branch]

Push branch on github :
git push origin [name_of_your_new_branch]
```

# Delete branch :

```bash

Delete local branch :
git branch -d localBranchName

Delete GitHub branch :
git push origin --delete remoteBranchName
```

# Change branch :

```bash
git checkout [name_of_you_branch]
```

# Fetch branch :

```bash
git fetch
```

# Verify modifications :

```bash
git status
```

# Look all commits :

```bash
git log
git log --oneline
```

# Pull branch :

```bash
git pull [on_branch_which_be_pull]
```

# Merge branch :

```bash
git merge [name_of_branch_will_be_merge]

If no conflicts :
git push

If conflicts :
Resolve conflicts
git add .
git commit -m "resolve conflicts"
git push
```
