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
Task 6 – Create a New Branch
git branch feature-ui
Switch to the branch:
git checkout feature-ui
(OR)
git switch feature-ui
Task 7 – Add New Feature

Edit style.css

p{
  background-color: yellow;
}

Then commit:

git add .
git commit -m "Added background color"
Task 8 – Merge Branch

Switch back to main:

git checkout main

Merge feature branch:

git merge feature-ui
