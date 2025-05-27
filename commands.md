
# Git Configuration Commands

## Set User Name and Email

```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Set Default Editor
```sh
git config --global core.editor "code --wait"
```

## Check Configuration
```sh
git config --list
```

## Set Default Branch Name
```sh
git config --global init.defaultBranch main
```

## Stage all files/changes
```sh
git add .
```

```sh
git status
```

## Add/create a snapshot of the changes/files to the local repository
```sh
git commit -m "message"
```

## Push the Local Repository to the Remote Repository
```sh
git push -u origin main
```

