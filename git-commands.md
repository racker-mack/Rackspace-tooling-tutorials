## git commands for rackspace ##

##clone directory from github

git clone "repository"

#example
git clone https://github.com/racker-mack/Rackspace-tooling-tutorials.git

##switch branch or directory
git checkout <branch name>

#example
git checkout features

##pull any changes
git pull

##add document(s) to be pushed
##notes- need to add a file any time changs are made to the file
git add <name-of-file>

#example:
git add git-commands.md

##commit changes##
git commit -m "<notes on commit>"

#example
git commit -m "added git-commands.md"

##push changes to github

git push origin <branch name>
git push origin features
