# Git Basics

Hi there! This file contains a basic guide for using [Git](https://git-scm.com/) and [GitHub](https://github.com/). If you have never used either of those before, that's ok, this guide is suitable for total beginners. Let's get started.


## What is Git?

Git is a computer program that creates a history of changes to files. This is useful (and often necessary) because it allows programmers to easily organize and track changes to the software that they create.


## Install Git

First you will need to install Git on your computer. You can download an installer for your system [here](https://git-scm.com/downloads). While you are downloading the installer, you can move on to the [next section](#github-account).


## GitHub Account

GitHub is a social coding platform used by many [open source](https://opensource.org/) projects. [Sign up](https://github.com/join) for a free GitHub account so that you can contribute to existing projects (or start your own projects).

Once you have setup your GitHub account, go back to the [previous section](#install-git) and finish installing Git.


## Using Git

To use Git, we will use a command-line interface instead of a graphic interface.

For Windows:
* Open your Start Menu and search for "git bash".
* You should see a program named "Git Bash".
* Open the git bash program.
* Type the command `git --version` and hit enter.
* The result should be something like this:

![git version 2.9.2-windows.1](screenshots/windows-git-bash.png)


For Mac or Linux:
* Open your Terminal program.
* Type the command `git --version` and hit enter.
* The result should be something like this:

![git version 1.9.1](screenshots/ubuntu-terminal-git.png)

If you had any trouble with the previous steps, please ask for help and we will get you back on track.

Now we will try some [basic Git commands](https://docs.gitlab.com/ee/gitlab-basics/start-using-git.html#basic-git-commands).


### Help Menu

Type `git help` and hit enter. You should see some text printed to your terminal window:
```
usage: git [--version] [--help] [-C <path>] [-c name=value]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p|--paginate|--no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

The most commonly used git commands are:
   add        Add file contents to the index
   bisect     Find by binary search the change that introduced a bug
   branch     List, create, or delete branches
   checkout   Checkout a branch or paths to the working tree
   clone      Clone a repository into a new directory
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   fetch      Download objects and refs from another repository
   grep       Print lines matching a pattern
   init       Create an empty Git repository or reinitialize an existing one
   log        Show commit logs
   merge      Join two or more development histories together
   mv         Move or rename a file, a directory, or a symlink
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects
   rebase     Forward-port local commits to the updated upstream head
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index
   show       Show various types of objects
   status     Show the working tree status
   tag        Create, list, delete or verify a tag object signed with GPG

'git help -a' and 'git help -g' lists available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
```

And if you ever need help with an individual git command, use `--help` like this:
```
git status --help
```
Press the `q` key to quit from the help screen.

### More resources

[Git tutorial for beginners](https://youtu.be/0fKg7e37bQE). 
