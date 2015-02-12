# Cheatsheet for Git

##Account functions

```

git congig --global --user.name "youname" //specify your name to git (can't work without a name)

git config --global --user.email "youre@email.com"	//specify you email to git(can't work without an email), --globall is to set it for all repos


```


##File and Repo functions

```

git init //start a repo in this folder

git status	//show the current stage
git log	//show commit history

git add "file.name"	//add the file to the stage
git add "*.extension" //add all the .extension file to the stage
git add folder/	//all all the files and subfolder of the directory to the stage

git commit "file.name"	//push the file to the repo online
git commit --all	//push all the watched file to the online repo


```