# Github-Course

For git you can use terminals like CMD,BASH,POWERSHELL etc. 

Settings
git config --global user.name "<username>"  (Global for current user)
git config --global user.email "<useremail>"

You may also use --system (for all users) || --local (for current folder) instead of global.

For reaching git information about your can write to terminal git config --list

If you create project at your own environment, you should use git init for adding your project to the local git environment.This should do once every project.


Commands <br />
git add . <br />
git commit -m"version_1" <br />
git status <br />
git log <br />
git log --oneline <br />
git show <hash 7 character> <br />
git restore . or git restore <file name> <br />
git restore --staged . or git restore --staged <file name> <br />
git reset --hard <br />
git checkout<hash code><file name> <br />
git checkout<hash code>. <br />
git reset --hard <hash code> <br />

git branch <branch name> <br />
git checkout <branch name> <br />
git branch -d <branch name> <br />
git branch -d . <br />
git merge <branch name> <br />
git branch -m <branch new name> <br />
git stash <br /> 
git stash list <br />
git stash pop <br />

GITHUB <br />
git clone <br />
git push <br />
git pull <br />
git remote -v (for checking) <br />
git remote add origin <github address> <br />

FOR FIRST PUSH <br />
git push -u origin <Branch name> || git push --set-upstream origin <Branch name> <br />
after this action u will use always git push <br />
.gitignore (for security issues) <br />

Thats it. Good luck!<br />


