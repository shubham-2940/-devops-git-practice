#Reference file for git

1] git init :- used to initialize empty git repo.

2] git config :- used to configure username and email.
e.g. git config user.email "sd823242@gmail.com"
     git config user.name "shubham-2940"

3] git config --list :- used to see/verify configuration.

4] git add : used to add any new file to staging phase.
e.g. git add git-commands.md

5] git status : used to check status to of git shows how many file are in staged and remaining for commit.

6] git commit : used to commit chnages with message. Moves file from Stagging=> Track phase
e.g. git commit -m "Created git-commands.md file."

7] git log : used to see/verify commit history.
e.g. git log
     git log --oneline : shows all logs in oneline
     git log --oneline : show last 5 commits in one line.
     git log -5 : show last 5 commits history/logs.

## Branching Commands ##

 git branch : to list all branches
 
 git branch <'branch name'> : to create new branch
 git checkout -b <'branch name'> : to create new branch and switch to it
 git switch <'branch name'> : used to switch between one branch to another.
