# Useful git commands

## Git basic configurations

```
$ git version
git version <major>.<minor>.<servicepack>.<os>.<num>
```

```
$ git config --global user.email "<email>"
set git email
```

```
$ git config --global user.name "<firstname> <lastname>"
set git user name
```

```
$ git config --global core.editor "<editor.exe> -multiInst -nosession"
display configurations
set core editor
```

```
$ git config --global --list
display global configurations
```

## Git repositories - Workflow

```
$ git init <project folder name>
initialize git repository
```

OR

```
$ git clone "<repository url>"
clone repository in folder
```

```
$ git status
display status of git repostory
```

```
$ git add "<filename>"
add changes of file in working directory to staging area
```

```
$ git add .
add all changes in working directory to staging area
```

```
$ git commit -m "<commit message>"
perform a commit with commit message
```

```
$ git push
push changes to repository
```
