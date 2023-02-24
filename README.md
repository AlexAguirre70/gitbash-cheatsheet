# Review of GitBash Command Line Interface
This is only a README file to review the most common GitBash commands to create a local and remote repositories. 

Git is a DevOp used to handle small and large projects efficiently. <br/>

It allows for collaboration among different people in different parts of the same project. <br/> 

Git is a version control system for tracking changes in computer files, so a specific version can be considered whenever needed. <br/>

The **local repository** resides on the local computer and consists of all the files and files and folders. This repository is used to make changes locally, review history and commit when offline. <br>

The **remote repository** resides anywhere on a web server that can be used by team members to exchange the changes made on their own local repositories. 
## Commands

### git init -y
this is used to create an EMPTY git repository in the folder and sub-folders it is created in. Once initialized the process of creating other files begins. <br/>

The **-y** flag adds the default parameters to the initialization.

### git add -A
This adds any new or changed files to stading.<br/>
The -A flag is the same as using a . This adds all the files.

### git commit -m "message"
This saves the changes in that are staged to the local repository. <br/>
The **-m** flag and message allows us to describe to team members what changes were made.

### git status
This returns the current state of the repository. All the files in the staging area not yet committed will be shown.

### git config user.name "name"
This is used intially to configure the user.name and the user.email<br/>
When using the -global flag, this applies it to all the repositories

### git branch
This command is used to determin what branch the local repository is one.<br/>
When adding the branch name it creates an new branch. **git branch "name"** <br/>
When used with the **-m** flag it modifies the branch name. **git branch -m originalName newName** <br/>
When used with the  **-a** flag it will list all remote or local branches <br/>
when used with the **-d** flag and **branch name** it will delete the branch.

### git checkout
This is used to change branches whenever you need to make changes on another branch. **git checkout branchName**

### git merge branchName
This is used to integreate branches together.  The branch name you pass merges it with the current branch you are on.

### git remote add origin URL
This is used to create, view and delete connections to remote repositories. <br/>
These are not direct links but act as bookmarks that serve as convenient name to be used as a reference. <br/>


### git clone remote_url
This command creates a local working copy of a remote repository. <br/>
It also initializes a repository if it does not already exist.

### git pull
This is used to fetch and merge changes from the remote repository to the local repository.

## git push -u origin main
This transfers the commits from the local repository up to the remote repository to share with remote team members. <br />
The **-u** flag pushes unsaved changes upstream to the repo name provided. In the example the changes are being pushed to the repo named 'main'.

### git stash -u
This command takes your modified tracked files and saves it on a pile of incomplete changes that you can reapply at any times. <br/>
To get back to making changes use the **git stash pop**

### git log
Shows the order of the commit history for the repository.<br/>






