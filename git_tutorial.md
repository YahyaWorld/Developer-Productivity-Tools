# GIT

## basics
* git init 
* git clone <repo_url>
* git add .
* git commit -m"hello"
* git status
* git log
* git log --oneline

---
## remote
* git remote add origin <repo_url> 
* git remote -v
* git push origin main
* git push origin main --force
* git pull origin main
---
## branch
* git branch -M main :set default branch name as main
* git branch :list all branches
* git branch <branch_name> :create new branch
* git branch <branch_name> <commit_hash> :create new branch from specific commit
* git checkout <branch_name> :switch to another branch
* git merge <branch_name> :merge specific branch to current branch
* git branch -d <branch_name> :delete branch locally
---
## version_control
* git reset <file_name> :unstage added file
* git reset --soft <commit_hash> :move head to specific commit keeping changes staged
* git reset --hard <commit_hash> :move the head to specific commit by discarding all changes
* git revert <commit_hash> :create new commit to undo a specific commit
