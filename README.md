# Tutorial for learning Git and GitHub.
How to Create a New Git Repository and Upload Files to GitHub
Go to GitHub
Click New Repository
Give a name (e.g., scRNAseq_tidyverse_project)
Do NOT check “Add README” (avoids conflicts)
Click Create Repository

👉 Copy the HTTPS URL, e.g.:

Step 1: Create a new repository on GitHub (do not add README initially).  
https://github.com/your-username/repo-name.git

Step 2: Navigate to your project folder using terminal(cd path/to/project).. 
cd path/to/your/project

Step 3: Initialize git using:   
git init

Step 4: Add files:  
git add .

Step 5: Commit files:  
git commit -m "Initial commit" 

Step 6: Add remote repository:(connect to github)  
git remote add origin https://github.com/your-username/repo-name.git

Step 7: Set main branch:..
git branch -M main

Step 8: Push to GitHub: git push -u origin main..
git push -u origin main
When prompted:

Username = your GitHub username
Password = Personal Access Token (PAT) (not your GitHub password)


Imp Note: Use Personal Access Token (PAT) instead of password when prompted.

Git Commands in one go.^M
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/repo-name.git
git push -u origin main

Common Mistakes to avoid while creating git repository^M

❌ Adding README on GitHub → causes merge conflicts
❌ Using password → use PAT
❌ Mixing SSH and HTTPS
