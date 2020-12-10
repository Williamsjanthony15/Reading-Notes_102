# **Day 3 Notes

# **Vocab Words**
---------------
VCS - 
Git vs. Github - 
local vs remote - 
clone - 
commit - 
ACP - Add, Commit, Push ***Form This Habit***
deployment - 

#Topics for Day 3
----------------
Review of previous class
Share your learning
Sharing Code
Git
Github
Live Demos
Discussion Exercise
Git
Lab: Revisions and the Cloud


# Notes (Required reformatting)
Git is a version control system... It allows Multiple developers to work on the same code at the same time... It also keeps a change of history..... View, apply, and remove those changes.(THREE MAIN THINGS)..... Keep all of your project files in one repository....IT makes collaboration possible.......
Git commits changes to repo (snapshot) But in laymens terms it is a "save as"
New commit creates a new version of the previous document

HEAD = the lable meaning YOU ARE HERE (the most recent commit and where you are) Will see this a lot

DETACHED HEAD STATE= Get staff to see what is going on it makes a difference. (on the wrong part of last commit...)

 Messages are like writing a caption for your snapshot. Do a description of everything you did for the commit. ANything and Everything... What did you do and Why did you do it. (leave your future self a note from the past)


Working Directory  |  Staging area |  Repository
----------------------------------------------------------

<--------------------Checkout project--------------------
----------------> Stage Changes ---------> (made changes, not going to commit them YET but they are going to save them and wait) 
---------------> Commit Changes----->. ( Push commits only)


Git is the version control its self
Github is the storage cloud

<Git**Hub**> 
  > Your Code, In the cloud
  
  Where to share code with others.
  an online place to store you code
  it uses git to help you manage your teams work
    version tracking
    reviewing cahnges
    keep changes seperate untill you want to add them in
  WIth Git (version Control) and Github (online code storage), you can:
  
    Have lots of team members work together
    historys of filke
    work on computer and sync to online.
    
    Github is the best and most used in open source community SO many tools for enterprise level software to be provided
    
    Atlassian is a open source platform as well. 
    
  Gitflow:acp
  add commit push
  
  Common pattern that we use for git that ensures the consistant flow and history to prevent incorrect software. 
  
  > Git status ------ basic command you will use a lot**************************
  Files that have been changed that arent and are in your staging area. What branch your on. Function WILL not ***Change*** your Repo
  
  > code . 
  Edit that file with VS code 
  
  Git add README.md 
  
  Git will auto recognize the changes Than it will stage it and than push to the repo. 
  
  Git status and it will output something different
  
  > git commit -m "adds initial greeting to the world"
  -m tells it that you want to add a message. 
  
  >git push origin master
  .....
  
  
  
  More Command line stuff.
  
  .git will be in the command line Readme.md file but it doesnt matter GITHUB will understand and know its in there.... No need to deal with anything
CLI will immedietly automatically put me in the repo

PUSH will move it from CLI to Commiting...


git remote -v 
Tells us what remote repo is connected to my local repo on my machine
Where is it connected and what it is...


Pulling repo
git clone (URL from your repo on github) 
WHen you pull it in to CLI. Main is a branch from the repo in GIT
push gets the two into sync 


Visual studio code will automatically detect the changes ....

Look at changes through terminakl 

git status
(Red means unstagged change)
git Add readme.md 
get status again 
(green) now ready to be comminited
git commit -m "add new line and improve readability for title"

-----All these changes are on the local machine only. Havent changed anything in GITHUB -------

If you get an error message than. obvioussly it idnt work

git push origin main ---- pushing the data to origin main
it will ask for your information
to authorize the change


Find your repo on github
clone it from the https
open your project on vs code
make changes
come back to  it
and run our A-C-P
add table of contents ** making changes** modifying it,. 
save the file on my working directory
git add . 
git commit -m "add table of contents to provide supreme navigations"
git push orgin main
Authorization
Done...... 

Will save it until you push it as long as i dont kill my computer

Kracken GUI

Get fetch will ask the repo to return with any changes that it doesnt have

Git status will tell you if your behind

Git pull will pull them down and update your changes


  

