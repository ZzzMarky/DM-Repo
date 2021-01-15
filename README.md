# DM-Repo
Design Methodology group repo
How to commit changes in git and push to github repository:
$ cd DM-Repo   //this will change directory to put everything in DM-Repo
$ ls           // shows list of files in repo
$ git remote -v  // not sure what this do.
$ touch Filename.md  //this creates file in the folder but not the folder on github
$ git status   //this shows which files are connected/tracked to github repo
$ git add .   //adds all untracked files
$ git status   //to double check it updated
$ git commit -m "blah blah" //adds a message to the thing being commited (filename.md)
$ git status //to see 1 commit or something
$ git log  //to see whats happening, or what you have done as far as messages
$ git show-ref // to see where we need to put this thing so that it connects to github
$ git push origin Head:main //it is officialy updated in git (might be git push origin master, but that didnt work for me)
