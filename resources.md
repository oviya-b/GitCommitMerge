# Useful OS Commands

## Windows

* dir -> prints the contents of current directory
* cd [directory name] -> change directory
* mkdir [new directory name] -> create new directory
* cls -> clear terminal screen

## Linux / Mac / git bash

* ls -> prints the contents of current directory
* cd [directory name] -> change directory
* mkdir [new directory name] -> create new directory
* clear -> clear terminal screen

# Useful Git Commands

* git config --global user.name “[name]” ->sets author name
* git config --global user.email “[email address]” ->sets author email id
<br><br>

* git init [repository name] ->start new repository

* git clone [url] ->obtain a repository from an existing URL.
<br><br>

* git add [file] ->adds a file to the staging area.

* git commit -m “[ Type in the commit message]” ->records or snapshots the file permanently in the version history.
* git commit -am "[ Type in the commit message]" ->Adds *modified* files to staging area, then commits it (Note: new files have to be added via git add)
<br><br>

* git diff ->shows the file differences which are not yet staged.
* git diff –staged ->differences between the files in the staging area and the latest version present.
* git diff [first branch] [second branch] ->differences between the two branches mentioned.
<br><br>

* git reset [file] ->unstages the file, but it preserves the file contents.
* git reset HEAD~1 ->undoes the last commit and preserves the changes locally.
* git reset [commit] ->undoes all the commits after the specified commit and preserves the changes locally.
* git reset --hard [commit] ->discards all history and goes back to the specified commit.
<br><br>

* git status ->command lists all the files that have to be committed.
<br><br>

* git rm [file] ->deletes the file from your working directory and stages the deletion.
<br><br>

* git log ->used to list the version history for the current branch.
* git log –follow[file] ->lists version history for a file, including the renaming of files also.
<br><br>

* git show [commit] ->shows the metadata and content changes of the specified commit.
<br><br>

* git tag [commitID] ->used to give tags to the specified commit.
<br><br>

* git branch ->lists all the local branches in the current repository.
* git branch [branch name] -> creates a new branch.
* git branch -d [branch name] -> deletes the feature branch.
<br><br>

* git checkout [branch name] -> used to switch from one branch to another
* git checkout -b [branch name] ->creates a new branch and also switches to it.
<br><br>

* git merge [branch name] ->merges the specified branch’s history into the current branch.
<br><br>

* git remote add [variable name] [Remote Server Link] ->used to connect your local repository to the remote server.
<br><br>

* git push [variable name] master ->sends the committed changes of master branch to your remote repository.
* git push [variable name] [branch] ->sends the branch commits to your remote repository.
* git push –all [variable name] ->pushes all branches to your remote repository.
* git push [variable name] :[branch name] ->deletes a branch on your remote repository.

<hr>
<br>
<p align="center">
	With :heart: by <a href="https://github.com/SIGMA-XI-VIT" target="_blank">Sigma Xi VIT</a>
</p>