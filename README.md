# Cheatsheet
## Cloning a Repo from GitHub
	• Change Directory to the root folder you want to save the repo
        ```
		○ Cd git/<NAME>
        ```
			§ Root folder is git
	• Using the repo URL clone the repo to your system
		○ Git clone https://github.com/<URL>
	• Now move to the directory
		○ Cd <NAME>/

## Creating Repo Locally
	• Open File explorer and create the folder where the repo will be saved
	• Open it in CMD
		○ Cd git/<NAME>
	• Initialize git
		○ Git init
	• Setup the origin on remote
		○ git remote add origin https://github.com/<URL>
	• Check fetch and push
		○ Git remote -v
	• Setup Account Identity
		○ Git config --global user.email <EMAIL_ADDRESS>
		○ Git config --global user.name <NAME>
	• Setup Upstream branch
		○ Git push -u origin master
		○ NOTE: "-u origin master" Is only needed once
	• DONE
## Setting up a branch
	• Creating the branch
		○ Git branch <NAME>
	• Switch to the branch
		○ Git checkout <NAME>
	• Sync to the remote
		○ Git push -u origin <NAME>
		○ NOTE: "-u origin <NAME>" Is only needed once
	• DONE