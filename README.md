# unity-project-file-using-git
make sure you have a personal access token so you can clone a repo

# How to upload a unity project file on GitHub using git

step 1 Make the GitHub repo
make sure you enable the readme and gitignore and choose unity

step 2 make the project in unity

step 3 clone the GitHub repo in any folder (git clone "URL of GitHub repo")

step 4 copy the contents of the clone folder and paste it into the inside of the project file of unity

step 5 inside the folder of the unity project file run git bash 

step 6 run these commands 
```bash
git add .
git commit -m "commit 1"  #### change the number 1 into the current next number when updating
git push origin main
```

# How to make a new branch and upload it there

step 1 make a branch in GitHub website 

step 2 run the git clone 

step 3 copy the contents of the clone folder and place it into the updated project folder contents:(.gitignore, readme, git)

step 4 run these
```bash
git checkout branch1
git status
git add . 
git status
git commit -m "branch1"
git push origin head
```

step 5 your done check it at GitHub

# How to clone a branch
git clone -b branch_name (URL GitHub repo)
