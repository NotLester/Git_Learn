'git init' -> Powers folder to be managed by git and initializes new repository with '.git' folder.
           -> Also re-initializes repo

'git status' -> Shows what files are tracked in the repository.
'git add <FILES>' -> Move file from working area to staging area.
'git rm --cached <FILES>' -> Remove file from staging area to working area.

Three areas in git:
    1) Working Area: Untracked files are contained in this area.(areas not handled by git)
    2) Staging Area: Tracked files which are not committed yet are stored in this area. (The files which are going to be part of next version)
    3) Committed/Repository Area: Contains details of the previous versions of the project. 

'git commit -m <MESSAGE>' -> make a version out of the current version ie moves files from staging tare to repository.
'git log' -> Gives info of all versions of the project.
'git restore <FILES>' -> All files are brought to latest committed area.
'git restore --staged <FILES>' -> removes file from changes from staging area to working area.

difference between git rm and git restore:
    if we wont to move whole file back to untracked state then do git rm, 
    else if u just want changes to be moved in working or staging area then use git restore.

'git diff <V1> <V2>' -> shows difference in contents between 2 commits.

'git remote add origin <LINK>' -> add local repo to github repository
'git push <CONNECTION_NAME> <BRANCH_NAME>' -> pushes local repo to github repository.

### Recommended practice
-make changes
- git add <files>
- git commit 
- git pull
- git push 