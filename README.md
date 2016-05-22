# GitHub Setup for RStudio

RStudio has a nicely integrated version control features that allow you to utilize 




http://www.molecularecologist.com/2013/11/using-github-with-r-and-rstudio/

https://support.rstudio.com/hc/en-us/articles/200532077?version=0.99.489&mode=desktop




## Helpful Vocabulary

Versioning system software like GitHub functions much like DropBox. You can have the same files stored on multiple computers and they will sync seamlessly via the cloud. With DropBox this process is automatic - DropBox will assume that if you make a change on a file on one computer, you will want updated versions on other computers. This is a file-sync system.

<img src="https://raw.githubusercontent.com/lecy/github-setup-for-rstudio/master/Images/dropbox.png" width="450">


Versioning systems function in a very similar way, but instead of solving a problem of keeping files syncronized with one user and multiple computers, versioning systems solve the problem of having one set of files and multiple users that are all working on the project. As a result, the major difference between DropBox and GitHub is that updates are not automatic when changes are made to files. Users must submit changes, and they must be approved. In order to get the most recent file version, you must request it.

The vocabulary that is unique to a versioning system is:

* *repository* - the project folder where code is stored
* *commit* - making edits available
* *push* - submitting edits to GitHub
* *pull* - downloading the most recent version of code from GitHub

The _repository_ is analogous to a DropBox folder where a project might be stored. Unline DropBox, the versioning system will not automatically update all of the files so that they are the same across all computers. Versioning systems allow for more control so that a team member does not submit bad code that breaks the system. You also do not want to save computer code that is partially complete, so in general a team member will find a breaking point in the work and then commit the code they have created.

In order to submit code to the project manager (the person who will is in charge of the GitHub repository, and who will ultimately approve and merge the work), the team member will _commit_ their code to the GitHub branch, then _push_ it to GitHub. In order to get the updated version, other team members will need to _pull_ the new code to their machines. 

<img src="https://raw.githubusercontent.com/lecy/github-setup-for-rstudio/master/Images/github.png" width="450">




## Step 01 - Setup a GitHub Account

If you do not have one already, create a GitHub account:

https://github.com/

## Step 02 - Instal Git

Install the appropriate version of Git on your machine:

https://git-scm.com/

After installed, be sure to configure the Git global commands. You will need to open a Git bash window (search for Git Bash in your program list). Type in the following commands using your GitHub _username_ and the _email address_ associated with your account.

```
git config --global user.name "username"
git config --global user.email "your@email.address"
```

## Step 03 - Setup in RStudio

Be sure that RStudio is installed on your machine. 

Go to: Tools > Global Options > Git/SVN

![alt text](https://raw.githubusercontent.com/lecy/github-setup-for-rstudio/master/Images/global_options.png)

## Linking to existing repository

## Submitting Code Edits (commit and push)

## Creating new repository


