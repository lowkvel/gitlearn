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

# check difference between changes
git diff                    # view difference before <add>
git diff HEAD               # view difference after <add>, use this command before <commit>

#####
# branching operations
#####

