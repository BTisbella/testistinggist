$ git clone https://github.com/username/Spoon-Knife.git
# Clones your fork of the repository into the current directory in terminal
$ cd Spoon-Knife
# Changes the active directory in the prompt to the newly cloned "Spoon-Knife" directory
git remote add upstream https://github.com/octocat/Spoon-Knife.git
# Assigns the original repository to a remote called "upstream"
git fetch upstream
# Pulls in changes not present in your local repository, without modifying your file
