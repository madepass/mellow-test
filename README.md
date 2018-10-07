# mellow-test



to clone:
`cd` to whichver directory on your machien you want this repo to live in.
find the url of repo on github or whatever git provider you are using.

run:
`git clone <url>`



`git status` tells you a brief summary of the state of your code.

`git diff` will you what has changed so far.

but so far you have not actually changed anything at all as far as git is concerned.


To register the change to git you need the following:

`git add <filename>`. Do this to all files that you've 1) modified 2) want git to know you modiefied it.

`git commit -m "some message"`.  A comment is required so you just have to live with it.

`git push origin master`. DOnt worry about origin. its just incantation as far as you are concerend for now.



#checkout

`git checkout ` allows you to traverse the your ocmmmit tree.

But honestly you will just be using it to reset your changes to top of tree.

To go back to an old hash:

`git checkout <hash>`

The more practical use case:
TO undo all the changes you did to a file:
`git checkout <filename>`. This will revert a file to top of tree.
`git checkout` by itself will revert your entire repo to top of tree. be pretty careful about this.