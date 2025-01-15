# ITI-Version-Control
This is lab 1 for version control
<div align="center">
 <img src="./task2.png" alt="task" width="90" height="auto">
<h1>Lab1</h1>
</div>

# Day 1 VC 
### What is Git? 
Git is a distributed version control system that tracks versions of files. It is often used to control source code by developers developing software collaboratively.
Git is the same as GitHub? False   
### What is the command to get the installed version of Git? 
git --version
### Which option should you use to set the default user name for every repository on your computer? 
--global  
 
### What is the command to set the user email for the current repository? 
git config user.email 
### What is the command to add all files and changes of the current folder to the staging environment of the Git repository? 
git add –all 
### What is the command to get the current status of the Git repository?
git status 

### What is the command to initialize Git on the current repository? 
git init 
### Git automatically adds new files to the repository and starts tracking them.? False 
### What is the command to commit the staged changes for the Git repository? 
git commit -m 
### What is the command to commit with the message "New email": 
git commit -m “New Email”
### What is the command to view the history of commits for the repository? 
git log
In Git, a branch is:  
A separate version of the main repository
### What is the command to create a new branch named "new-email"? 
Git branch new-email
Git checkout -b new-email
### What is the command to move to the branch named "new-email"? 
Git checkout new-email
### What is the command to merge the current branch with the branch "new-email"? 

Git checkout main	
Git merge new-email
