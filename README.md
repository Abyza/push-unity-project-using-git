# unity-project-file-using-git

# How to upload a unity project file on GitHub using git

step 1. Make the GitHub repo
make sure you enable the read me and gitignore choose unity

step 2 make the project in unity
make sure you have a personal acccess token so you can clone a repo
step 3 clone the github repo in any folder (git clone "urlof github repo")

step 4 copy the contents of the clone folder paste it into the inside of the project file of unity

step 5 inside the folder of the unity project file run git bash 

step 6 run these commands 
git add .
git commit -m "commit 1"  #### change the number 1 into the current next number when updating
git push origin main

# How to make a new branch and upload it there

step 1 make a branch in github website 


step 2 run the git clone 

step 3 copy contents of clone folder and place it into the updated project folder contents:(.gitignore, readme, git)

step 4 run these

git checkout branch1
git status
git add . 
git status
git commit -m "branch1"
git push origin head
step 5 your done check it at github

# How to clone a branch
git clone -b branch_name https://github.com/username/repository.git
