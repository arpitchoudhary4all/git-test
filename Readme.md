Git Test

->      To check git version
         
        git --version

->      To configure username to be used by git

        git config --global user.name "Your Name"

->      To configure email to be used by git

        git config --global user.email "Your Email"

->      To check the default git configurations

        git config --list

->      To initialize git

        git init

->      To checck git repository status

        git status

->      To add files to the staging area of your Git repository

        git add .

->      To commit the current staging area to your Git repository

        git commit -m "first commit"

->      To check the log of the commits to your Git repository

        git log --oneline

->      To check out some file from a particular commit, find the number of that commit using the git log
        
        git checkout <commit's number> <file'name>

->      To discard the effect of the previous operation and restore index.html to its state at the end of last commit
        
        git reset HEAD index.html + git checkout -- index.html
