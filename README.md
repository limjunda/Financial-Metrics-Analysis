# Financial-Metrics-Analysis
BCG Project

# How to setup your local and github for the project

# When you create a new folder
git init

# Setup of your SSH key, if too many argument error show, type it out manually instead of copy paste
ssh-keygen -t ed25519 -C your@email.com

# Find your SSH key, change to your own directory
cat "\Users\Lim Jun Da\.ssh\id_ed25519.pub"

# Copy the SSH key and got to GitHub -> Profile(Top right the icon) -> Setting -> SSH Key -> Create new SSH key

# Rename your local machine reference from master to main
# Use git log to check if you are using master or main
git log
git branch -m master main

# Setup your remote, origin is just a nickname for your local terminal reference
git remote add origin git@github.com:limjunda/Financial-Metrics-Analysis.git
git remote -v
git remote remove origin

# Example python file name is test.py
# This will create a new branch and push the files to the Github new branch
# Create a new branch locally
git checkout -b Nameofbranch
git add test.py
git commit -m "This is to add test.py"
git push --set-upstream origin Terminal
