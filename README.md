# GIT-Course
This is git course from FreeCodeCamp.

git --version : to check whether git is installed or to know the version of git.

git clone [repo url https/ssh/github cli] : to clone the existing repository from github.

git status : show modified or updated file in working directory, staged for your next commit.

git add [file_name] : add a untracked file to the git as it looks now ( we can use ".(period)" to add all files ).

git commit -m ["Initial Commit"]  -m ["Initial Commit Description"] : to save the changes of files locally.

git push : to push code into the remote repository (git push origin master: to push code to the master branch).

# Configuring SSH key in GITHUB
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

# Initializing empty repository and pushing it to github
git init: to initialize empty repository locally on your system.

git remote add origin [github url] : to add or make a connection to the remote repository to add local changes into it.

git remote -v : to show the remote repository which we are connected to.

# git branch

git branch : to know the current branch on which working on or list of all branches.

git checkout -b [new_branch_name] : to create new branch using the existing branch or main branch.

git checkout [branch_name] : to checkout between the branches present.

git push --set-upstream origin [branch_name] : to publish the branch in github or to set upstream with the main branch. we can use --set-upstream or -u in the command.

# pull merge file

git diff [branch_name] : to know the commited changes in the branch.

git merge [branch_name] : to merge the specific changes into the current one.

git pull / git pull origin main : to pull the updated code from the main branch or merged code.

# undoing changes in git

git log : to know all the staged or commited changes.

git reset : to know the last change to undo it. we can also add 'filename' to undo changes or use rest command.

git reset HEAD~1 : to reset or undo last commit which is staged.

git reset [hash key of commit] : this command is used to undo or unstage all the commits till the hash key.

git reset --hard[hash key of commit] : to remove or delete all the commits till the last HASH KEY permanently.

# deleting branch in git

git rm [branch-name/file-name] : to remove or delete branch or file from local or remote repository.

# forking
It is done using the UI interface to get the copy of other repository into your code or repository.

# Welcome to GitHub Course Repository

thank you and visit again for more information.
