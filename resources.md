# Useful OS Commands

## Windows

* dir → Prints the content of current directory
* cd [directory name] → Change directory
* mkdir [new directory name] → Create a new directory
* cls → Clear the terminal screen

## Linux / Mac / git bash

* ls → Prints the content of current directory
* cd [directory name] → Change directory
* mkdir [new directory name] → Create a new directory
* clear → Clear the terminal screen

# Useful Git Commands

* git config --global user.name “[name]” → Sets author name
* git config --global user.email “[email address]” → Sets author email id
<br><br>

* git init [repository name] → Initializes a new repository
* git clone [url] → Obtain a repository from an existing URL
<br><br>

* git add [file] → Adds a file to the staging area.

* git commit -m “[ Type in the commit message]” → Records or snapshots the file permanently in the version history
* git commit -am "[ Type in the commit message]" → Adds *modified* files to staging area, then commits it (Note: new files have to be added via git add)
<br><br>

* git diff → Shows the file differences which are not yet staged
* git diff –staged → Differences between the files in the staging area and the latest version present
* git diff [first branch] [second branch] → Differences between the two branches mentioned
<br><br>

* git reset [file] → Unstages the file, but it preserves the file contents
* git reset HEAD~1 → Undoes the last commit and preserves the changes locally
* git reset [commit] → Undoes all the commits after the specified commit and preserves the changes locally
* git reset --hard [commit] → Discards all history and goes back to the specified commit
<br><br>

* git status → Command lists all the files that have to be committed
<br><br>

* git rm [file] → Deletes the file from your working directory and stages the deletion
<br><br>

* git log → Used to list the version history for the current branch
* git log –follow[file] → Lists version history for a file, including the renaming of files also
<br><br>

* git show [commit] → Shows the metadata and content changes of the specified commit
<br><br>

* git tag [commitID] → Used to give tags to the specified commit
<br><br>

* git branch → Lists all the local branches in the current repository
* git branch [branch name] → Creates a new branch
* git branch -d [branch name] → Deletes the feature branch
<br><br>

* git checkout [branch name] → Used to switch from one branch to another
* git checkout -b [branch name] → Creates a new branch and also switches to it
<br><br>

* git merge [branch name] → Merges the specified branch’s history into the current branch
<br><br>

* git remote add [variable name] [Remote Server Link] → Used to connect your local repository to the remote server
<br><br>

* git push [variable name] master → Sends the committed changes of master branch to your remote repository
* git push [variable name] [branch] → Sends the branch commits to your remote repository
* git push –all [variable name] → Pushes all branches to your remote repository
* git push [variable name] :[branch name] → Deletes a branch on your remote repository

<hr>
<br>
<p align="center">
	With :heart: by <a href="https://github.com/SIGMA-XI-VIT" target="_blank">Sigma Xi VIT</a>
</p>
