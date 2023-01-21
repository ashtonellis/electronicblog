# Week 1 Notes

## January 9th Class Notes

Participation Criteria:

* participate in in-class discussions
* asking / answering peer questions online
* arrive on time / be present in class
* be prepared for each class

## January 10th Homework Notes

### VSCode Introduction

* Open folder: ctrl + O
* Command palette: ctrl + shift + P
  * control center for all commands
  * status bar: shows errors / warnings, current line number and programing language
* Intelisense: smart completion
* You can turn on auto save under "File"
* New file: ctrl + N
* Extra support is required for Python
* HTML cannot be executed in VSCode preview
  * need live preview extension

### Introduction to Version Control

* Version history is tracked within the same tile
  * commit
  * branch
  * merge
* Version control options: Git / Subversion / Mercurial
* Centralized VCS - Subversion
  * files kept on a central server
  * only check out files needed, so you won't have a full copy of the project
* Distributed VCS - Git
  * project files are stored locally on a computer
  * files can also be stored on a remote server
  * only time you need to be connected to the remote server is when pushing / syncing
* The Shell
  * a user interface for communicating with an operating system's services
  * can be acced using a GUI (graphical user interface) or a CLI (command-line interface)
* GUI
  * most common way to access the shell
  * uses graphic tools
* CLI
  * terminal (mac) powershell (windows)
  * only text-based commands

### Git Concepts and Terminology

* VCS can also be reffered to as an SCM (source code manager)
* Repository: repo, directory that contains project files, where Git stores and tracks changes and revision history, can exist locally or remotely
* Commit: snapshots of project files and changes, stored in revision history
* Branch: different lines of development, allows multiple people to work on the same files at the same time
* Hosting Services - gitlab / github / bitbucket
  * allow for remote storage of repos
  * offer wikis, issue tracking, osting public and private repos, collaboration tools

### Git WorkFlow

1. create repository
2. make changes
3. add files
4. commit
5. repeat steps 2-4

* uses internal state management system
  * working directory: create, edit, delete and organize files
  * staging: revised files are ready to be commited, uses git add command
  * git commit: moves staged files to repository

### Markdown Basics

* Human Readable Markup
  * Headings: correspond to HTML h1 - h6
    * uses 1-6 # before text for various heading sizes, make sure to include space between
  * Bulleted List:
    * uses asterisk for each item, make sure to put a space after asterisk before text
    * tab / 5 spaces to create sublist
  * Numbered List
    * works the same as a bulleted list, but with numbers
    * can be combined with a bulleted list
  * Bold / Italic
    * Italic: single asterisk or underscore on each side of a phrase
    * Bold: double asterisk or underscores on each side of a phrase
    * can be layered together as a whole or one within another
  * Links / Images
    * [Link Text] (link)
    * ![Alt Text] (image link)
  * Showing Markdown Characters
    * use backslash before character

## January 11th Class Notes

### Git Commands

* commit
* add (stage)
* branch
* clone
* fetch
* push

### GitHub Commands

* fork
* pull request (pr)

We added a theme to a repo using Jekyll
