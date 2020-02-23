// Use visual stuido code just for cloning the project to the directory or use the android studio
// Go to the directory where you want your repo to be in
cd directory_you_want_to_work_in 

// Make sure directory is empty then clone the repo, use line below
git clone https://github.com/kgupta31/Capstone-1-Gravel-Shooters.git

// Create your branch and go into it
git checkout -b Your_name

// You shouldn't have changes but if you do here is the command to add them and commit them
git add -A
git commit -m "Helpful message why your commiting"

// To update and sync your branch from master
//  (Make sure to have no unadded changes and commits)
git checkout Your_Branch_name
git pull origin master
git merge master
git push origin Your_Branch_name // Your branch name

// To update Master with your changes from your branch
//  (Make sure to have no unadded changes and commits)
git checkout master
git pull origin master
git merge Your_branch_Name
git push origin master

// commands for switching branches
git checkout Your_Branch_name
git checkout Master

// Check your changes 
git status

// The command to list all branches in local and remote repositories is:
$ git branch -a

// If you require only listing the remote branches from Git Bash then use this command:
$ git branch -r

// You may also use the show-branch command for seeing the branches and their commits as follows:
$ git show-branch

