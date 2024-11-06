# Add files to the staging area
```
git add <file>  
git add .
```
# Commit changes to the repository
```
git commit -m "Initial commit"
git commit -a -m "Initial commit"  # Add all changes, then commit. For changed files only.
```


# Push changes to a remote repository
```
git push origin branch-name
git push origin --force
```


# Pull changes from a remote repository
```
git pull origin branch-name
```



# Discard changes in a file
```
git checkout -- file-name
```

# Revert to a previous commit
```
git revert commit-hash
```

# Remove a file from the repository
```
git rm file-name
```

# Reset the repository to a previous commit
```
git reset --hard commit-hash
git reset --hard HEAD~1  # Reset to the previous commit
git reset --hard HEAD~2  # Reset to the commit before the previous commit
git reset --soft
git reset --mixed # default
```

git remote -v