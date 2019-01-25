# How to contribute

The goal of this file is to outline how to contribute to the Asheville Community Data Library.  There are four different areas: **Starting Git/GitHub**, **GitHub Issue Tracking**, **R Specifics**, and **Python Specifics**.  If you've never used Git/GitHub, begin at the **Starting Git/GitHub** section and then continue to the **GitHub Issue Tracking**.  The **R Specifics** and **Python Specifics** are sections for those coding languages.

## Starting Git/GitHub

This section provides a starting point for using Git/GitHub to contribute to this project.  This section should take three hours or less to complete.  It's designed so that a user can start and finish getting ready to contribute to this project within an afternoon.  This guide to using Git/GitHub is NOT comprehensive because of the massive amount of options for using Git/GitHub.  For example, it doesn't cover setting up a repository because that's not needed to contribute here.  It purposefully leaves out information to keep it succinct.

### Setting up a GitHub account / Git
- Create an account

The first step is to set up an account.  This can be done following this page https://help.github.com/articles/signing-up-for-a-new-github-account/.  The free account will work for this project (a most others).

- Download / Set up git

Direction for setting up git bash can be found here.
https://help.github.com/articles/set-up-git/#next-steps-authenticating-with-github-from-git

This section and the **Setting up working with the Asheville-Community-Data-Library** basically follow this page: https://help.github.com/articles/fork-a-repo/.
A great walk through for the setup is found at the beginning of this YouTube video: https://www.youtube.com/watch?v=HVsySz-h9r4&list=PL-osiE80TeTuRUfjRe54Eea17-YfnOOAx.

At this point a user should have a GitHub account and git bash installed on their computer.

### Setting up working with the Asheville-Community-Data-Library

- Fork the repository

This section will make a copy of the Asheville-Community-Data-Library for your GitHub account.  You will be able to show work your have done to the Asheville-Community-Data-Library members here.  If the changes are approved, they can be pulled into them to the original repository.

To start working with the Asheville-Community-Data-Library, a user will need to **fork** the avl-community-data/Asheville-Community-Data-Library to their GitHub account.  Directions for this can be found here: https://help.github.com/articles/fork-a-repo/, but instead of navigating to the **octocat/Spoon-Knife** repository navigate to the avl-community-data/Asheville-Community-Data-Library here: https://github.com/avl-community-data/Asheville-Community-Data-Library.

- Clone to user's computer

This section will make a copy of the repository from your GitHub account to your computer.  You will be able to make changes here for your work here without worrying about what they look like and then push them to your repository on your GitHub account when are done working.

Continuing the steps listed at https://help.github.com/articles/fork-a-repo/, cloning to the user's local machine can be done at Step 2.  The only change needs to be switching from **YOUR-USERNAME/Spoon-Knife** to **YOUR-USERNAME/Asheville-Community-Data-Library**.

- Add a remote

This section connects all the repositories together: the original **avl-community-data/Asheville-Community-Data-Library** (which will be called 'upstream'), **YOUR_USERNAME/Asheville-Community-Data-Library** on GitHub (which will be called 'origin'), and your local **Asheville-Community-Data-Library** on your computer.  This will help keep your repository up to date to changes in the avl-community-data/Asheville-Community-Data-Library repository.

The last section, Step 3, on https://help.github.com/articles/fork-a-repo/, gives directions on adding a remote to your repository.  The changes from the example page to use the Asheville-Community-Data-Library are navigating to https://github.com/avl-community-data/Asheville-Community-Data-Library repository instead of the octocat/Spoon-Knife one, instead of **YOUR_USERNAME/YOUR_FORK** the output should be **YOUR_USERNAME/Asheville-Community-Data-Library**, instead of https://github.com/octocat/Spoon-Knife.git have https://github.com/avl-community-data/Asheville-Community-Data-Library, and finally instead of **ORIGINAL_OWNER/ORIGINAL_REPOSITORY** the output should say **avl-community-data/Asheville-Community-Data-Library**.

More direct directions can be found here: https://help.github.com/articles/configuring-a-remote-for-a-fork/.

## GitHub Issue Tracking

The Asheville-Community-Data-Library repository uses GitHub issues to track work that needs to be done.  Each issue should take less than four hours.  This is by design so that a user can start and finish a task within an afternoon.

- Find an issue to resolve

The first step is to find an issue to resolve here: https://github.com/avl-community-data/Asheville-Community-Data-Library/issues.  There should always be an issue for 'Minor grammatical fixes' such as a mispeling.  This is a great first issue to try out since it won't break any code if it is broken.

- Check and sync remote

Before making any changes to your repository, changes from the upstream remote, **avl-community-data/Asheville-Community-Data-Library**, need to be pushed to your repositories.  Following the steps on the following pages will sync your repositories: first this page https://help.github.com/articles/syncing-a-fork/ to sync your local repository, and then following the link to sync your repository on GitHub: https://help.github.com/articles/pushing-to-a-remote/.

- Create a branch

To begin working on the GitHub issue, you need to create a branch.  Creating branches keeps your work on the issue separate.  Make sure to name your branch something that relates to the issue so that tracking will be easy.  This can be done two ways: on GitHub by following this link https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/ and then pulling to your local machine, or locally by running the following commands:

> git checkout -b BRANCHNAME

- Saving work with Git

While your work can be saved normally, using Git makes it easy to track changes.

> git status
> Add / commit
git add -A
git commit -m �commit message�

Push branch to remote
git push -u origin BRANCHNAME
git branch -a (see all branches)
Merge
Delete branches
git branch -d BRANCHNAME
sync fork
https://help.github.com/articles/syncing-a-fork/
https://help.github.com/articles/pushing-to-a-remote/

Messed up?
https://stackoverflow.com/questions/42332769/how-do-i-reset-the-git-master-branch-to-the-upstream-branch-in-a-forked-reposito


## R Specifics:
Use `here` package
.gitignore

## Python Specifics:
.gitignore
