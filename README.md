<!-- hi -->
<!-- clone - crea
checkout
-b
status
push
-u
pull
add
commit
-m
-a
-am
branch
-a
-d
merge -->
# clone:
Creates a local copy of a remote repository from GitHub on your computer.
# status: 
Shows the current state of your working directory. It tells you which files are modified, staged for the next commit, or untracked.
# Branching & Navigationcheckout
# -b [name]: 
Creates a new branch and immediately switches you to it.
# branch -a: 
Lists all branches in the repository, including both local and remote-tracking branches.
# branch -d [name]:
 Deletes a local branch that has already been merged.
 # merge [branch]: 
 Combines the history and changes from a specified branch into your current branch.
 # Saving & Sharing Changesadd: 
 Moves changes from your working directory to the staging area, preparing them to be committed.
 # commit -m "[msg]": 
 Records a snapshot of your staged changes to the local history with a descriptive message.
 # commit -a: 
 Automatically stages every file that is already tracked before committing.
 # commit -am "[msg]": 
 A shortcut that combines -a (stage all tracked files) and -m (add a message) into one command.
 # push -u [remote] [branch]: 
 Uploads your local commits to a remote repository. The -u flag sets the upstream tracking relationship, so future pushes for that branch
 # pull: 
 Fetches changes from the remote repository and merges them into your current local branch.