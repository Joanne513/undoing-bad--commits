# undoing-bad--commits
## 1. git commit --amend -m""  (wrong commit message)
## 2. git checkout REAMDME.md  (wrong change to back to before the change)
## 3. git add .gitignore 
##    git commit --amend (left of a file to commit)
## 4. git log > copy the number >checkout feature-branch > git cherry-pick + 
## number> git checkout master branch> git reset --soft + last log 
## number（satgeinga area ）/--mixed+ last log number(before add to satging
## area)/--hard+ last log number(剩下untracked file) > git clean -df(we have
## to move this commit to other branch, because commit to the wrong
## branch)>git reflog> git checkout + lognumber > git log (on detached head
## stage)
## 5. 最后一个undo mistake