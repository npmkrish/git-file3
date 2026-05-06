# Git-GitHub Project

This project is created to practice basic Git and GitHub commands using files and folders inside Visual Studio Code.

## Project Structure

The project contains: #content

- `one/`
- `two/`
- `three/`
- `four/`
- `one.txt`
- `git-linux commands.pdf`
- `readme.md`

These files and folders are used for testing Git operations like add, commit, push, pull, and status checking.

## Git Commands Used

### Check Git Status

```bash
git status

#check git.status.dot

Checking Status #status
git status
git log
git log --oneline
git log --graph
git show
git diff
git diff --staged 



Adding Files
git add <file_name>
git add .
git add --all
git rm <file_name>
git rm --cached <file_name>
git mv old_name new_name



Commit Commands
git commit -m "commit message"
git commit -am "commit message"
git commit --amend



Branch Commands
git branch
git branch <branch_name>
git checkout <branch_name>
git checkout -b <branch_name>
git switch <branch_name>
git switch -c <branch_name>
git branch -d <branch_name>
git branch -D <branch_name>




Merge Commands
git merge <branch_name>
git merge --abort



Remote Repository Commands
git remote -v
git remote add origin <repository_url>
git remote remove origin
git remote rename origin new-origin



Push Commands
git push origin main
git push origin master
git push -u origin main
git push --all
git push --force


Pull and Fetch Commands
git pull
git pull origin main
git fetch
git fetch --all



Restore / Undo Commands
git restore <file_name>
git restore --staged <file_name>
git reset
git reset --soft HEAD~1
git reset --hard HEAD~1
git revert <commit_id>



Stash Commands
git stash
git stash list
git stash apply
git stash pop
git stash drop
git stash clear



Tag Commands
git tag
git tag <tag_name>
git tag -a <tag_name> -m "message"
git push origin <tag_name>
git push --tags



GitHub Helpful Commands
git clone <repo_url>
git pull origin main
git push origin main
git branch
git remote -v
Ignore Files

Create:

.gitignore

Example:

__pycache__/
*.pyc
.env
node_modules/
Advanced Commands
git cherry-pick <commit_id>
git rebase main
git rebase --continue
git rebase --abort
git blame <file_name>
git reflog
git clean -f
git clean -fd




SSH Commands for GitHub
ssh-keygen -t rsa -b 4096 -C "your@email.com"
cat ~/.ssh/id_rsa.pub
ssh -T git@github.com  




Useful Linux + Git Commands
pwd
ls
cd folder_name
mkdir folder_name
touch file_name
rm file_name
clear
Full Basic Workflow
git init
git status
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <repo_url>
git push -u origin main

and all set #!!!!!!!!!!