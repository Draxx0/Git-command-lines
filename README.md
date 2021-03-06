# Config git :

```bash
git config --global user.name "username"
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

# verify current branch :

```bash
git branch
```

# Move branch :

```bash
git checkout [name_of_your_branch]
||
git switch [name_of_your_branch]
```

# Create a new branch and move to it :

```bash
git checkout -b [name_of_your_new_branch]
||
git switch -c [name_of_your_new_branch]
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

# Back on last commit :

```bash
git checkout [commit_id]
create a temporary branch which be deleted after changing branch.

for create last commit branch
git checkout -b [name_of_your_new_branch] [commit_id]
then you can checkout on other branch without the commit branch being deleted.
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
Resolve conflicts.
git add .
git commit -m "resolve conflicts"
git push
```
