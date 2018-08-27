Git Practice


# Intro to Git

Git is version control software. Software engineers use it to track changes, contribute code simultaneously without interfering with each other, and to easily do things like undo changes or find out when something broke.

It’s a good idea to study some of the official documentation, or at least watch some of the introduction videos here: https://git-scm.com/doc

Using git proficiently doesn’t require a full knowledge of everything, just the following key concepts:

Things: Repository, Branch, Commit
Actions: Clone, Pull, Push, Pull Request, Merge
Places: Local, Remote
Tools: Github, Sourcetree, Command Line Interface
Bonus: Merge conflicts

# Git Good

## Things

**Repository** (“Repo”)

A repository is the highest level container of code. Usually, each project will have its own repository. In Periscope, each customer site will have its own repository. An example repository is https://github.com/raymondgh/solutions-practice-repository

**Branch**

A branch is a version of the repository. The main branch is called the “Master Branch” and other branches are named by the developers involved in the project.

Typically, when someone wants to make changes to a project, they’ll create a new branch based off the master branch, make some changes, then merge the branch back to the master branch (more on this later).

**Commit**

A commit is a saved change to a branch. There’s no auto-saving with git, so it’s important to “commit your changes” whenever you want to save. Every saved change is a commit, whether you’re deleting or adding code. Commits are added to a branch and any given branch will have a list of all commits made to it.

**Pull Request (“PR”)**

A request for a branch to be merged into another branch. Typically after you finish updating the branch you’re working on, you’ll submit a PR and a teammate will read it, make sure it doesn’t break anything, and then either Merge it into destination branch or reject it with a reason that you can fix.

### Places

**Remote** - A remote repository is a repository on a server somewhere

**Local** - A local repository is a repository on your own local machine


## Actions

**Clone** - Downloading a repository from remote to local

**Pull** - Retrieving the latest remote version of a branch into local 

**Push** - Upload the latest local files to the remote repostiory

**Merge** - The action of combining two branches. When branch B merges into branch A, only branch A will remain, and it will contain the latest changes from both.

**Fork** - Copy a repository into your own directory. This creates a totally new repository with totally reset permissions and settings.

## Tools

**Command Line Interface (CLI)** - The original tool for using Git is the CLI. There’s a steep learning curve, but the pros will use this.

**Github** - Github is a service provided by Github Inc that provides free and paid git repository hosting. 

**Github for Desktop** - Github for Desktop is desktop software that makes it easy to use Git. It replaces the CLI but can’t do everything (most things though!).

**Sourcetree** - Sourcetree is desktop software made by Atlassian to help use Git. It competes with Github for Desktop. 



## Exercises:

1. Sign up for [Github](https://github.com/join)
2. Have someone add you as a contributor to this repository
3. Download and install [Github Desktop](https://desktop.github.com/)
4. Download and install [Sublime Text 3](https://www.sublimetext.com/3)
5. _Clone_ this repository to your desktop computer using Github Desktop
6. _Pull_ the latest code
7. Create a new _branch_, name it with your own name
8. _Commit_ changes to your branch (move your name from one section to the other in the readme.md file)
9. _Push_ your changes to the remote repository
10. Submit a _Pull Request_ for your branch
11. Check github.com to see active pull requests
12. _Merge_ a PR

## People who haven't completed Git Training

- Sunny
- Esther
- Andreas
- Charlotte
- Neha
- Caitlan
- Christine
- Mark
- Adam
- Skip
- Ray

## People who have completed Git Training
