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
add changes of filename in working directory to staging area
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

## Create new repository on commandline

```
$ git init
initialize git repository
```

```
$ git add README.md
add changes of README.md in working directory to staging area
```

```
$ git commit -m "<commit message>"
perform a commit with commit message
```

```
$ git branch -M main
move master branch to main
```

```
$ git remote add origin https://github.com/<user>/<repo-name>.git
add local repo to remote one
```

```
$ git push -u origin main
push the commits in the local branch named master to the remote named origin
```
