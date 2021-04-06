# Github Notes

## What is a Git repository

- A special folder, that git is tracking, this word means the same thing for git and for github.
- A git repository always has a .git file at its root. Without this file it isn't a git repo( short for repository) anymore
- to make a folder a git repository run the command.
- to show a . file, try `ls -a`

## How to make a folder

run the following command

```sh
git init
```

## How to store changes in Github

### Part I

add the files that we want git to watch

```sh
git add <filename1> <filename2> <filename3>
```

or you can tell git to watch all files by doing

```sh
git add .
```

### Part II

Commit the changes on those files, and add a message on what content was changed during that commit.

```sh
git commit -m "Your message would go right here"
```

## Setting up a github repository

### Go to github.com/new

- copy the instructions for the if you already have a project made
- paste them in your terminal and you are good to go probably

## Getting your code onto Github

### First stage and commit your changes ( all in Git, not in Github )

### Push changes to github
