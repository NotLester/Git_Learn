'git init' -> Powers folder to be managed by git and initializes new repository with '.git' folder.
           -> Also re-initializes repo

'git status' -> Shows what files are tracked in the repository.
            
'git add <>' -> Move file from working area to staging area.
'git rm --cached <>' -> Remove file from staging area to working area.

Three areas in git:
    1) Working Area: Untracked files are contained in this area.(areas not handled by git)
    2) Staging Area: Tracked files which are not committed yet are stored in this area. (The files which are going to be part of next version)
    3) Committed/Repository Area: Contains details of the previous versions of the project. 

'git commit -m <MESSAGE>' -> make a version out of the current version ie moves files from staging tare to repository.
'git log' -> Gives info of all versions of the project.
'git restore <FILES>' -> All files are brought to latest committed area.
'git restore --staged <FILES>' -> removes file from changes from staging area to working area.