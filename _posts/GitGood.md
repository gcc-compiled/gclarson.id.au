---
layout: post
title: GitGood
subtitle: Basic Knowledge Dump of Git and Github
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [git, github]
comments: false
---

# Git Good
This is just some testing grounds on understanding, utilising and getting better at Git. This is something I have been trying to do for a while so why not use it as a testing ground, but also share some notes.

I dont really like the idea of "those who can't do, teach", because for me I solidify and reaffirm my knowledge or even learn more by teaching or sharing my info with others. It opens an important dialoge if I am wrong so I can understand where my knowledge is gapping, so if there is something not true within this repo please PM me or let me know!


# What is it Git for? 

- Git is used primarily for version control.
- It is very common in the programming community, however it is not just for programming.
- Most businesses have pretty messy version control, and Git can help with it. However you can do a lot of this with a solution like DropBox, OneDrive, Sharepoint all have their own way of version control.


# Is Using GitHub Gitting Good?

Not really there are some key differences that should be known in understanding what you can do and why they are related.
For example:
- Git is the software itself, it has its own commands and usually contained within a CLI type environment with vary little sharing capabilities.
- GitHub is a web service used for not only hosting files in the same way Git creates and manages files, but also in more of a GUI and beginner friendly way. This is also used as a sharing platform between users to share projects they have made.


# Terminology
Some good terminology to know when understanding, communicating and using Git or GitHub
- Repository (a.k.a "Repo"): A repository of files containing a specific project
- README File: Is a file that is often used in GitHub to give a blurb in markdown what the project is about.
- Commit: essentially a "Save Button" for files, one a commit has been performed a Hash is generated that will uniquely identify a version change
- Branch: A branch is essentially an experiment of code that is in parallell but seperate to the Master. Its mostly used to try new code and see if new techniques would work without affecting the master. Very affective for large repositories or collaborative projects and patching.
- Master: A default name for the main linear list of changes within a repository.
- Merge: is a request to have all the commited changes made within a branch, and make it part of another branch, most commonly used to merge back to Master. This can also be utilised to merge a series of branches together into a single branch.
- Fetch: is a request to grab all of the history information within a branch, it is commonly used along with Merge by either utilising a Pull request or another workflow.
- Fork: Creates a duplicate of a repository as a whole from one account to your local account.
- Pull Request: Is a combination of Fetch and Merge requests, essentially a shortcut instead of fetching then merging all the time. Pull == Fetch + Merge. In the context of a repo that was forked, a Pull requests is asking the original owner of the repository to merge your changes from your local repo to theirs.
- Push Request: is used to transfer commits from your local repository to a remote repository like a central server or GitHub

