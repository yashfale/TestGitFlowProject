# TestGitFlowProject
This is a TestGitFlowProject to learn the basic gitflow commands 

#Feature Branch commands : 

# create new feature branch 
git flow feature start [BranchName]
# make some changes and add the new changes 
git add .
# commit the latest changes 
git commit -m "type your msg here"


# some of the important commands 


#merge the existing branch in current branch
git merge --no-ff [BranchName]

#Revert the existing branch in current branch
git revert --no-edit [commitid]

# checked unmerged branches from master
git branch --no-merged master

# add tag name and push it to the remote
git tag [entertagNmae]
git push --tag 

# Change the git branch name 
git branch [new branch name] { Note : at the time of current branch }  

# if Parent git repo changed by some one then do the below things and push the existing repo branch 
git remote remove origin, 
git remote add origin <new_url> , 
git remote update ,
git push 

# delte tag from local and remote
git push --delete origin tagname
git tag --delete tagname





