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
you should [Download Git](https://git-scm.com/) from Git and install it.

![C](https://github.com/ALTONIBOT/Public/blob/main/img/C.png)

![D](https://github.com/ALTONIBOT/Public/blob/main/img/D.png)

## 2- Directory
> Write this commands with Windows Powershell (Recomended) or Command Prompt

* Create directory

@1 `{your path}:\> mkdir {directory name}`

✪ for example `D:\> mkdir test`

* Open directory

@2 `cd {path file}` 

✪ like `D:\> cd test`

![E](https://github.com/ALTONIBOT/Public/blob/main/img/E.png)

## 3- Start Git

* Initialize Git
> git init is a command that creates an empty Git repository or reinitializes an existing one. It is one of the first commands you should run when starting a new project with Git. It creates a hidden directory called .git that contains all the information and files required for version control.

@3 `git init`

![F](https://github.com/ALTONIBOT/Public/blob/main/img/F.png)

![G](https://github.com/ALTONIBOT/Public/blob/main/img/G.png)

* Show Status
> git status is a command that shows the current state of your Git working directory and staging area. It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git. It also provides helpful information depending on your current situation, such as branch and tracking info, untracked files, merge conflicts, etc...

@R `git status`

![H](https://github.com/ALTONIBOT/Public/blob/main/img/H.png)

* Put git files to stage
> git add is a command that adds new or changed files in your working directory to the Git staging area. The staging area is where you prepare the content for the next commit. You can use git add to select specific files, directories, or even parts of files for staging.

![I](https://github.com/ALTONIBOT/Public/blob/main/img/I.png)

`git add` -switch

| `{file name}` specied file name

| all ` -a`

| verbose ` -v`

| dry-run ` -n`

| force ` -f`

| interactive ` -i`

| patch ` -p`

| edit ` -e`

| update ` -u`

✪ for example `git add -a`

* Add git files to repository
> A git commit is a command that records changes to the repository. It creates a snapshot of your files and adds a message that describes what you have changed.

`git commit` -switch

| automatically add all modified files ` -a`

| write a message inline ` -m`

| interactively select which changes to include ` -p`

| put message {after switch} '{your message}'