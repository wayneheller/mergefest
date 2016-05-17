# Welcome to Mergefest

1. Edit this with your first name *here*.
----------------------------------------------

Now lets pull but take the master changes: 
`git pull -s recursive -X theirs`

(In your normal repos to get Jim's changes, use `git pull upstream master -s recursive -X theirs`)


2. Edit this with your last name *here*.
----------------------------------------------
Now lets pull but take our local changes: 
`git pull -s recursive -X ours`

(In your normal repos to keep your changes, use `git pull upstream master -s recursive -X ours`)

3. Edit this with your favorite fruit *here* and your favorite song *here*.
----------------------------------------------

Also, write anything you want below this line. :) 

\/\/\/\/\/\/\/\/\/\/\/\/\/
   
(**EDIT THIS LINE!**)
   
/\/\/\/\/\/\/\/\/\/\/\/\/\

Now lets pull but take both parts of our changes and their changes:
`git pull`

Open your favorite text editor and follow along. 

### *Side note:

* `git mergetool --tool=opendiff` - (for mac) will put you in an "interactive merge conflict" tool. ([pc alternative](http://stackoverflow.com/questions/426026/git-on-windows-how-do-you-set-up-a-mergetool))
* `git reset --hard HEAD~1` - will reset your git back to your last commit.
* `git clean -f` - will remove extra files that aren't in version control.
* https://www.gitignore.io/

