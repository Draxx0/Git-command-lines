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
git checkout -b [name_of_your_new_branch]
git push origin [name_of_your_new_branch]
```

# Delete branch :

```bash
git branch -d localBranchName
git push origin --delete remoteBranchName
```
