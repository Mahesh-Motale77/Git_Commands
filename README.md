# Git_Commands
This is the Repository which has all git command and information.
<br>
<b><i><h3>                 </h3></i></b>
Git:   <br>
</h3></i></b>
- version control system is a tool that helps to track changes in code <br>
- Git is a version control system <br>
- It is popular, free & open source, fast & Scalable <br>
• Track the history <br>
• Collaboration <br>

<b><i><h3>   
Github:
</h3></i></b>
-website that allows developers to store and manage their code using Git.
 <br>
<b><i><h3>  
Setting up Git:
</h3></i></b>
- Visual Studio code <br>
- windows (Git Bush) <br>
- mac (Terminal) <br>
 <br>
git --version (for checking)
 <br>
<b><i><h3>  
Configuring Git
</h3></i></b>
git config --global user.name "my name" <br>
git config --global user.email "email@gmail.com <br>
git config --list <br>
 <br>
-----Go to vs code terminal
 <br>
<b><i><h3>  
clone & status-
</h3></i></b>

Clone: Cloning repository on our local machine git clone <- some link -> <br>
Status: display Status of code. <br>

<b><i><h3>  
git status
</h3></i></b>
- file modified or not <br>
untracked : new file that git doesn't yet track <br>
modified : changed. <br>
staged : file is ready to committed <br>
unmodified : unchanged . <br>

<b><i><h3>  
Add & commit:
</h3></i></b>
add - adds new of changed files in your working directory to the Git Staging area <br>
 git add <- file names -> or gil add . <br>
 <br>
commit - it is the record of change <br>
git commit -m "Some message" <br>
 <br>
<b><i><h3>  
Push command:
</h3></i></b>
upload local repo content to remote repo <br>
git push origin main <br>
 <br>
<b><i><h3>  
Init Command:
</h3></i></b>
init : used to create a new git repo
 <br>
git init <br>
git remote add origin <- link -> <br>
git remote -v <br>
git branch <br>
git branch -M main <br>
git push origin main <br>

<b><i><h3>  
Workflow :-
</h3></i></b>
 <br>
Github repo -> clone -> changes -> add -> Commit -> push
 <br>
<b><i><h3>  
Git Branches :
</h3></i></b>
 <br>
git branch (to check branch) <br>
git branch -m main ( to rename branch) <br>
git checkout <-branch name -> (to navigate) <br>
git checkout -b <- new branch name? (to create news branch) <br>
git branch -d <-branch name -> (to delete branch) <br>

<b><i><h3>  
merging Code:
</h3></i></b>

Way 1: <br>
git diff branch name> - to compare commits, branches, files & more <br>
git merge <-branch name -> - to merge 2 branches <br>
 <br>
Way 2: <br>
-Create a pull request (Done through github) <br>
-let other know about changes you've published to brunch in repo on github. <br>
 <br>
<b><i><h3>  
pull command:
</h3></i></b>
git pull origin main <br>
-used to fetch and download content from a repo and immediately update the local repo to match that content. <br>

<b><i><h3>  
Resolving merge conflicts: <br>
</h3></i></b>
An event that takes place when Git is unable to automatically resolve differences in code between two commits. <br>
→ we have to manually decide the change. which we want. <br>

<b><i><h3>  
Undoing changes:
</h3></i></b>
 <br>
Case 1: Staged changes (added but not committed) <br>
git resets <-file name-> git resets <br>
 <br>
case 2: committed changes (for one commit) <br>
git reset HEAD~1 <br>
 <br>
case 3: committed changes (for many commits) <br>
git reset <-commit hash-> <br>
git reset --hard <- commit hush-> <br>
 <br>
<b><i><h3>  
Fork:
</h3></i></b>
A fork is a new repository that shares code ar visibility settings with the original "upstream" repository <br>
→fork is a rough copy <br>
..
