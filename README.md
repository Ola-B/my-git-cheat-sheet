# my-git-cheat-sheet
Simple git

## Clone
To clone a repo:
```git clone https://github.com/Ola-B/my-git-cheat-sheet.git```

## Add new file
To track a new file:
```git add <filename>```
```git add -a```

## Status
```git status```

## Commit changes
```git commit -m "commit message"```
To stage and commit at same time:
```git commit -a -m "commit message"```

## Branch
To create a new branch:
```git branch <branch-name>```
Use
```git log```
to see what branches there is and where "HEAD" is.
To switch branch:
```git checkout <branch-name>```
To create new branch and checkout in one go
```git checkout -b <newbranchname>```
To see tree of branch:
```git log --oneline --decorate --graph --all```

To merge the branch and the master, first go to the master branch you want to merge into:
```git checkout master```
Then merge the branch with the master:
```git merge <name-of-branch>```
To delete the branch:
```git branch -d <branch-name>```