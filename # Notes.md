# Notes

This is intended to be a more serious document related to test project 'one' for git training. I want to write down a series of descriptions that capture the steps and associated concepts discussed in the git training. 

## Table of Contents

1. [Introduction](#introduction)
2. [Setup](#setup)
3. [Basic Commands](#basic-commands)
4. [Branching](#branching)
5. [Merging](#merging)
6. [Rebasing](#rebasing)
7. [Advanced Topics](#advanced-topics)
8. [Best Practices](#best-practices)
9. [Troubleshooting](#troubleshooting)
10. [Resources](#resources)

## Introduction

<!-- Provide an overview of the git training, its objectives, and what you aim to achieve by the end of the training. -->

This training module about git, 'git-real', is intended to provide me with the basics of git use, to assess and retrain my git skills and introduce some new useful concepts, so I can swiftly join the project, more able in terms of version control. 

## Setup

<!-- Detail the initial setup required for the training, including installing git, configuring user information, and setting up a repository. -->
In order to engage with this course, first it is necessary to clarify how the interaction with git technology to test the course concepts and commands. 
This was made primarily through the command line (windows powershell), since this is more suitable for a low-level overview which produces a more comprehensive knowledge.

## Basic Commands

<!-- Explain the fundamental git commands such as `git init`, `git clone`, `git add`, `git commit`, `git status`, and `git log`. -->
`git init` : This command initializes the git repository. 

`git clone` : This command copies the remote repository into the local machine, on a newly created folder with the same name. 

`git add` : This command adds the tracked, but unstaged files into the staging area -- marking the chosen files as 'staged', selected to be included in the commit (the final step for a given arbitrary development cycle).

`git commit` : This command is the actual instruction to commit the changes for the selected (staged) files into the Version Control apparatus, which saves a copy of the repo into a data-structure, holding, from this moment on, a Version of the code base.
 
`git status` : This command provides a colorful summary of the changes made in the repo from the last commit. This list, resulting from the command, informs the user about which changes (normally through files) to **stage**.

`git log` : This command provides a list as a timeline of all the previous commits made in this repo. 

## Branching
## Branching
<!-- Describe the concept of branching, how to create and switch branches using `git branch` and `git checkout`, and the importance of branches in git workflows. -->
Branching refers to the action of creating a new branch within the version control system. The command `git branch` creates a new branch, which is essentially a copy of the original repository (main) but separated. From this point, development can continue on the new branch independently, allowing for the implementation of new features or experiments without affecting the main branch. 
To switch to the new branch, use the command `git checkout <branch-name>`. This allows you to work on the new branch while keeping the main branch unchanged.


## Merging

<!-- Discuss the process of merging branches, resolving conflicts, and using commands like `git merge`. -->
 Once the development on the new branch is complete and tested, it can be merged back into the main branch using the `git merge <branch-name>` command. This integrates the changes from the feature branch into the main branch, combining the two branches back together.
## Rebasing

<!-- Explain what rebasing is, how to perform a rebase with `git rebase`, and the differences between rebasing and merging. -->

## Advanced Topics

<!-- Cover more advanced git topics such as `git stash`, `git cherry-pick`, `git bisect`, and `git reflog`. -->

## Best Practices

<!-- List best practices for using git effectively, including commit message conventions, branching strategies, and code review processes. -->

## Troubleshooting

<!-- Provide solutions to common git problems and errors that users might encounter during the training. -->

## Resources

<!-- Include links to additional resources such as official documentation, tutorials, and community forums for further learning. -->
