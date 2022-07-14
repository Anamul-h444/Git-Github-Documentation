# Git-Github-Documentation
#### Sequence of go local repository
-> git init (In Working directory)  
-> git add fileName with extension (Staging file which file you write)  
-> git add . (Staging all file)  
-> git commit -m"message here" (For commit or finally go local repository)  
Now We ready for push remote repository.

#### Connect local repository to remote repository and push branches
-> git remote and origin github link here  
-> git branch -m branch name here  
-> git push -u origin branch name here

#### Necessary command
-> git staus (For check git status)  
-> git log (For check commit)  
-> git log --oneline (For check commit shortly)
-> git pull (For get update from remote repository to local repository)  
-> git clone repo link here ( For get full repo from remote repository to local repository)  
-> git checkout branch name here (For move branch)
-> git merge branch name here (For marge branch)    
-> git branch (List of branches)  
-> git branch -r (List all remote branches )  
-> git branch -a (List all local & remote branches)   
-> git checkout branch_name (move to a branch)  
-> git checkout -b branch_name (create and move to a branch)   
-> git branch -d branch_name (delete a branch)  
-> secret.txt (secret.txt will be ignored)  
-> *.txt (ignore all files with .txt extension)  
-> !main.txt (ignore all files with .txt extension without .main.txt)  
-> test?.txt (ignore all files like test1.txt test2.txt)  
-> temp/ (all the files in temp folders will be ignored)  
-> git show (For check what is changed in commit)  
-> git show commit-id (For check what is changed in commit by commit id)  
-> git checkout commit-id (For go any commit by commit id)  
-> git reset --soft HEAD^ (uncommit the commit in HEAD and move to staging area)  
-> git reset HEAD^ (uncommit the commit in HEAD and move to unstaging / working area)  
-> git reset --hard HEAD^ (uncommit the commit in HEAD and delete the commit completely with all the changes)  
-> git rm --cached fileName (unstage a file from staging area)  
-> git diff (checking the what is changes of a staged file)  
-> git restore fileName (changes restore/delete from the file)  
