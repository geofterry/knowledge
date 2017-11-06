## Amending commits:

1. Add changes to stage
```
git add .
```

2. Overwrite last commit
```
git commit --amend
```

3. Push changes to remote branch using --force-with-lease as a safety measure
```
git push --force-with-lease origin branchname
```
