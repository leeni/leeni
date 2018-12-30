---
layout: default
---

## Course Introduction

> **Official Course Introduction:** This is a gentle introduction to command-line tools for linguists. It is aimed at bachelor students in languages who are interested in language technology. This course covers the fundamentals of Unix-like command-line environments for linguists.

The Command-Line Course covers introduction to basic unix file and process concepts and also teaches how to navigate in unix file system and how to install and run programs made with different programming languages.

As it is aimed for linguists, the Command-Line Course teaches the basics of text processing and how to write programs which help to analyse text, using gutenberg project books as example material.

The course also includes basics of version control using Git as the example version control system.
In the end of the course the participants create a webpage about their learnings using GitHub Pages.

### Command-Line Course Videos Playlist @ YouTube

[![Command-line Course Videos](http://img.youtube.com/vi/j9Oi10ggoxY/0.jpg)](http://www.youtube.com/watch?v=j9Oi10ggoxY&list=PLtpBLbHSJbOUh9JZzGWekDn-9BecuqPfa "Command-Line Course Videos")

#### My favourite course videos

| Video name    | Course Week   |
| :-------------|:------------- |
| col 3 is      | right-aligned |
| col 2 is      | centered      |
| zebra stripes | are neat      |


## Week 1: Introduction to Command-Line Environments

#### Overview

The main content for this week was to learn how to
*   open and operate the command line
*   create or download files and folders
*   learn to use nano text editor

#### Some command examples using *bash*
```
$ cd <location>       #go to location
$ mkdir <folder_name> #create a folder
$ wget <web location> #download content from the web
$ nano <file_name>    #opening a file with nano file editor
```
> **My learning experience:** Excluding using nano, the content in the week 1 was mostly familiar to me, as I had previously used command line at work and at some other courses. However, it was great to learn how to use nano as text editor, I had previously only tried to use vim, which is more difficult to use. Additionally, I had never really used wget to download files before.


## Week 2: Navigating a UNIX System

#### Overview

The main content for this week was to learn
*   about files and folders in UNIX file system including links
*   about setting and modifying permissions and about sudo
*   about processes within UNIX system
*   about ssh and working with remote servers

#### Some command examples using *bash*

```
$ chmod <permissions> <file or folder>  #set permissions for a file or folder
$ sudo <command>                        #execute command as super user
$ ssh <server>                          #creating a connection to a remote server
```
> **My learning experience:** This week was still mostly familiar to me. The most challenging was to learn how to use the permissions since the syntax is not them most intuitive. It was also a good refresher to watch all the videos about the file system in UNIX and compare it to Windows.
> This week's XKCD comic explained how SUDO works.
>
> ![XKCD-Comic about SUDO](https://imgs.xkcd.com/comics/sandwich.png)


## Week 3: Corpus Processing

#### Overview

The main content for this week was to learn how to
*   TODO

```
$ cd .. #go one folder up
$ pwd #tell me where I am
$ ls #list folder content
```
> **My learning experience:** TODO



## Week 4: Scripting and UNIX Configuration Files

#### Overview

The main content for this week was to learn how to
*   TODO

```
$ cd .. #go one folder up
$ pwd #tell me where I am
$ ls #list folder content
```
> **My learning experience:** TODO


## Week 5: Installing and Running Programs

#### Overview

The main content for this week was to learn how to
*   TODO


```
$ cd .. #go one folder up
$ pwd #tell me where I am
$ ls #list folder content
```
> **My learning experience:** TODO


## Week 6: Version Control

#### Overview

The main content for this week were
*   how version control works in principle
*   creating a GitHub repository
*   adding new commits and pushing them with git
*   reverting commits
*   creating new branches and changing a branch
*   ... additionally, installing and running Java in commandline

```
$ git commit -m "message"   #commit staged changes with a commit message
$ git push                  #push changes to make them visible for others
$ git branch                #see list of all branches and which branch is now used
```
> **My learning experience:** I had a fair amount of experience using a version control system, though mostly I have used mercurial, not git. I have used git a little bit, but I was not completely comfortable with it before. It was very intersting to learn how to revert commits and change between commits and branches.

## Week 7: Project

#### Overview

The main content for this week were to learn how to
*   use GitHub pages
*   use Git in a "real" project with feature branches
*   use jekyll
*   use markdown (create and edit .md files)

#### Some command examples using *md* and *bash*
```
$ ##                        # level 2 header in md
$ *                         # list item in md
$ [link_text](link)         #adding a link in md
$ bundle exec jekyll serve  #building with jekyll in bash
```
> **My learning experience:** I had previous experience about creating web pages, but never with jekyll or github pages. I also had never used markdown, even though it is very similar to the syntax used in e.g. atlassian wiki pages or JIRA. It took me a while to understand the structure of the files and what needs to be put where.
> Additionally, installing and using jekyll (and ruby stuff in general) was very difficult, since I had multiple pythons, apparently multiple ruby installations and bundle just was never found correctly, so I had to hack the alias for the correct bundle location to finally make jekyll work so that I could locally build the website.
