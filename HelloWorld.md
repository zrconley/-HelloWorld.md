##
git clone https://github.com/zrconley/-HelloWorld.md
# Clones your fork of the repository into the current directory in terminal
cd Spoon-Knife
# Changes the active directory in the prompt to the newly cloned "Spoon-Knife" directory
git remote add upstream https://github.com/zrconley/datasciencecoursera
# Assigns the original repository to a remote called "upstream"
git fetch upstream
# Pulls in changes not present in your local repository, without modifying your files

git remote add origin https://github.com/zrconley/datasciencecoursera.git
git push -u origin master
