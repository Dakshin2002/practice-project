This is my Git practice project.
Task 2 – Initialize Git
git init--->You are telling Git to start tracking this project.
Task 3 – Add Files to Staging
git add .
Prepare all files to be saved in Git.
OR
git add file_name
Check status:
git status
Task 4 – First Commit
git commit -m "Initial project files added"
Save the first version of your project.
Task 5 – Modify a File
Edit index.html
again check status:
git status
git add index.html
git commit -m "Updated index file with paragraph"

"NEXT PROCESS IN GITHUB"
ask 9 – Push to GitHub

Create repo in GitHub.

Example repo name:

git-practice-project

Then connect:

git remote add origin https://github.com/username/git-practice-project.git

Push:

git push -u origin main