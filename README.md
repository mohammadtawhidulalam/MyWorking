# MyWorking
This is my first Git REspository
<br>
Author - Mohammad Tawhidul Alam
<br>
Configuring Git <br>

git config --global user.name "My Name" <br>

git config --global user.email "someone@email.com" <br>

git config --list <br>

cd change directory

ls -Fo = hidden file included

Clone & Status
Clone - Cloning a repository on our local machine
git clone <- some link ->
displays the state of the code
status -
git status


untracked
 new files that git doesn't yet track

modified
 hanged

staged
file is ready to be committed

unmodified
unchanged



Add & Commit

add - adds new or changed files in your working directory to the Git staging area.
git add <- file name ->

commit - it is the record of change
git commit -m "some message"


Push Command

push - upload local repo content to remote repo
git push origin main


Init Command
init - used to create a new git repo
git init
git remote add origin <- link ->
(to verify remote)
git remote -v
git branch
(to check branch)
git branch -M main (to rename branch)
git push origin main