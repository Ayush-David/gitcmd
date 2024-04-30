# gitcmd


git config --global user.name "Ayush-David"
git config --global user.email "ayushdavid14@gmail.com"

git config --global init.defaultBranch main :sets the default branch to main
 git push origin main: pushing changes to GitHub
git commit -m "message"
git status :
git remote add origin <link>
git remote -v

git pull origin main :to fetch and download contentd from a remote repo to local system
git branch :to check branch
git checkout <branch name>:to navigate
git checkout -b <new branch>:to create new branch
git branch -M main :to rename branch
git branch -d <branch to delete>
git merge <branch name>:to merge to branch

git remote add upstream <remoteurl>
git fetch upstream
git merge upstream/main
git push origin main
  

git request-pull <branch> <url>
git submodule add <url>
 git config --global alias.<alias name > <command>
