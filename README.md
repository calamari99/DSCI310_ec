# UBC_DSCI310

## Guide to Git and Version Control
Common 
- `git status`: status of current changes in repo
- `git clone <URL>`: one time download from git rep to local machine

Changes:
- `git add <FILE>`: add the </FILE>s to the staging area

- `git commit <FILE>` commit changes <FILE> 
    - `git commit -m "MESSAGE"`: creates the git message.

- `git push <FILE>` push changes to git
    - e.g. `git push origin main` which sends code from branch to origin.

- `git pull <where> <what>`: take remote commits on `</what>`, and pull from `where`
    - e,g, `git pull origin main`


### Conventional folders:
- data
- code

Note: Git Tracks folders in a peculiar way.
- Github needs a file in a folder for the folder to appear on origin

### Branches
- added branches
-   `git branch <name>` creates a new branch called <name>

swap branches
- `git checkout <name>` changes to branch <name> [classic notation]
    - e.g. git checkout main
- `git switch <name>` [modern notation]

- `git push -u origin <branchname>` push branch to github origin folder

