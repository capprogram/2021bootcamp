# Git and GitHub tutorial

## 1. Go [here](https://github.com/capprogram/2017bootcamp-general/blob/master/git-prep.md) if you need a GitHub account or must install Git.

## 2. Configure Nano

Nano will be a text editor that Git will use whenever Git wants to open up a text editor. Nano is fairly simple to use and straight-forward, with instructions to remind you of how to use them at the bottom. The only thing is that installing nano can be tricky. Here are some steps to installing Nano if you are using a windows machine.

    1. Go to this website: https://www.trishtech.com/2020/11/how-to-install-nano-editor-in-windows-10/
    2. Click on the link in step 1 and find the latest version of nano. Download it and give it permission to be installed/edit device if it asks. 
    3. Go to https://www.7-zip.org/ and download the version of 7-zip (version 19.00) that works for your computer (probably 64-bit)
    4. Install 7-zip and give it whatever permission it asks for (should be a very fast installation)
    5. Open 7-zip and go to the nano installation folder in 7-zip.
    6. Press on the folder (The one with x86 is for 64-bit) and click on the "Extract" button at the top.
    7. It should then have extracted nano. Outside of 7-zip, go into the folder and into the bin file to find nano.exe. 
    8. Copy nano.exe and paste it into your C:/Windows/ folder.
    9. Run nano.exe, if it worked then you should see a small black terminal with some tips at the bottom!

## 2. Configure Git.

On your linux machine, run `git config` (in any directory) to set your name, email, and preferred options.

Examples:

    git config --global user.name “Sheila Kannappan”
    git config --global user.email sheila@physics.unc.edu
    git config --global color.ui "auto"
    git config --global core.autocrlf false
    git config --global core.editor vi

Note `user.name` is not your GitHub username but rather your name.

*(Our git tutorial assumes you will use vi as your editor, but if you wish to use emacs or some other plain text editor as your default, just type `git config --global core.editor "emacs"' or the analogous command.)*

You can check what you’ve done with

    git config --list
    
You can get more details on config option by typing

    git config -h        # short version
    git config --help    # long version

On your laptop, run `git config` with the same answers used above for your linux machine (to get a terminal, under Windows go to start menu and type "gitbash" to search, or under Mac go to spotlight and type "terminal" to search).

## 3. Complete the tutorial below.

### Table of Contents

1. [Automated Version control](01-automated-version-control.md)
2. [Creating a repository](02-creating-a-repository.md)
3. [Tracking changes](03-tracking-changes.md)
4. [Exploring history](04-exploring-history.md)
5. [Working with branches](05-branches.md)
6. [Setting up a remote repository in GitHub](06-remotes-in-github.md)
7. [Collaborating](07-collaborating.md)

### Source

This tutorial borrows heavily from [Software Carpentry's](http://software-carpentry.org/) tutorial [Version control with git](http://swcarpentry.github.io/git-novice/) and Software Carpentry's [branching tutorial from erdavenport](https://github.com/erdavenport/git-lessons), both under a [Creative Commons Attribution license (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

## 4. Additional Resources

1. [Git cheat sheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
2. [Quick overview](http://rogerdudler.github.io/git-guide/)
