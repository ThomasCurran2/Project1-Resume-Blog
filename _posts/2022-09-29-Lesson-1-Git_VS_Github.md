---
title:  "Git VS Github, HTML and CSS"
modified: 2022-09-06T16:03:49-04:00
categories: 
  - Git
  - Github
  - HTML
  - CSS
tags:
  - HTML
  - CSS

---

<img src="/Project1-Resume-Blog/images/Github_postImage.png" alt="Github_newlogo">

Git and Github are both powerful tools when it comes to coding project development. However many may not know the differneces between Git and Github.

{% include base_path %}

{% include toc title="Getting Started" %}

Git is a version control system that allows you to take snapshots, preform rollbacks, and view the history of all changes to your files. While GitHub is a website that allows you to centralize your Git history in one place, which is helpful to remote developers that don't directly have the source code on their computer. The following section will break down both tools and will mention some of their more specific uses.

This code can be written in the HTML format, Hyper Text Markup Language, with CSS, Cascading Style Sheets, to add stylization to the pages.

## Git: Version control 

Git is a program operated through the control panel and other similar software that allows the user to push thier code to repositories, restore previous versions of their code, and view their commit history.

An example of working with Git looks something like this:

<img src="/Project1-Resume-Blog/images/Git_Console.png" alt="Git_Terminal" width="500"/>

Some of the more basic commands include: 

`$ git init` - Turns a directory into a repository.

`$ git branch [branch-name]` - Creates a new branch to work on.

`$ git fetch` - Downloads all history from remote tracking branches.

`$ git merge` - Combines remote traking branch with the local branch.

`$ git push` - Pushes commits to Github.

`git pull` - Updates your current branch to match the code in the Github repository.

`$ git commit -m "[commit message]"` - Adds a file snapshot to version history that can be pushed.

These commands allow the user to more easily keep track of different versions of the same code and allows them to backup their work to Github.


## Github: Featrues and Functions

Github is a website developers can use to push their local repositories to remote repositories. This allows for developers who don't have the most up to date code on their computers to be able to download and work on the most recent build.

Github's interface looks like this:

<img src="/Project1-Resume-Blog/images/Github_look.PNG" alt="Github_image" width="500"/>

Some of  Github's features include:

`Branches` - Alternate versions of the Master code that allow for developers to edit the code without any risk of the source code being unusable in the event of an error.

`Forking` - Creates a copy of another repository for you to work on.

`Pull requests` - Created when a developer wants to merge code from a branch to the main branch. Must be accepted for the merge to take place.

`Cloning` - Repositories can be cloned locally so that they can be worked on even if you didn'y have the code to start with.

`Pushing` - You can push your code using Git to Github to have it saved to a remote repository that anyone can download and work on.

Github makes collaborative code development easy by allowing multiple developers work on a project remotly.

## HTML: Tags and Webpages

HTML, or Hyper Text Markup Language can be used in an IDE, integrated development enviornment, to construct webpages.

An example og HTML looks like this:


<img src="/Project1-Resume-Blog/images/HTML_example.jpg" alt="HTML_code" width="500"/>

Tags are used to designate how the code will be have or look, and can take in attributes to modify their functions:

`<p>` - Paragraph tag, groups words together in a paragraph.

`<em>` - Puts italics on the works inside the opening and closing tags.

`<strong>` - puts the words in bold.

`<a href = "link" title = "website name">` - Tag that creates a clickable link. Takes in attributes to get the link address and website name.

`<!DOCTYPE html>` - Defines doc type and the rules to follow. Put at the start of a file.

`<html>` - Placed around the entire file.

`<head> or <header>` - Holds metadata for the file.

`<title>` - Holds the title of the page for the browser.

`<body>` - Holds all of the content shown on the page.

HTML can be used to create websites and can be styled using CSS.

## CSS: Styling the page

CSS, Cascading style sheets, are used to stylize a page and can add anything from colored text to a colored background.

A page using CSS looks like this:

<img src="/Project1-Resume-Blog/images/CSS_example.png" alt="CSS_page" width="500"/>

Types of CSS include:

`External style sheet` - The user can set styles to tags and other parts of code from an external file and link to it in the main file.

`Internal style sheet` - The user can set what tags and other peices of code's styling directly in the main file.

`Inline` - The "<stlye>" tag can be used with attributes to style specific lines in an HTML file.
  

---

That's everything from lesson 1! My next post will be on lesson 2, which covers workflow and different collaborative strategies.
