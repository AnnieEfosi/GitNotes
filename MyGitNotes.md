# Annie's Personal Help Notes for Git

1. Version Control

* **Version Control System (VCS)** - Toll that manages different versions of source code
* **Source Code Manager (SCM)** - Another name for a VCS

* **Commit** - Save the sate of your project in Git
* **Repository / Repo** - Directory containing project work and files that communicate with Git. *Repos can exist locally on your computer or remotely on another computer.
* **Working Directory** - Files on your computer's filing system
* **Staging Area / Index or Index** - A file in the Git directory that stores info on what will go into your next Commit.
* **Checkout** - Content from the repo is copied to the working directory
* **SHA - Secure Hash Algorithm** - ID number for each Commit
* **Branch** - New line of development that diverges from the main development.  


2. Creating a Repo from Scratch

- Create a repo from scratch - $ git init 
- list files and directories - ls
- Create new directory - mkdir
- Change directories - cd
- Remove files and directories - rm
- Print Working directory (find out what you are woring on) - pwd


3. Cloning a repo

- Clone a repo - $ git clone <path-to-repository-to-clone>
- By default the clone is created with the same name but it can be re-named


4. Status Update

- Find out the status of a Commit - $ git status

5. Track changes

- Find out when changes are made and by whome - $ git log
  By default, this command displays:

      the SHA
      the author
      the date
      the message

- Shorten the display of the log (short SHA and comment only)  - $ git log --oneline

	navigating the log:
	-to scroll down, press
		j or ↓ to move down one line at a time
		d to move by half the page screen
		f to move by a whole page screen
		
	-to scroll up, press
		k or ↑ to move _up_ one line at a time
		u to move by half the page screen
		b to move by a whole page screen
	
	-press q to quit out of the log (returns to the regular command prompt)



Advanced Stuff

- Customising Git - https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration

- Git Plumbing and Porcelain - https://git-scm.com/book/en/v2/Git-Internals-Plumbing-and-Porcelain

- Git Hooks - https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks
