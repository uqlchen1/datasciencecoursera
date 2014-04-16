CloneRepo
===========
git clone https://github.com/jtleek/datasharing.git
# Clones your fork of the repository into the current directory in terminal

cd jtleek
# Changes the active directory in the prompt to the newly cloned "jtleek" directory

git remote add upstream https://github.com/jtleek/datasharing.git
# Assigns the original repository to a remote called "upstream"

git fetch upstream
# Pulls in changes not present in your local repository, without modifying your files


git push origin master
# Pushes commits to your remote repository stored on GitHub


git fetch upstream
# Fetches any new changes from the original repository
git merge upstream/master
# Merges any changes fetched into your working files





git remote add origin https://github.com/uqlchen1/datasciencecoursera/CloneRepo.git

