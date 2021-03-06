# Revisions and the Cloud Class 3
*version control* is a system that allows you to revisit versions of a file or set of files by recording changes
- centralized version control is focused on collaboration where clients can access the same files
- distributed version control allows clients to replicate files in case of corruption

## Git
- **snapshots** = each time you save data in a file system it means it is a *commit*
- files in Git can reside in three main states: committed (data stored in local database), modified (data changed but not committed), and staged (flagged a file's changed version to be committed in the next snapshot)

**Graphical clients**
- Git uses GUI tools, but also can use third-party tools

## Initial Customization
* git config allows to control variables
 ## Importing Git Repository
 1. Switch to target project's directory
    a. cd test
 2. cloning
    a. git clone URL
    
 ## Workflow
 **Local Repository Structure**
 The local Git repository has three components:
 1. working directory: the files reside here
 2. index: the area used for staging
 3. head: points to the most recent commit
 
 **Saving Changes**
 All files are either tracked or untracked. Untracked were not in the last snapshot and do not currently reside in staging area.
 
 **Life Cycle of File Status**
1. After you edit a file, git flags it as modified as you made changes
2. you staged the modified file
3. then you commit staged changes

- *check file status* = git status

**Tracking and Staging a New File**
- single file = git add filename
- all files= git add *
- resetting = git reset

**Committing a File**
- After staging one or multiple fies, you should commit the changes and record what you did by using      git commit -a "made change ....."
- committing all changes is        git commit -m or -a

**Rule is ACP**
- git add filename
- git commit -m "personal message for me to remember what I saved"
- git push origin master


- pushing changes to a remote repository is.   git push origin master

**stashing changes**
- when you are not ready to commit to changes but do not want to lose them, use git stash to temporarily remove changes and hides them, then you can use git stash apply to retrieve hidden changes.

**Clean git history**
it is important to save my changes with why I saved them with a personal message to see what the changes were.
- this taught me how to use the terminal to use vscode directly instead of github. I also learned how to save my data into messages so I have more organization with my coding.

**to get to git master through terminal**

1. pwd
2. documents
3. ls
4. cd projectsgit p
5. ls
6. cd codefellows
7. ls
8. cd reading-notes
9. code .
[<= back](README.md)
