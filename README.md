# The Terminal

The `terminal` allows you to executes commands and print outs their results as text.
You can open it with the shortcut `⌘ + t`.

You can do a lot with this simple text interface and learning to use it is
critical as often it's easier to manipulate from programs and a lot of specific
tools don't have Graphical User Interfaces *(GUI)*
and a simple Command Line Interface *(CLI)* is better than a bad GUI.

Your commands are executed from a directory, know as the **Working Directory**.

You can list what's in your working directory with `ls` (list)
```sh
ls
```

You can change the working directory with `cd` (Change Directory)
```sh
cd somedir # change the working directory to somedir
```

You can display the working directory with `pwd` (Print Working Directory)
```sh
pwd # print the working directory
```

You can get a short description and few simple examples from most commands with
`tldr` (To Long Didn't Read)
```sh
tldr cd # print the tldr page of the command cd
```

If you need full details, read the manual using `man` (Manual)
```sh
man cd # print the man page of the command cd
```
(as you can see, a lot more detailed, so that's often `tldr` is enough)

You can make a new directory with `mkdir` (Make Directory)
```sh
mkdir somenewdir # create a directory named somenewdir
```

*Other commonly used commands `chmod`, `chown`, `ps`, `kill`, and more !*

There are a few specials caracters for common directories :
- `.` is the current directory
- `..` is the parent directory
- `/` is the root directory
- `~` is your user home directory usualy (`/home/username/`)



# Git (Version Control System)
`git` is a version control system, it's use to collaborate and share code files.

It allows you to handle multiple version of the same project,
switch between them, merge them and much more.

It also serve as a backup and a way to go back to previous versions.

> :warning: note that **github** is not git, it's a web interface and webhost
for git, we use it because it's free for opensource, thanks github :+1:

Those are the `git` commands I use the most :
```sh
tldr git clone
tldr git add
tldr git commit
tldr git push
tldr git stash
```

If you want to go deeper into it checkout this guide
[learngitbranching.js](https://learngitbranching.js.org/?demo)



# Node (Runtime System)

`node` is used to run your JavaScript files.
It gives you an api that you can use to do all the things, more details in
[the documentation](https://nodejs.org/api/index.html)


```
tldr node
```



# NPM (Package Manager)

`npm` is node package manager

When we program, we like to share and reuse bits of code between project
instead of recoding everything all the time.  
`npm` allow us to do just that by creating packages of code that we can then
install and use in our other JavaScript files

```
tldr npm
```

# Code (Source Code Editor)

`code` is your defaults source code editor

You can open files from terminal with the command `code`

```sh
tldr code
```

Writing code will be your main occupation, be confortable with your editor.

**Learn the shortcuts.**

It's a powerfull tool with a lot of features, explore them and show your peers
your amazing discoveries.
