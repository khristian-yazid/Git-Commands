# Git-Commands
Basic Commands of Git

# Configure Git User Environment

## configure user name 

```bash
git config --global user.name "username"
```

## Configure Email

```bash
git config --global user.email dasdo1@gmail.com
```

# Git Basic Commands

## initialize repository

```bash
git init
```
# Git-add Adds The Files To The Staging

## add all files to staging

```bash
git add .
```

## add file to staging

```bash
git add <file>
```

## add files to staging skipping the new files 

```bash
git add --all 
```

## add file to this extension

```bash
git add *.txt
```

## add files from this directory

```bash
git add docs/
```

## add files from this directory and this extension

```bash
git add docs/*.txt
```

# Git-commit confirm changes to the files

## confirm file to repository

```bash 
git commit -m "description of commit"
```

## add files and confirm files

```bash
git commit -am "description of commit"
```
## show conflicts

```bash
git commit -a 
```