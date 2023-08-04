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

## 2- Directory
> Write this commands with Windows Powershell (Recomended) or Command Prompt

* Create directory

@1 `{your path}:\> mkdir {directory name}`

✪ for example `D:\> mkdir test`

* Open directory

@2 `cd {path file}` 

✪ like `D:\> cd test`

## 3- Start Git
> @Number(1,2,3,...): Steps that are done step by step and usually after doing it once, there is no need to do it again in a file.

> @R: It is usually done routinely.

* Initialize Git
> git init is a command that creates an empty Git repository or reinitializes an existing one. It is one of the first commands you should run when starting a new project with Git. It creates a hidden directory called .git that contains all the information and files required for version control.

@3 `git init`

* Show informations
> git status is a command that shows the current state of your Git working directory and staging area. It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git. It also provides helpful information depending on your current situation, such as branch and tracking info, untracked files, merge conflicts, etc...

@R `git status`

> According to the documentation1, git log is a command that shows the commit logs of a Git repository. It can be used to list the commits that are reachable from a given revision or branch, and to filter or format the output in various ways.

@R `git log` -{switch}

| `–oneline` show each commit on a single line with a shortened commit hash and the first line of the commit message

| `–decorate` show the branch or tag names of each commit

| `–stat` show the number of insertions and deletions for each file changed by each commit

| `-p` or `–patch` show the diff for each commit, i.e. the changes made to each file by each commit

@R `git diff` Show the diff between the staging area and the working tree

* Put git files to stage
> git add is a command that adds new or changed files in your working directory to the Git staging area. The staging area is where you prepare the content for the next commit. You can use git add to select specific files, directories, or even parts of files for staging.


@R `git add` -{switch}

| `{path\file name}` stage a specific directory or file

| ` -A` stage all changes in the entire repository

✪ like `git add -A {path}`  stage all changes in a specific directory or file

✪ like `git add -A *.html`  stage all changes in files that have a .html extension

| ` -v` git add -v is a command that adds new or changed files in your working directory to the Git staging area, and also shows you what changes are being staged. The -v option stands for verbose, and it makes git add print a summary of the changes for each file that is added

| ` -n` git add -n is a command that performs a dry run of git add. It shows what files would be added to the staging area, but does not actually add them. It is useful for checking what changes you have made before committing them

| ` -f` The command git add -f is used to force adding a file or a directory to the Git staging area, even if it is ignored by the ~.gitignore~ file. This can be useful if you want to override the default ignore rules for some files that you need to track in your repository

✪ like `git add -f {path\file name}`

✪ like `git add -f bar/` Force add the entire directory ~bar/~ and its contents to the staging area, even if they are listed in the ~.gitignore~ file

| ` -i` The command git add -i is used to interactively stage changes to the Git staging area. This means that you can choose which files or parts of files you want to include in your next commit, without having to use separate commands for each file

✪ like `git add -i {path\file name}` Enter the interactive mode for only the file {path\file name}.

✪ like `git add -i bar/` Enter the interactive mode for only the directory bar/ and its contents.

| patch ` -p`

| edit ` -e`

| update ` -u`

@R `git revert`

* Add git files to repository
> A git commit is a command that records changes to the repository. It creates a snapshot of your files and adds a message that describes what you have changed.

@R `git commit` -{switch}

| automatically add all modified files ` -a`

| write a message inline ` -m`

| interactively select which changes to include ` -p`

| put message {after switch} '{your message}'