git init
git config --global user.name "name"
git config --global user.email "email"
git status
git add "<filename>"
git commit -m "message"
git branch
git branch -M main   #changes to branch main
git config user.name  #to get username
git push origin main   #to push from origin to main
git restore "<filename>"  # discarding out local changes
git add .   #adding all
git clone <code url>
git restore --staged "<filename>"   # to restore after doing git add
git reset "<filename>"     # same as above
git diff --staged  # to check which are alreade commited or staged
git branch <branch name>  # to create a branch
git checkout <branch name>  # to move to the branch
