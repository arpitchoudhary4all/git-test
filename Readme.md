Git Test

1. To check git version = git --version

2. To configure username to be used by git  = git config --global user.name "Your Name"

3. To configure email to be used by git  = git config --global user.email "Your Email"

4. To check the default git configurations  = git config --list

5. To initialize git  = git init

6. To checck git repository status   =  git status

7. To add files to the staging area of your Git repository  = git add .

8. To commit the current staging area to your Git repository  = git commit -m "first commit"

9. To check the log of the commits to your Git repository  = git log --oneline

Note  - To check out some file from a particular commit, find the number of that commit using the git log
        git checkout <commit's number> <file'name>

Note  - To discard the effect of the previous operation and restore index.html to its state at the end of last commit
        git reset HEAD index.html + git checkout -- index.html

