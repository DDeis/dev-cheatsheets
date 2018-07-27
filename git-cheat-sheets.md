# Git
## Config

```sh
git config --list
```

Rebase preserve by default when pulling:
```
git config --global pull.rebase preserve
```

Set editor:
```sh
git config --global core.editor "nano -w"
```

Create alias:
```sh
git config --global alias.tidy "rebase -i @{upstream}.."
```

## Branchs
Create branch
git checkout -b $branchname

git push origin $branchname --set-upstream
