# An introduction to git and how we'll use it in this module

Unity projects are large and comprise a very large number of files. This means that it’s often impractical and very slow to store and run them from a file server like your university storage drive. For this reason, we recommend you use git to store your work in this module. We will also be hosting all of the intructions and files for practical exercises for the module on GitHub too.

Git has a bit of a learning curve, but using it will mean you’ll be able to spend more time working on creative projects in this module and less time waiting for files to upload! Git is also the industry standard version control system. Therefore, learning it now will benefit you in the future.

This document explains how you can use git to save your work to a remote server and then access it later from another computer. We’ll be using GitHub as a hosting service and the GitHub desktop app to keep things simple. However, if you’d like to learn how to use git via the command line just ask.

**Please try and complete these steps BEFORE the practical class – you’ll have Unity work to do in the practical! However, if you get stuck, please do ask for help in the practical.**

If you're working from home (I did call this homework after all!) you'll need to download [GitHub Desktop](https://desktop.github.com).

## Step 1: Create a GitHub Account

The first thing you’ll need to do is create a GitHub personal account. To do this, go to https://github.com and follow the instructions to create your account. If you’re already got a GitHub account, please feel free to use that of course.

If you sign up using your university email, you’ll be eligible to apply for a student account that offers some otherwise paid features for free here: https://education.github.com/students 

## Step 2: Creating your First Repository

A git repository is a place where you can save your code (and multiple versions of it, but let’s not worry about that for now). I’d recommend that you create a unique repository for every Unity project in this module (i.e. one per practical class). In this step, we’re going to create your first repository.

To get started, open the GitHub Desktop application – you can find it under Spotlight Search for GitHub Desktop – and login. Once you’ve logged in, choose “Create a new repository on your hard drive” on the page that appears.

![Create a new repository on your hard drive](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/create.png)

In the popup that appears, give your repo a name. I’ve chosen “my-first-repo”.

![Create a new repository on your hard drive](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/name.png)

Then choose where you’d like it to be stored on your local computer. I’d recommend placing it on the desktop.

![Local](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/local.png)

Choose Unity for the “Git Ignore” option. This will add a special file to your git repo that prevents the large numbers of temporary files that Unity creates from being saved, making your projects much quicker to upload and download.

![Ignore](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/ignore.png)

Finally press the “Create Repository” button to create the repo. 

## Step 3: Adding a Files to Your Repository

You now have a git repository on your local computer. To see your git repository press the “Show in Finder” button.

![View the files of your repository in finder](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/finder.png)

You’ll notice it’s just an empty folder for now! However, any files that you place within this folder can be tracked and stored by the git system. Let’s try this out by creating and dragging a simple text file into your repository folder. 

Once you’ve done this, you should see that your text file now appears in a list in the GitHub desktop application under the list of changes. This means that it’s now part of the repository. 

![Current repository](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/current.png)

## Step 4: Committing Changes

One of the coolest things about git is that is doesn’t just let you save the latest version of your work. Rather, you can save lots of versions of your work and go back to older ones if you need to. When using git, you can create a snapshot of a version of your work using the commit command. For example, you might want to commit a snapshot of your repository every time you complete a practical exercise, or when you’ve got a new feature working in your assessment. In this step, we’re going to use the commit command to make a snapshot of our repository with the single text file we’ve added to it.

The list of changes you saw in the previous step is actually a list of all files that have been added or changed in your project since the last commit (in our case just one text file). You can save a snapshot of these changes by using the commit dialogue at the bottom of the list.

![Commit to main](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/commit.png)

It’s good practice to add a message to your commit, so you know what version of your work it represents. For example, I’ve added the message “First file added to project”. Once you’ve written a suitable message, press the “Commit to main” button to execute the commit command.

## Step 5: Publishing Your Repository to GitHub

It’s important to note that at this stage you’ve only saved your changes to the local version of the git repository on your computer. Therefore, if you delete your repo now your work will be lost. In this step, we’re going to publish our changes on the GitHub server, so they will be saved there too.

You can do this by pressing the “Publish Repository” button in GitHub desktop.

![Publish your repository to github](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/publish.png)

It’s important you choose the “Keep this code private” option for your university work. If you don’t other students may be able to see your work and copy it. 

![Keep this code private](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/private.png)

Once you’ve published your repository it’ll now appear on your GitHub account. You can see it online by pressing the “View on GitHub” button.

![View on github](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/view.png)

A website will load showing all the files in your repository. See if you can you browse it to check if the text file your added is there.

## Step 6: Making and Pushing a Change

Every time we want to save changes to our repository onto the GitHub server, we’ll follow a similar process to the one we’ve completed above:

1. Make some changes
2. Save a snapshot of those changes using the commit command
3. Push the changes up to the server to they’re saved for later

Once you’ve published your repository to the server, you’ll have to use the “push” command to save subsequent changes to the GitHub server. This is easy, just press the “Push origin” button instead of the publish button.

![Push commits to the origin remote](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/push.png)

Make a change to your text file and see if you can follow the process above to save them onto the GitHub.

## Step 7: Cloning Your Repository onto a Different Computer

Your repository is now safely stored on the internet!  If you want to access from a different computer, you can use the clone command to do this. The clone command basically makes a new copy of your repository on the computer you’re working on. In this step, we’ll learn how to do this. 

Before you do this step, you’ll either need to move to a new computer in the lab or delete the repository from the computer you’re working on. If you’re doing the latter, simply delete the repository folder off the desktop.

To clone your repository onto the computer you’re working on, press the “Clone a Repository from the Internet” in GitHub Desktop.

![Clone a repository from the internet](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/clone.png)

You’ll be presented with a list of all the repositories on your GitHub account. Choose the one you want and where you want to put it (I recommend the desktop for now) and press the “Clone” button.

![Clone a repository](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/list.png)

You should find that the last version of your code that you pushed to the server is now available on your local computer to run and edit.

## How will we use git in this module?

When used in the most basic way described in this document, a git repo is a bit like a book in a library. You can check it out onto your computer to run and make changes and then when you’re done you can check it back into GitHub to save the changes you’ve made. I’d recommend you use Git in this basic way to save and back up your work during this module.

To make things a bit simpler, for all practical classes where you'll be asked to build on an existing Unity project we've created template git repositories. These templates are repositories that already include all the files you'll need for a practical class. You can press a single button ("use this template") to create a new repository in your personal GitHub account based on one of these templates. All you'll then need to do is clone that copy of the repository on your machine to access all the files you'll need to start the class.

This tutorial is actually a git template repository. Therefore, you can try this out now by following these steps:

1. Press the "use this template button" at the top right of this page. This will create a copy of the repository in your own GitHub account
2. Clone the copy you have created in your own account (i.e. not this repository) onto your local computer using GitHub desktop
3. Make a change to a file in the repository (e.g. try corect one of the intetnional typors in this tutoriel in the Readme.md file)
4. Push the change back to your own version of the repository and check if you can see it on the GitHub website 

You can also install GitHub Desktop onto your own computer at home from the following link: https://desktop.github.com. This means that if you don’t finish your work in class, you can clone it onto your own computer when you get home and carry on from where you got up to.



