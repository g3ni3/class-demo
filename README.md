# This is my project!

This is some information **about** my project! If you want to know more, [here is my website.](http://g3ni3.com)

- first thing
- second thing

```
var x = 100;
```


# GITTING STARTED
open a folder, and a README.md doc (customary thing used to describe your program when it comes in a downloaded package)

in terminal, type
```
$ git init
```
will create a **REPOSITORY**, hidden folder called .git (visible in atom) which tracks all the changes you make

- to have your changes be logged, you have to commit it

- you'll need to add a file to the stage before you can commit it (staging a file)
```
$ git add README.md
```
then commit those files on the stage with
```
$ git commit -m "the beginning of my project"
```
- -m adds a message to your commit, so you have a description of what it is

To check if your files have been committed, you can type
```
$ git status
```
and that will show you which files have been recently modified

- if you create a new file, and did not commit it, you will see the new file under "untracked files" in your terminal when you check status
- you can use "git add [file]" and/or "git commit -m" (after staging it) to start tracking it

- YOU HAVE TO ADD THE FILE TO THE STAGE EVERY TIME YOU MAKE A CHANGE
- Which files do you want to be committed, and which files do you want to be tracked?

```
$ git .
```
adds all your files in your project folders to the stage so you don't have to type them all individually!

- your workflow would look like: work on your file, save changes, add to stage, commit it; repeat
