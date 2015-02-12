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

git commit "file.name"	//push the file to the repo online
git commit --all	//push all the watched file to the online repo

git reset HEAD nameofthe.file   //uncommit the last change given the file
git checkout -- nameof.file //undo last change on the given file
git reset --soft HEAD^	//move to commit 1 level before actual
git reset --soft HEAD^^	//move to commit 2 level before actual
```
