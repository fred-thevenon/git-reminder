# Git Command Toolbox

# Create a new branch and checkout
```bash
git checkout -b nom-de-la-nouvelle-branche 
```
# Delete branch

Local branch
```bash
git branch -d feat/12345-ma-super-feature
```

Remote branch
```bash
git push origin --delete feat/12345-ma-super-feature
```

# Show email from config in repository

```bash
git config --show-origin --get user.email
```

# Merge without commi merge

```bash
git merge feat/12345-ma-super-feature --no-ff
```