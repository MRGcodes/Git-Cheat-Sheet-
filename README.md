# Command Cheat Sheet 

## Initialize A Repositroy

* git **init**
    * *Initialize new repository*
* git **clone** *repositroy-url*
    * *clone an existing remote*
* git **remote add origin** *repository-url*
    * *connect a local repository to remote*

## Basic Commands

* git **status**
* git **add** *file-name* or [ . ]
* git **commit** -m "*message*"
* git **push origin** *branch-name*
* git **pull origin** *branch-name*

## Branching Commands

* git **checkout** -b *new-branch-name*
    *  *creates new branch* 
* git **checkout** *branch-name*  
    * *switch between branches*
* git **branch**  
    * *lists local branches*
* git **branch -r** 
    * *lists remote branches*
* git **branch -d** *branch-name* 
    * *deletes local branch*
* git **push origin --delete** *branch-name*
    * *deletes remote branch*

## Merging and Stashing 

* git **merge** *branch-name*
    *   *integrates changes from another branch*
* git **stash** 
    * *temporarily saves changes*
* git **stash apply** 
    * *restores temporary changes*

## Viewing Change and Commit History

* git **diff**
    * *shows changes between commits and the working directory*
* git **log**
    * *displays commit history*
* git **log --oneline**
    * *displays a summarized commit history*

## Tagging

* git **tag**  
    * *lists all tags*
* git **tag** *tag-name*  
    * *creates a new tag*
* git **tag** *tag-name* *commit-id*  
    * *assigns a tag to a specific commit*
* git **tag -a** *tag-name* -m "*message*"  
    * *creates an annotated tag with a message*
* git **tag -d** *tag-name*  
    * *deletes a local tag*
* git **push origin** *tag-name*  
    * *pushes a tag to the remote repository*
* git **push origin --tags**  
    * *pushes all tags to the remote repository*


## Undoing Changes

* git **checkout --** *file-name*  
    * *reverts changes in the working directory for a specific file*
* git **reset**  
    * *unstages a file, keeping changes in the working directory*
* git **revert** *commit-hash*  
    * *Creates a new commit that undoes changes from a specified commit*
* git **merge --abort**  
    * *aborts the current merge process and returns to the pre-merge state*

  
