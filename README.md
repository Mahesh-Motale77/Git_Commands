# Git_Commands
This is the Repository which has all git command and information.
<b><i>                     </b></i>
Git: 
 </b></i>
- version control system is a tool that helps to track changes in code
- Git is a version control system
- It is popular, free & open source, fast & Scalable
• Track the history
• Collaboration

<b><i> 
Github:
 </b></i>
-website that allows developers to store and manage their code using Git.

<b><i> 
Setting up Git:
 </b></i>
- Visual Studio code
- windows (Git Bush)
- mac (Terminal)

git --version (for checking)

Configuring Git
git config --global user.name "my name"
git config --global user, email "email@gmail.cor
git config --list

-----Go to vs code terminal

clone & status-

Clone: Cloning repository on our local machine git clone <- some link ->
Status: display Status of code.

git status
- file modified or not
untracked : new file that git doesn't yet track
modified : changed.
staged : file is ready to committed
unmodified : unchanged .

Add & commit:
add - adds new of changed files in your working directory to the Git Staging area
 git add <- file names -> or gil add .

commit - it is the record of change
git commit -m "Some message"

Push command:
upload local repo content to remote repo
git push origin main

Init Command:
init : used to create a new git repo

git init
git remote add origin <- link ->
git remote -v
git branch
git branch -M main
git push origin main

Workflow :-

Github repo -> clone -> changes -> add -> Commit -> push

Git Branches :

git branch (to check branch)
git branch -m main ( to rename branch)
git checkout <-branch name -> (to navigate)
git checkout -b <- new branch name? (to create news branch)
git branch -d <-branch name -> (to delete branch)

merging Code:

Way 1:
git diff branch name> - to compare commits, branches, files & more
git merge <-branch name -> - to merge 2 branches

Way 2:
-Create a pull request (Done through github)
-let other know about changes you've published to brunch in repo on github.


pull command: git pull origin main
-used to fetch and download content from a repo and immediately update the local repo to match that content.

Resolving merge conflicts:
An event that takes place when Git is unable to automatically resolve differences in code between two commits.
→ we have to manually decide the change. which we want.

Undoing changes:

Case 1: Staged changes (added but not committed)
git resets <-file name-> git resets

case 2: committed changes (for one commit)
git reset HEAD~1

case 3: committed changes (for many commits)
git reset <-commit hash->
git reset --hard <- commit hush->

Fork:
A fork is a new repository that shares code ar visibility settings with the original "upstream" repository
→fork is a rough copy