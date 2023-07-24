# Git

## Git Structure

* What is Git?
> Git is like a garden where you have the number of trees, branches and fruits of this garden, and you can even create restrictions that only you have access to this garden or that a few other people have access or even be made available to the public!

![A](https://github.com/ALTONIBOT/Public/blob/main/img/A.png)

> In essence, this garden is your "Account", the trees are "Repositories" and the branches are "branche", and the fruits of the tree are your "Files" and "Projects"...

![B](https://github.com/ALTONIBOT/Public/blob/main/img/B.png)

> Gate's capabilities can be used as a team، which means that each member of a team can develop a branch and eventually integrate into the main branch.


# Starting with Git

## 1- Install Git
you should download git from [Git](https://git-scm.com/) and install it.

![C](https://github.com/ALTONIBOT/Public/blob/main/img/C.png)

![D](https://github.com/ALTONIBOT/Public/blob/main/img/D.png)

## 2- Create Directory
> Write this commands with Windows Powershell (Recomended) or Command Prompt

@1 `{your path}:\> mkdir {path name}` for example `D:\> mkdir test`

* Open directory

@2 `cd {path file}` like `D:\> cd test`

## 3- Start Git

* Initialize Git
> git init is a command that creates an empty Git repository or reinitializes an existing one. It is one of the first commands you should run when starting a new project with Git. It creates a hidden directory called .git that contains all the information and files required for version control.

@3 `git init`

* Show Status
> git status is a command that shows the current state of your Git working directory and staging area. It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git. It also provides helpful information depending on your current situation, such as branch and tracking info, untracked files, merge conflicts, etc...

@R `git status`

* Add Git files to repository
> git add is a command that adds new or changed files in your working directory to the Git staging area. The staging area is where you prepare the content for the next commit. You can use git add to select specific files, directories, or even parts of files for staging.

`git add`
Switch:
`{file name}` specied file name | `-a` all |`-v` verbose | `-n` dry-run | `-f` force | `-i` interactive
`-p` patch
`-e` edit
`-u` update
and etc...
