# welcome to mergefest

1. edit this with your name *here*.

now lets pull but take the master changes: 
`git pull upstream master -s recursive -X theirs`

(in your normal repos to get Jim's changes, use `git pull upstream master -s recursive -X theirs`)

now lets pull but take our local changes: 
`git pull -s recursive -X ours`

(in your normal repos to keep your changes, use `git pull upstream master -s recursive -X ours`)

now lets pull but take both parts of our changes and their changes:
`git pull`
