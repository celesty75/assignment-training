# Git
Git is a distributed version control system (DVCS). "Distributed" means that all developers within a team have a complete version of the project. A version control system is simply software that lets you effectively manage application versions. Git is able to do the following:
   * Keep track of all files in a project
   * Record any changes to project files
   * Restore previous versions of files
   * Compare and analyze code
   * Merge code from different computers and different team members

## Basic Git Commands
The basic git commands are given below.

### 1.Configuring Git
* **git config**
  This command sets the author name and email address respectively to be used with your commits.  
    ```
    $ git config –global user.name “[name]”  
    $ git config –global user.email “[email address]” 
    ```
### 2.Starting a New Local Repository with Git    
* **git init**
  This command is used to start a new repository.
    ```
    $ git init [repository name]
    ```
* **git clone**
  This command is used to obtain a repository from an existing URL.
    ```
    $ git clone [url]
    ```
### 3.Staging Files
* **git add**
  This command adds a file to the staging area.
    ```
    $ git add [file]
    ```
  * This command adds one or more to the staging area.
    ```
    $ git add * 
    ```
* **git status**
  This command lists all the files that have to be committed.
    ```
    $ git status
    ```
* **git rm**
  This command deletes the file from your working directory and stages the deletion.
    ```
    $ git rm [file]
    ```
* **git diff**
  This command shows the file differences which are not yet staged.
    ```
    $ git diff
    ```
* **git log**
  * This command is used to list the version history for the current branch.
    ```
    $ git log
    ```
* **git show**
  * This command shows the metadata and content changes of the specified commit.
    ```
    $ git show [commit]
    ```
### 4.Commiting to a repository
* **git commit**
  This command records or snapshots the file permanently in the version history.
    ```
    $ git commit -m “[ Type in the commit message]”
    ```
* **git reset**
  This command unstages the file, but it preserves the file contents.
    ```
    $ git reset [file]
    ```
 ### 5.Push and Pull To and From a Remote Repository
 * **git remote**
  This command is used to connect your local repository to the remote server.
    ```
    $ git remote add [variable name] [Remote Server Link]
    ```
* **git push**
  This command sends the committed changes of master branch to your remote repository.
    ```
    $ git push [variable name] master
    ```
  This command sends the branch commits to your remote repository.
    ```
    $ git push [variable name] [branch]
    ```
* **git pull**
  This command fetches and merges changes on the remote server to your working directory.
    ```
    $ git pull [Repository Link]
    ```
### 6.List of Git Commands for Working with Branches
* **git branch**
  This command lists all the local branches in the current repository.
    ```
    $ git branch
    ```
  This command creates a new branch.
    ```
    $ git branch [branch name]
    ```
  This command deletes the feature branch.
    ```
    $ git branch -d [branch name]
    ```
* **git checkout**
  This command is used to switch from one branch to another.
    ```
    $ git checkout [branch name]
    ```
  This command creates a new branch and also switches to it.
    ```
    $ git checkout -b [branch name]
    ```
* **git merge**
  This command merges the specified branch’s history into the current branch.
    ```
    $ git merge [branch name]
    ```
  
