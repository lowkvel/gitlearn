# gitlearn

######
# basic operations
#####

# git initialization using <init>
git init                    # git repository initialization

# status checking using <status>
git status                  # status checking

# stage changes (newly added or modified) for tracking using <add>
git add README.md           # stage a specific file for tracking
git add .                   # stage all files for tracking

# commit changes using <commit>
git commit -m "comments"    # commit with a comment

# view committed log using <log>
git log                     # all log
git log --pretty=short      # all log in a simplified format
git log README.md           # all log for a specific file
git log -p                  # all log with difference between commits
git log --graph             # view log in graph mode

# check difference between changes
git diff                    # view difference before <add>
git diff HEAD               # view difference after <add>, use this command before <commit>

#####
# branching operations
#####

# view all branches using <branch>
git branch                  # the branch with a '*' on the left is the branch we currently working on

# create a new branch using <branch> with a name after it
git branch feature-a        # create a branch with "feature-a" as its name

# switch to another branch using <checkout>
git chechout feature-a      # switch to the branch called "feature-a" we just created above

# create a new branch using <checkout> and switch to it
git checkout -b feature-a   # create a new branch with "feature-a" as its name and switch to it

# merge a branch using <merge --no-ff>
git checkout main               # switch back to main before merging
git merge --no-ff feature a     # merge feature-a into main

#####
# reset operation and conflict fix
#####

# reset to old version using <reset --hard> with destination hash code
git reset --hard hash_code

# view git command log using <reflog>
git reflog

# 
