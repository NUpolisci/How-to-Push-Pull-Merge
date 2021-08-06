# How-to-Pull-Push-Merge
This repository is a simple guide for how to pull, push, and merge Github repositories when you are running a workshop with other people. If you are unfamiliar with Github, you should first check out this repositry on [how to use Github repositories for workshops](https://github.com/NUpolisci/How-to-use-Github-repositories-for-workshops).

# Git Basics 
The best guide to use when working with Github and RStudio is [here](https://happygitwithr.com/new-github-first.html). This is just a supplementary guide to quickly compile some of the basic skills you may wish to use. 

# Pushing 
## Committing 
Committing a code is basically bookmarking a change you have made. It does not yet add it to your repository (i.e. version control). You can committ a number of things at once, and you can commit numerous times before adding it to your repository.

There are two ways to commit: 

### 1) Commit via Terminal 
If you wish to commit via the terminal, you must first go to your terminal and write: 
`git add "your_file_name.filetype"`
`git commit "meaningful message"` 

When you are committing, the key is to write meaningful messages to your future self and your collaborators. This is basically logging what the major changes you made were. If you want to go back to a previous version to look at your code, these commit messages will be HUGE in helping you figure out what changes you made. Messages like "UGH JUST WORK", "OMG YAY", "UGH NOT AGAIN", etc... are not useful messages. You must include a message when you commit. 

### 2) Commit via RStudio 

On R studio, once you have connected your project to a github repository, you can commit via the RStudio platform. 
