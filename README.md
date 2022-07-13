# Cheatsheet
## Cloning a Repo from GitHub
Change Directory to the root folder you want to save the repo
```
cd git/<NAME>
```
Root folder is git
#
Using the repo URL clone the repo to your system
```
git clone https://github.com/<URL>
```
#
Now move to the directory
```
cd <NAME>/
```
#
#
## Creating Repo Locally
Open File explorer and create the folder where the repo will be saved and open it in CMD
```
cd git/<NAME>
```
#
Initialize git
```
git init
```
#
Setup the origin on remote
```
git remote add origin https://github.com/<URL>
```
#
Check the fetch and push config
```
git remote -v
```
#
Setup Account Identity
```
git config --global user.email <EMAIL_ADDRESS>
```
```
git config --global user.name <NAME>
```
#
Setup Upstream branch
```
git push -u origin master
```
NOTE: "-u origin master" Is only needed once
#
#
## Setting up a branch
Creating the branch
```
git branch <NAME>
```
#
Switch to the branch
```
git checkout <NAME>
```
#
Sync to the remote
```
git push -u origin <NAME>
```
NOTE: "-u origin <NAME>" Is only needed once
#
#
