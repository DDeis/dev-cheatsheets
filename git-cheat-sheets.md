# Git
## Config

```
git config --list
```

Rebase preserve by default when pulling:
```
git config --global pull.rebase preserve
```

Set editor:
```
git config --global core.editor "nano -w"
```

Create alias:
```
git config --global alias.tidy "rebase -i @{upstream}"
```

## Branchs
Create local branch:
```
git checkout -b $branchname
```
push new branch to remote:
```
git push origin $branchname --set-upstream
```

Delete remote branch:
```
git push origin :$branchname
````

List remotes:
```
git remote -v
```
Get branch from remote:
```
git fetch origin
git checkout --track origin/$branchname
```

fetch from all remotes:
```
git fetch --all
```
fetch and delete and remove any remote tracking branches which no longer exist on the remote:
```
git fetch --prune (-p)
```
