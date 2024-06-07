# github-demo
In this repo, I am just learning how to use Github &amp; how this version control basically functions. Good luck to me!
Commit: here shows, how many times you've made changes in the repo. The moment you make one repo, count initalizes to 1. I did some grammatical error so I corrected that twice which leads to 3, and now when i am writting this it would be 4.


# 👉 Now,
The changes you are seeing here onwards are all committed from the VS Editor using Git.


# ➡️ Let's talk about some basic Git Commands :
1) For cloning a repository from Github use command - git clone <link of the website>

2) To go inside the folder you're working on use command - cd <folder name>

3) To see files inside the folder use command - ls

4) To clean the terminal use command - clear

5) To check the status of the file use command - git status

# (There are 4 stages of files in git let's dicuss them) :
a) Untracked -  files which are not tracked by the git, git dosen't have a clue about the modification or deletion in it.
b) Unmodified - files which are tracked by the git, for the changes taking place in the file. Mid level stage between untracked and modified
c) Modified -   changes which are now staged to git, but haven't been pushed yet to the root app(Github in this case).
d) Staged -     changes which are saved, and pushed to the root app via git command.


6) To save the changes made in the file we use command - git add <file name>

7) To commit those changes, meaning to put them on stage we use command - git commit -m"some meaningful message here"

8) To see all these changes on the remote app use command - git push origin main

# What if you made a folder in your device first, and then you wanna push it on github?
9) For folder which you made in your device first and now it should be availabe on github for that use command - gitint

10) For pushing folder on github, make a new repo on github. Then run command - git remote add origin <link>

11) For verification of the folder link, use command - git remote -v

12) Now, use the same push command.

13) For ex: you made changes directly on github, then you have to pull those changes in Git use command - git pull origin main




