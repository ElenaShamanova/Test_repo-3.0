# Git Guidelines

These Guidelines feature the most basic commands for your easy reference.

## How to set up your Git username:

With the command below you can configure your user name:

    git config --global user.name "insert your user.name here"

## How to setup your Git user email:

This command lets you setup the user email address you'll use in your commits:

    git config --global user.email "insert your user.email here"

## How to create a Repo

To create (initialize) a repository, use the following command in the terminal:

    git init

Don't use this command when a repo was intialized before as it'll create a conflict and make extra Git files forming in a system folder.

## How to add a file to the staging area:

The command below will add a file to the staging area. Just replace **filename_here** with the name of the file you want to add to the staging area.
    
        git add filename_here

## How to check a repo status:

This command will show the status of the current repository including staged, unstaged, and untracked files.

    git status

## How to commit changes with a message:

You can add a commit message without opening the editor. This command lets you only specify a short summary for your commit message.

    git commit -m "add your message here"

## How to see your commit history in Git:

This command shows the commit history for the current repository:  

    git log

## How to see your commit history in a shorter (oneline) list:

The following command shows the commit history for the current repo in "oneline" list:

    git log --oneline

## How to see changes made before committing them:

To see the changes before committing use the following command:

    git diff

## How to switch from the current commit of the project to the one you need:

To switch from the current commit to the you need use the following command:

    git checkout insert commit id

## How to switch to the most recent commit:

To switch to the most recent commit in the system use:

    git checkout master

## How to clear the terminal in VS Code:

To remove all the information reflected in the field "terminal" of the VS Code program use this command:

    clear

## How to create a branch:

By default, you have one branch, the main (master) branch. With this command, you can create a new branch:

    git branch branch_name
    
## How to switch between branches:

To switch from one branch to another use

    git checkout branch_name

## How to list branches:

You can view all created branes using the following command:

    git branch

It will also mark the current branch with an asterisk (*) and highlight it in green.

## How to delete a branch:

To delete a branch use the following command:

    git branch -d insert_the_branch_name_you_want_to_delete_here

## How to merge branches:

You can merge only 2 branches at a time. To do so, switch to the branch where you can add the content of another branch and use this command:

    git merge add_here_branchname_from_where you_want_to_add_info  

## How to ignore files in Git:

Create `.gitignore` file and commit it as usual.
Basically this command lets you hide a file or a group of files from reflecting it/ them when using `git status`. 

## How to show the commit log as a graph:

You can use `--graph` to get the commit log to show as a graph. Also, `--oneline` will limit commit messages to a single line.

    git log --graph --oneline

## How to show the commit log as a graph of all branches in Git:

Does the same as the command above, but for all branches.

    git log --graph --oneline --all
    
## How to work with remote repo on Git Hub:

Remote repos are required when you need to work on a project in group.
