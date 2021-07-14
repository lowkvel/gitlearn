# gitlearn
 
# git initialization using <init>
git init

# status checking using <status>
git status

# stage changes (newly added or modified) for tracking using <add>
git add README.md
git add .

# commit changes using <commit>
git commit -m "comments"

# view committed log using <log>
git log                     # all log
git log --pretty=short      # all log in simplified form
git log README.md           # all log for a specific file
git log -p                  # all log with difference between changes

# check difference between changes
git diff
git diff HEAD