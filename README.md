author: kristin scott \
test repo

today, i learned how to add and  update github repositories from the command line. 

to initialize a repo on your computer: \
mkdir <repo_name> \
cd <repo_name> \
git init <repo_name>

then, add this repo to your github using GUI

git remote add origin <https link to repo on github>

to add/update files:

create a file called file_name. then,...

git add <file_name> \
git commit \
gut push -u origin master

i just learned that if you make changes to git repo using GUI, you have to git pull the repository before pushing changes from terminal. 

