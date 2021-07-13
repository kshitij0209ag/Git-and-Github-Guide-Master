# **GIT & GITHUB GUIDE**

## **CREATING A GITHUB REPOSITORY** :-
   - ###  Creating a New Repository
    - `git init name_of_repository`
   - ### Make a Existing Folder Repository
    - Step 1 ->  `cd into the Folder`
    - Step 2 ->  `run git init`


## **CHECKING THE STATUS OF THE REPOSITORY** :-
  - `git status`

## **ADDING FILES TO THE STAGING AREA ** :-

- ### Adding all files in single Step(use any one of these)
    - `git add --all`
    - `git add "*"`
- ## Adding files one by one
    - `git add file_name`
- ## Adding files more than one but selected
    - `git add file_name1 file_name2`

## **COMMITING THE CHANGES** :-
- ### With the commiting message in one line
    - `git commit -m "commit message"`
- ### Write the commiting message in the Git Default editor
    -  `git commit`

## **Git Log**
- ### View Log
- `git log`

## **Git Branch**
- ### Make Branch/Reset/Checkout
- #### New Branch
- `git branch new_branch_name`
- #### Git checkout to new branch
- `git checkout new_branch_name`
- #### Check in which branch you are in now type->
- `git branch`
- #### Reset Commit  //this can be used to a previous commit in your history
- `git reset SHA`

## **Git Clone**
- `git clone remote_location clone_name`
- ### List of Git's project's remote->
- `git remote -v`
- ### Git Fetch
- `git fetch`
- ### After Git Fetch we merge local master to remote master
- `git merge origin/master`


