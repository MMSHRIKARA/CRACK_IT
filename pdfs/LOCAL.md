**if two microservices needs same logic where should that code lies?

LOCAL**

**-----**

**git init** \[turns working directory into empty git repository]

**git add .** / **git add "file name"** \[moves files into staging area]

**git status** \[shows status of git repository]

**git commit -m "commit message"** \[commits changes into git repository history]

**git commit -a -m "commit message"** \[Commits changes by staging file, -a does not add untracked files-- only modified tracked ones]

**git branch "new branch name"** \[create new branch]

**git branch** \[lists all local branches]

**git branch -r** \[lists all remote branches]

**git branch -a** \[lists all local \& remote branches]

**git switch "branch name"** \[to switch branch]

**git switch -c "branch name"** \[creates \& switch to new branch]

**git merge "branch name"** \[Incoming changes to current branch from mentioned branch]

**git stash** \[cleans Staging area \& working directory \& then moves changes into stash area/temporary storage]

**git stash pop** \[retrieves changes from stash area/temporary storage]



**REMOTE**

**------**

**git clone "remote repo url"** \[initial setup of remote repository on our computer, creates folder of repo name \& download all files]

**git remote add origin "remote repo url"** \[To add remote repository]

**git push -u --all** \[push all local branches to remote \& -u sets default corresponding upstream branch]

**git push -u origin "branch name"** \[push branch to remote \& -u set as default upstream branch]

**git fetch** \[checks \& shows latest updates from remote repo]

**git pull** \[will pull changes from remote repo]





