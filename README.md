# GitGuide

To make a header put a hashtag, space then the name
To make a sub-header pt two hashgtags, space then the name
For normal text nothing is needed

## MarkDown

This is a MarkDown file or a md file for short (also the extension)
In GitHub or any Git, always provide a file called README.md 

## Git Commands and Terms

There are five basic commands for git:
clone - clones a repository from a remote repository to your local PC (downloads the files)
add - adds files you want to track within a repository so when changes are saved, they'll be added to Git (you can add them by using their specific file name or add everything from the reposity by using ".")
commit - saves files into Git to commit and add at the same time for modified files you can use: git commit -am "message"
push - pushes saved files from Git to remote repository like Github
("git push origin master" is the default, if you wanted to push to a branch specify instead of master)
pull - Downloads changed files from remote repository into local cloned repository
init - initializes repository as a Git repository if made locally
branch - using git branch allows you to see what branches there are as well as what branch you are currently on
status - Status allows for you to check what files you added for git to check and in addition to that which ones have been updated/commited to git
checkout - Used to swich between branches, but if you want to make a new branch type "git checkout -b nameOfBranch"
reset - If you make an accidental add you can do 'git reset' to unadd them. If you do an accidental commit you can do 'git reset HEAD~1' to uncommit and unadd them
## How to connect Github starting locally

Say you've created a project locally not knowing anything about git, but now want to implement it into your project to have consistent updates. Simply, create a repo on Github with the same name, then get the ssh. Next on your local device init your repo as a git repo and then add a remote repo with the following command ("git remote add origin 'ssh here'")

## Git Branching

Three main types of branches, master, hotfix, and feature. These branches usually get merged back into the master branch.