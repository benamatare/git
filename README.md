# H1 Notes on Good ole Git!
# H2 SOURCE > https://guides.github.com/introduction/git-handbook/

- What's Version Control?
A way of tracking changes on a project. Seeing what changes were made, who made those changes, when they were made and why the changes were needed.

- What's a distributed version control system?
Git is an example, it''s key feature is taht it allows full access to every file, branch and iteration of a project - and allows users to access a full, and self-contained history. Also they don't need a constant connection to a central repo!


- Basic Git Commands
`
- git init
Initialize a brand new repo, and start tracking. Adds a hidden subfolder within the directory that houses the internal data strucutre required for version control

- git clone
Create a local copy of a project that exists remotely (on git); clone includes hisotry, files, and branches

- git add
Stages a change, akin to taking a snapshot to include everything up to that point in time. Two-step process (Stage the changes), then 'git commit' those changes. (Board the ship, get the ship ready for take-off)

- git commit 
Saves the snapshot to the projects history (akin to taking a photo) - Anything that's been staged with 'git add' will become part of the snapshot of 'git commit'

- git status
Shows the status of changes; untracked, modified or staged

- git branch 
Shows the branches currently being worked on locally

- git merge
Merges lines of development together (weaving in the quilt). Used when you want ot merge a feature branch to another branch.

- git pull
Updates the local line of development with updates from the remote counterpart. If changes have been made to master, you can pull to update your local branch

- git push 
Update the remote repo with any commits made locally to a branch

