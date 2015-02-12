# Cheatsheet for Git

##Account functions

```

git congig --global --user.name "youname" //specify your name to git (can't work without a name)

git config --global --user.email "youre@email.com"	//specify you email to git(can't work without an email), --globall is to set it for all repos


```


##File and Repo functions

```

git init //start a repo in this folder

git config --global user.name “username”    //set the username for all repo(cant’ work withour one)
git config --global user.email “your@email.com” //set the email for all repo


git status	//show the current stage
git log	//show commit history
git diff //get difference in the file

git add "file.name"	//add the file to the stage
git add "*.extension" //add all the .extension file to the stage
git add folder/	//all all the files and subfolder of the directory to the stage

git commit "file.name"	//push the file to the repo
git commit --all	//push all the watched file to the repo

git remote nameoftherepo(ex:origin) url		//sets the actual directory to the remote online repo given a url https,git,ftp,etc...
git remote -v 	//list all the remote
git remote show origin	//list all the brancks and remote
git remote prune origin	//delete the deleted remote 

git push -u 	//push to the online repo and sets it to default
git push origin branch	//push on github the branch on the given master/or origin
git push origin :nameofthebranch	//delete the remote branch
git push --tags		//push the local tags to the remote
git pull	//pull from the remote

git branch	//list all the local branchs
git branch -r 	//list all the remote branchs
git branch -d nameofthebranch 	//delete the local branch
git branch -D nameofthebranch 	//force delete the local branch

git clone url.git (optional)nameofthedirectory	//clone a repo

git checkout branch	//move to the named branch
git checkout -b branch	//create a new branch and move in it
git checkout tagname	//jumps to the given commit history tagname

git reset HEAD nameofthe.file   //uncommit the last change given the file
git checkout -- nameof.file //undo last change on the given file
git reset --soft HEAD^	//move to commit 1 level before actual
git reset --soft HEAD^^	//move to commit 2 level before actual

git tag 	//list all the tag

```
