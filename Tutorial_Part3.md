# Welcome to part 3 of the tutorial

<br>

### Introduction
everybody likes some quality of life to make work a little better. For working with Github alot is the internet webpage not optimal. Luckly are there various tools to help us, one of these tools is Visual Code Studio (VCS).

VCS is a source-code editor made by Microsoft and can run on Windos, Linux and macOS. It features debugging, syntax highlighting, snippets, coderefractoring and is even embedded in git. Thereby are there alot of extensions available online to customise VCS to your needs. In this tutorial the installation to creating and using git will be explained.

# Contents

- Installations
- Extensions
- Overview
- accesing a github
- forking, pulling, clone and commiting
- Creating Python codes



## Installation

Like the most softwares, can it be easily installed by using internet. click [here](https://code.visualstudio.com/) for a link to download VCS.

![image](images/Download.png)

<br>




### Extensions

Before we start we a total tutorial about how VCS works. Lets install a few extensions.
Extensions are little software packages who can install new features of make some quality of life changes.

The extension button is located on the left bar with the following button ![image](images/Extension.png). 

Search for the following extensions
- Github Pull Requests and Issues
- Github Repositories
- Python

![image](images/install_extension.png)

There are many more extensions out there so dont be scared to go some shopping for features you would look handy.
For example there are also features which makes writing in markdown easier or even spellcheck it for you.<br><br><br>

## Overview of VCS

Visual code study contains alot of awesome features but can be quite overwhelming in the start. Luckly we already installed some extensions for quality of life.
But now is the real work.

![image](images/layout.png)

- Explorer. In this  tab are all files of the current github repository. This is currently still empty. but not for long!
- Search, a search function for in your github repository
- Source controll. If you edited and saved a file from a github, is here your change to make an pull request or to commit it directly
.<br> pull request = sending the owner a nice message about what you would like to change
- run and debug, is for running files, for exammple hello_world.py
- extensions, a place where you can go shopping for new plugins
- Remote exporer. an overview of previous githubs where you have been
- github, here is the real magic. Every github repository you own or are admin for will be sended to this. when a person makes a pull or fork request you will get an automated message here. 

On the top bar of VCS are various functions. Files to generate files. Edit to easily edits files. It also possible to openup an terminal and run various codes

On the bottom of the windo is the workspace and branch you are working in.
![image](images/onderste_balk.png)


but enough talking, lets get into some action<br><br><br>



## Getting access to a github repository

Remember the repository you made. lets open it up.
click on the green box in the left under box ![image](images/github_knopje.png).

This will open a small terminal above and click on "open remote repository".
![image](images/open_repository_box.png)
 
 In this window you fill in the URL of the github repository you created earlier.
![image](images/open_repository_2.png)


Every time you have added a github repository. you dont have to search the url again. when clicking the remote repository you will find a overview off all repository you have worked in. you also see if you need to update a repository locally in VCS. In this is it also possible to look up pull requests and access pulled repositories. When you have done this. is it possible to view and edit all files in the explorer tab.

![image](images/all_repositories.png)


## excersices

- open the repository of this github tutorial
````
https://github.com/Avans-ATGM/Github_Tutorial
````
- Create a new branch to work in and give it a usefull name.<br>
A new branch can be opend by clicking on this button below ![image](images/branch_button.png) <br> and click on ``` + Create new branch ``` <br>
since we are testing, lets call it 
````
test_[your_username]
````

So now we have a copy from the mainbranch. in this we can code and give adjustment. <br> After we edited or created some new files we can merge it back into main by creating a pull request
<br>
In the Examples directory is the file "Nucleotide_Counter.py"  lets improve that one.

Here we see a for loop to count all the nucleotides. Since we are pretty good Python coders we can improve it. ![image](images/nucleotide_counter.py.png)

Lets make it a dictionary loop to reduce the number of lines.<br> It should look like something like this.

![image](images/Nucleotide_counter_edited.png)

Safe all your work by clicking on file and then safe, or close the window and a message will pop up
## pull request

We have edited the pythoncode to be more efficient and lesses lines. 
Lets make a pull request to merge it back to the main branch.

- Go to Source controll and click on the top bar on create pull request. <br> 
When you click on your files you get a neat overview about your edits. <br>
The person who will be checking your pull request will also be able to view this (and he should since you are making edits to the main branch).