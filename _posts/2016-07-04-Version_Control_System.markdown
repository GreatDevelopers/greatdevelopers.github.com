---
layout: post
title:  "Amisha and Gagan - Version Control"
date:   2016-07-04 11:45:00 +0530
author: "Deepti Sharma"
categories: presentation
---


**Version Control System (By Amisha Budhiraja and Gagandeep)**

Version control system help a software team manage changes to source code over time.
There are two types of Version Control System:
- Centralized Version Control System. Eg: Perforce, CVS (Concurrent Version Control System)
- Distributed Version Control System. Eg: Git, Bazaar 

**Q1. What is CVS, SVN?**


**Basic diference between Git and Github**

Git is a revision control system, a tool to manage your source code history. GitHub is a hosting service for Git repositories. So they are not the same thing: Git the tool, GitHub the service for projects that use Git.

There are various control systems like Bitbucket, Gitlab etc.

**Making new local repository**

*Some of the commands are:*
- Mkdir test
- cd test
- git init
- touch new.txt

And so on ..
 
You can also use **git clone** command

**Q2. Can we push a repository from local system without having any remote repository?**

**Basic difference between git add and git commit:**

Git add is just the index of a file but git commit is actual data which is present under that index number.

- git status tells about the status of the repository.

- git remote add red http://github.com/amisha2016/invention

Above command gives shortcut named red instead of writing url
git stash command is used when we had added a file but hadn’t commit it then we can save it in another place where we can refer afterwards and can move to other repository.

**Q3. How to git stash a particular file?**

- git log tells about the recent commits.
- git revert is used for undo changes after push command.
- git reset : If you do changes locally and didn’t push yet and you apply reset it will undo all the changes and didn’t show any changes on git hub, repo remains same.
-  git branch commands show all branches.

**There are 2 modes:**
- **Hard:** It removes the commitment entry from the index and actual commit stage.
- **Soft:** It removes only the actual commitment


**Q4. How to change the message if we had written wrong message accidently?**

