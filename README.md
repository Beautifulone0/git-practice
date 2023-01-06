# git-practice just an illustration on how to start with git and git hub and also push to a remote repository 
# you should have already created a GitHub account, downloaded git and git bash for windows users and Linux os users you should have installed git through your terminal and also you should have configured your git for both Linux and windows users
# it's just a practice not really a project 

For those of us  having issues with Git & Git hub

    ◦    Create a folder called git practice Note that you should create this folder on your desktop so it would be easy to locate
    ◦    For those using windows operating system open your GitBash and those using a Linux OS open your terminal 

Start by changing directory to where your file is located and that’s on your desktop do that by entering this commands

    ◦    ls (small letter L ) would show you a list of all file and folders in your pc even hidden folders 
Then  the next command is cd 

    ◦    cd desktop helps you change directory to desktop where you have your file 
Then enter the command ls to show the list of folders you have on your desktop and then cd to your git practice folder after that

Note: you can save your self all the stress of changing directory and go to your git practice folder right click and click git bash here that’s for windows users. 

Next step is to initialize git

    ◦    Initialize git by entering the command git init you would get a message initialized empty git repository in desktop/git practice/git
    ◦    Then enter the command git status to know the status of the folder you would get a message saying on branch master or main there is nothing to commit create or add file to be able to add and commit

Then quickly open you git practice folder on vs code and add some files could be index.html or style.css then go back to your git bash or terminal enter the command git status and you would get a message telling you to add your file to do that 

    ◦    Enter the command git add the name of your file example git add index.html

After successfully adding files next is to commit 

    ◦    Enter the command git commit -m “Enter your commit message “ example git commit -m “git practice “

After committing successfully 

    ◦    Enter the command git -m master if your branch is main do git -m main
    ◦    Next enter the command git branch it shows you the branch your git repo is on if it’s master it shows master if it’s main it shows main 

Then go to your git hub profile and add new repository you have to use the same name on your folder after creating the repo the next step is to copy the url and then enter the command 

    ◦    git remote add origin then enter the url you copied example: git remote add origin https://GitHub.com/Beautifulone0/git-practice.git 

After that the next thing is to push to the remote repository 

    ◦    Enter the command git push -u origin master if your branch is main do git push -u origin main

You would get a response or you would be prompted to input your username 
And the password after that your folder should be on your GitHub as a remote repository 
You can also use the terminal on your vs code too if you don’t want to use git bash or your terminal 
just make sure you have the particular file you are working on opened on your vs code 
click on terminal then click on new terminal and then a terminal where you can initialize git and also publish remotely would appear 
I hope this helps someone happy coding 😊😊😊🎉
