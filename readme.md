https://www.w3schools.com/git/git_branch.asp?remote=github

# basic 
git --version
git config user.name
git status 

# staging 
git add index.html
git add --all

# commit 
git commit -m "init"
# staging all and commit in one go
git commit -a -m "again" 

# commit history
git log

# help
git commit -help
git help --all

# branch
git branch new_branch_name

# create branch and checkout in one go 
git checkout -b new_branch_name 

# list all branches
git branch 

# checkout to another branch
git checkout new_branch_name

# github 
git remote add origin https://github.com/ZhengGong-hub/learngh.git
git push --set-upstream origin master 

# show difference 
git diff origin/master

# pull = fetch + merge 
# fetch  # what is happening on gh
git fetch origin

git merge origin/master
