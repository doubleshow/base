base
====

# Group folder

## Add a project

e.g.,

$ git submodule add git@github.com:ucdd2-sp15/website.git





# Project folder

A folder can hold a submodule, which points to a git repository.

for example, bigdiff/ed/fcq --> http://github.com/sikuli/fcq

Run the following git commands to

initialize

	$ git submodule init

fetch code

	$ git submodule update

checkout the master branch to work on code

	$ git checkout master

or another bracnh

	$ git checkout development

add and commit new changes

	$ git add ...
	$ git commit 

push changes

	$ git push origin master

In a different machine, to pull new changes from upstream, run 

	$ git pull

