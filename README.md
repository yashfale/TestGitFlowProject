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





