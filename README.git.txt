GitHub

--Git Bash
cd /mnt/d

https://github.com/hesbornO/undergradProject_frontEnd.git
https://github.com/hesbornO/undergradProject_backEnd.git

1. Backend
csc/CSC_416_Project/Project

2. Frontend 
xampp/htdocs/project
git remote add origin https://github.com/hesbornO/project_frontend.git

$ git config --global user.name "hesborn"
$ git config --global user.email "oswago54@gmail.com"

navigate to project directory
cd /d/csc/csc_416_project/project/workspace/fabric-dev-servers

$ git init

$ git add .
# Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.

$ git commit -m "First commit"
# Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.

$ git remote add origin https://github.com/hesbornO/Project.git
# Sets the new remote
$ git remote -v
# Verifies the new remote URL

$ git push origin master
# Pushes the changes in your local repository up to the remote repository you specified as the origin


####
BRANCH MANAGEMENT
####


// SWITCHING BRANCHES

git branch branch_name    ;;create new branch

git checkout branch_name   ;switch to new brach



git merge master

press i,type commit message, ESC , :wq

//deleting a branch
git branch -d <branch>

//ADDING REMOTE REPOSITORY

git init 
git commit -m 'commit message'
git remote add origin https://github.com/hesbornO/fb_andela.git
git push -u origin master


//REMOVING FILE FROM GIT REPO BUT NOT LOCAL DIR
git rm --cached filename.ext

//LIST FILES
git ls-files

//EXIT LOG
q

//
master - production
branch - staging
//remove staged files
git rm --cached -r .

// git remove remote origin
git remote remove origin

OR
git remote set-url origin git://new.url.here



#######BRANCHING######### 
https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches
