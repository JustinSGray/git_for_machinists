# What is this repo for? 

A planning file for a video on how to explain git + github to machinists. 



# Questions to answer

## What is git + github? 
A version control system mainly designed for text documents (any file type that is made up of ascii or unicode txt)

Anything that looks like a txt file: 
- gcode files 
- csv data files 
- xml files 


You can also keep non txt files in the repo, like PDFs and image files.
These can sometimes be useful too, but aren't the main purpose of git or github. 

## Why would you want to use git + github? Which circumstances? what kinds of files? 
    
Git is very useful when multiple people need to collaborate on a document.
It allows tracking of changes, and keeps a history of who changed what. 
Git + Github also provides a nice backup system, and a convinent way to sync up work across multiple machines.


Here are a few specific situations that might benefit from Git+GitHub: 

- shop procedure documents
- important gcode for parts 
- important gcode for any macros 
- machine backups 


## What is the difference between git and github? 
Git is a program that runs locally on one or more computers. 
It is actually the version control software itself. 

GitHub is a website that hosts copies of Git repositories in the cloud, 
and provides a convinent web page based interface for interacting with them. 

## What is the recommended workflow for using git + github by yourself? 

I've never gotten good at the VSCode workflow, but that is probably the best one to include here. 

### Key Skills 

- creating a new repo 
- commiting changes to it 
- pushing the repo up to github 
- looking at changes and rolling back to older versions

## What is the recommended workflow for using git + github to collaborate with someone? 

Fork or shared repo? I suggest fork, but then you have to teach them about multiple remotes ...

### Key Skills 

- forking a repo 
- issuing a pull request 
- pulling changes from another fork into your fork
- adding and using multiple remotes in your local environment



