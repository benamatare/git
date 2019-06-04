__Git Cheatsheet / Notes__
__SOURCE > https://guides.github.com/introduction/git-handbook/__

####- What's Version Control?
A way of tracking changes on a project. Seeing what changes were made, who made those changes, when they were made and why the changes were needed.

####- What's a distributed version control system?
Git is an example, it''s key feature is taht it allows full access to every file, branch and iteration of a project - and allows users to access a full, and self-contained history. Also they don't need a constant connection to a central repo!


####Basic Git Commands
__- git init__
Initialize a brand new repo, and start tracking. Adds a hidden subfolder within the directory that houses the internal data strucutre required for version control

__- git clone__
Create a local copy of a project that exists remotely (on git); clone includes hisotry, files, and branches

__- git add__
Stages a change, akin to taking a snapshot to include everything up to that point in time. Two-step process (Stage the changes), then 'git commit' those changes. (Board the ship, get the ship ready for take-off)

__- git commit__
Saves the snapshot to the projects history (akin to taking a photo) - Anything that's been staged with 'git add' will become part of the snapshot of 'git commit'

__- git status__
Shows the status of changes; untracked, modified or staged

__- git branch__
Shows the branches currently being worked on locally

__- git merge__
Merges lines of development together (weaving in the quilt). Used when you want ot merge a feature branch to another branch.

__- git pull__
Updates the local line of development with updates from the remote counterpart. If changes have been made to master, you can pull to update your local branch

__- git push__
Update the remote repo with any commits made locally to a branch

