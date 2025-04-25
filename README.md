Steps followed to create a file in local and pushing to remote repo
Step 1 - Install git on Mac system user command 
  brew install git
After the successful installation of git just verify to use command as 'git' 

Step 2 - Configure git by using below 2 commands 
  git config --global user.name "HarshadaShende"
  git config --global user.email shendeharshada@gmail.com

Step 3 - Make a program file in your local 
  mkdir GitPractice
  cd GitPractice

Step 4 - Create New Local Repository
  git init

Step 5 - Checking the status 
  git status

Step 6 - Add changes on staging area 
  git add
  git add a.java
  git add . //add everything
  git status

Step 7 - Committing into local repository 
  git commit -m "You can add any descriptive comment while committing" 

Step 8 - Connecting to a remote repository 
    1. In order to upload something to a remote repo.
    2.Create a Repo at Github.com and Add Remote to it.
    3.The Git command to do this is git push and takes two parameters.
      The name of the remote repo (we called ours origin) and the branch to push to
  git remote add origin (https://github.com/HarshadaShende/GitPractice.git)
  
