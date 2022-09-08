# An introduction to git and how we'll use it in this module

Unity projects are large and comprise a very large number of files. This means that it’s often impractical and very slow to store and run them from a file server like your university storage drive. For this reason, we recommend you use git to store your work in this module. We will also be hosting all of the intructions and files for practical exercises for the module on GitHub too.

Git has a bit of a learning curve, but using it will mean you’ll be able to spend more time working on creative projects in this module and less time waiting for files to upload! Git is also the industry standard version control system. Therefore, learning it now will benefit you in the future.

This document explains how you can use git to save your work to a remote server and then access it later from another computer. We’ll be using GitHub as a hosting service and the GitHub desktop app to keep things simple. However, if you’d like to learn how to use git via the command line and/or another hosting service just ask.

**Please try and complete these steps BEFORE the practical class – you’ll have Unity work to do in the practical! However, if you get stuck, please do ask for help in the practical.**

## Step 1: Create a GitHub Account

The first thing you’ll need to do is create a GitHub personal account. To do this, go to https://github.com and follow the instructions to create your account. If you’re already got a GitHub account, please feel free to use that of course.

If you sign up using your university email, you’ll be eligible to apply for a student account that offers some otherwise paid features for free here: https://education.github.com/students 

## Step 2: Creating your First Repository

A git repository is a place where you can save your code (and multiple versions of it, but let’s not worry about that for now). I’d recommend that you create a unique repository for every Unity project in this module (i.e. one per practical class). In this step, we’re going to create your first repository.

To get started, open the GitHub Desktop application – you can find it under Spotlight Search for GitHub Desktop – and login. Once you’ve logged in, choose “Create a new repository on your hard drive” on the page that appears.

![Create a new repository on your hard drive](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/create.png)

In the popup that appears, give your repo a name. I’ve chosen “my-first-repo”.

![Create a new repository on your hard drive](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/create.png)

Then choose where you’d like it to be stored on your local computer. I’d recommend placing it on the desktop.

![Local](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/local.png)

Choose Unity for the “Git Ignore” option. This will add a special file to your git repo that prevents the large numbers of temporary files that Unity creates from being saved, making your projects much quicker to upload and download.

![Ignore](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/ignore.png)

Finally press the “Create Repository” button to create the repo. 

## Step 3: Adding a Files to Your Repository

You now have a git repository on your local computer. To see your git repository press the “Show in Finder” button.

![View the files of your repository in finder](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/finder.png)

You’ll notice it’s just an empty folder for now! However, any files that you place within this folder can be tracked and stored by the git system. Let’s try this out by dragging a file into your repository folder. 

Once you’ve done this, you should see that your text file now appears in a list in the GitHub desktop application under the list of changes. This means that it’s now part of the repository. 

![Current repository](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/current.png)

## Step 4: Committing Changes

One of the coolest things about git is that is doesn’t just let you save the latest version of your work. Rather, you can save lots of versions of your work and go back to older ones if you need to. When using git, you can create a snapshot of a version of your work using the commit command. For example, you might want to commit a snapshot of your repository every time you complete a practical exercise, or when you’ve got a new feature working in your assessment. In this step, we’re going to use the commit command to make a snapshot of our repository with the single text file we’ve added to it.

The list of changes you saw in the previous step is actually a list of all files that have been added or changed in your project since the last commit (in our case just one text file). You can save a snapshot of these changes by using the commit dialogue at the bottom of the list.

![Commit to main](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/commit.png)

It’s good practice to add a message to your commit, so you know what version of your work it represents. For example, I’ve added the message “First file added to project”. Once you’ve written a suitable message, press the “Commit to main” button to execute the commit command.

Step 5: Publishing Your Repository to GitHub

It’s important to note that at this stage you’ve only saved your changes to the local version of the git repository on your computer. Therefore, if you delete your repo now your work will be lost. In this step, we’re going to publish our changes on the GitHub server, so they will be saved there too.

You can do this by pressing the “Publish Repository” button in GitHub desktop.

![Publish your repository to github](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/publish.png)

It’s important you choose the “Keep this code private” option for your university work. If you don’t other students may be able to see your work and copy it. 

![Keep this code private](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/private.png)

Once you’ve published your repository it’ll now appear on your GitHub account. You can see it online by pressing the “View on GitHub” button.

![View on github](https://github.com/UoY-IM-MPIE/mpie-git-tutorial/blob/main/Instructions/view.png)

A website will load showing all the files in your repository. See if you can you browse it to check if the text file your added is there.
