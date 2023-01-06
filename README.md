##What is Git?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
Git is easy to learn and has a tiny footprint with lightning fast performance. It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase with features like cheap local branching, convenient staging areas, and multiple workflows.

#Commands used in git

1) Clone
2) Add
3) Commit
4) Push
5) Pull

#Git Initializer

 To initializes a new repository use the following command
<br/>
Command :  git init 

#Create Connection

Create a connection between local repository and remote repository
<br/>
Command : git remote add origin "https://github...." 

#Save changes to Git :

1)git status
2) git add .

#Git checkout
This is also one of the most used Git commands. To work in a branch, first you need to switch to it. We use git checkout mostly for switching from one branch to another. We can also use it for checking out files and commits.

Command: git checkout <name-of-your-branch>

#Git Clone

Bring a repository into a folder in your local machine
<br/>
Command : git clone git@github.com:gwef/demo-repo.git

# Adding file

Track down the file and changes in git
<br/>
Command : git add .  // for adding all files
<br/>
Command : git add index.html  // for adding index.html file

# Commit file

Save the file in git
<br/>
Command : git commit -m "added new task"

# Push

Upload git commits to remote repository
<br/>
Command : git push -u origin main 
  
# Git status
The Git status command gives us all the necessary information about the current branch. 

 Command: git status
 
##Major Featues of Git status:
Whether the current branch is up to date
Whether there is anything to commit, push or pull
Whether there are files staged, unstaged or untracked
Whether there are files created, modified or deleted  
  

#Git branch
  
Branches are highly important in the git world. By using branches, several developers are able to work in parallel on the same project simultaneously. 
  We can use the git branch command for creating, listing and deleting branches.

Creating a new branch:

 Command: git branch <branch-name>

# Undo operation

Command : git reset

#git diff

You can use this command to see the unstaged changes on the current branch
Command: git diff --stage

Command : git reset HEAD~1

# Fork

A fork is a copy of a repository that you manage. Forks let you make changes to a project without affecting the original repository. You can fetch updates from or submit changes to the original repository with pull requests
