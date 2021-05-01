# Git-Commands
Basic Commands of Git

## Configure Git User Environment

configure user name 

```bash
git config --global user.name "username"
```

Configure Email

```bash
git config --global user.email dasdo1@gmail.com
```

## Git Basic Commands

initialize repository

```bash
git init
```
## Git-add

add all files to staging

```bash
git add .
```

add file to staging

```bash
git add <file>
```

add files to staging skipping the new files 

```bash
git add --all 
```

add file to this extension

```bash
git add *.txt
```

add files from this directory

```bash
git add docs/
```

add files from this directory and this extension

```bash
git add docs/*.txt
```

## Git-commit

confirm file to repository

```bash 
git commit -m "description of commit"
```

add files and confirm files

```bash
git commit -am "description of commit"
```
show conflicts

```bash
git commit -a 
```

## Git-log

show logs of the commits

```bash
git log
```

show the changes in the commits

```bash
git log --oneline --stat
```

show graphic decorated of the commits

```bash
git log --oneline --graph
```

## Git-diff 

show changes in files

```bash
git diff
git diff --staged
```

## Git-reset 

pull file from commit

```bash
git reset HEAD <archivo>
```
return the last commit and places it in staging

```bash
git reset --soft HEAD^
```

return the last commit and all 

```bash
git reset --hard HEAD^^
```

