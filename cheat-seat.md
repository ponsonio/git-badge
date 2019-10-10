```
git help 

git help rebase

 git init

 git status

 git add --all

 git add "*.txt"  //all text files

 git add 

 git commit -m "add readme file" 

  git commit -a -m "add readme file" (add all files)

 git log

 git diff

 git checkout 

git reset --soft HEAD^

git reset --hard HEAD^

git commit --amend -m "add line 3 and file to ammend"

git remote add origin https://github.com/ponsonio/git-badge.git


git push -u origin master

git remote rm  

git branch cat

git branch

git checkout cat

git merge cat

git pull 

git push tag

git config --global color.ui true

git log --pretty=oneline


git log --oneline -p

git log --oneline -stats

git diff HEAD^

git diff HEAD^^

git diff HEAD~5

git blame cat.txt


git help

git rm log.txt

git rm --cache log.txt  //stop tracking

```

git push -u origin master

git remote rm  

git branch cat

git branch -d cat //Delete branch

git branch

git checkout cat
git checkout -b cat (Creates the branch)

git merge cat

git pull 

git checkoout -b <branch_name> 
git push origin <branch_name>

git push --tag

git config --global color.ui true

git log --pretty=oneline

git branch -r //remote branches

git checkout <remote_branch>  /linkea 

git remote show origin

git push origin :<branch>  //Delletes remotes

git pushheroku-staging staging:master --> push local -> remote

git log --oneline -p

git log --oneline -stats

git diff HEAD^

git diff HEAD^^

git diff HEAD~5

git blame cat.txt

git help

git rebase 

```
git fecth 


Summary
6:44 'git init' -> initialization of a git repository INSIDE a project folder to be managed by git
7:39 'git status' -> display status of monitored / tracked files
8:09 'git add .' -> add all files to be tracked (individually -> 'git add filename') (= to 'stage' a file(s))
8:43 'git commit -m "..." -> to save a version of file(s) inside a branch with its name
9:35 'git branch' -> to view the branch(es) available ('*' -> current branch)
11:00 'git log' -> to view list of all commit(s) (last commit (HEAD) is on top of the list) 
13:14 'git checkout (id of a commit)' -> to view a commit -> this commit becomes the HEAD but is no longer inside its branch anymore (cannot change and commit because this has no branch)
14:14 'git master' -> reentering master branch
14:55 'git reset --hard (id of commit that we want to use)' -> go to specified commit and  delete all commit(s) after that
16:37 'git checkout -- .' -> delete all unstaged changes and go to the  last commit
18:35 'git checkout -b (branch name)' -> create a new branch which have all commits in the previous branch
20:20 'git checkout master' = 'git master' -> change to (master) branch
20:52 'git merge (name of branch to be merged)' -> merge branches
21:39 'git branch -D (name of branch to be deleted)' -> delete a branch
24:20 to resolve conflict between merged branches -> better do that manually by editing lines ourselves then doing 'add .' and 'commit'


Establishing connection between local repository 
and a remote repository on GitHub: 3:46
- git remote add origin link-of-repository: 4:00

Checking connection:
- git remote: 5:30
- git remote -v: 5:40

How to push branches to GitHub:
- git push -u origin master: 6:15 

Caching GitHub password: 7:58 

How to see the connection between the local 
and the remote branch:
- git branch -r: 9:33 

Clone or download: 10:34 
- git clone + link: 11:20

Colleague push changes: 12:40

"Download" code: 13:45
- git fetch: 14:15
- git checkout origin/master: 15:04 
- git merge origin/master: 15:30

Combining the above two steps: 
- git pull: 16:00

Summary: 16:30

Deleting repository: 17:30
- git remote rm name-of-repository: 18:20

Playlist:
Git & GitHub - Managing Your Code:
https://www.youtube.com/watch?v=_OZVJpLHUaI&list=PL55RiY5tL51poFMpbva1IqfO-pylwSNsN

10

