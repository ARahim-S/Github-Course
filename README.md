# Github-Course

For git you can use terminals like CMD,BASH,POWERSHELL etc. 

Settings
git config --global user.name "<username>"  (Global for current user)
git config --global user.email "<useremail>"

You may also use --system (for all users) || --local (for current folder) instead of global.

For reaching git information about your can write to terminal git config --list

If you create project at your own environment, you should use git init for adding your project to the local git environment.This should do once every project.


Commands
git add .
git add -m"version_1"
git status
git log
git log --oneline
git show <hash 7 character>
git restore . or git restore <file name>
git restore --staged . or git restore --staged <file name>
git reset --hard
git checkout<hash code><file name>
git checkout<hash code>. 
git reset --hard <hash code>

git branch <branch name>
git checkout <branch name>
git branch -d <branch name>
git branch -d .
git merge <branch name> 
git branch -m <branch new name>
git stash
git stash list
git stash pop

GITHUB
git clone
git push
git pull
git remote -v (for checking)
git remote add origin <github address>

FOR FIRST PUSH
git push -u origin <Branch name> || git push --set-upstream origin <Branch name>
after this action u will use always git push
.gitignore (for security issues)

Thats it. Good luck!


