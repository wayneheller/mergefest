# Welcome to Mergefest

add this as the remote: `git remote add upstream https://github.com/outdoola/mergefest`

once you add this make sure your remote is there with `git remote -v`

1. Edit this with your first name *Hello!!*.
----------------------------------------------

Lets try to `git pull upstream master` and see what happens.

We have a merge conflict! Yay!

Let's reset to our last change by running `git reset --hard HEAD~1`

Now lets pull but take the master changes: 
`git pull upstream master -s recursive -X theirs`

(In your normal repos to get Jim's changes, use `git pull upstream master -s recursive -X theirs`)


2. Edit this with your last name *here*.
----------------------------------------------
Now lets pull but take our local changes: 
`git pull upstream master -s recursive -X ours`

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

#### What is a `.gitignore` file?

It is a way to say, "just ignore these files in my git repo, pretend they don't exist to git." All you have to do is create a `.gitignore` file in the base of your git repo and add any file matching patterns to it. for example, you may just want to ignore all ipython notebook checkpoints or all mac specific files that aren't part of your code in that repo.

* Check out [gitignore.io](https://www.gitignore.io/). It will help you create `.gitignore` files. [more on .gitignore](https://git-scm.com/docs/gitignore)
* `git reset --hard HEAD~1` - will reset your git back to your last commit.
* `git clean -f` - will remove extra files that aren't in version control.
* `git mergetool --tool=opendiff` - (for mac) will put you in an "interactive merge conflict" tool. ([pc alternative](http://stackoverflow.com/questions/426026/git-on-windows-how-do-you-set-up-a-mergetool)). [more on mergetool](https://git-scm.com/docs/git-mergetool) 
