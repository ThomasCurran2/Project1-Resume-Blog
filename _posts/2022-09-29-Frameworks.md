---
title: "Frameworks"
excerpt: "What are frameworks and how can they be used?."
modified: 2022-09-29T09:55:10-04:00
header:
  teaser: "markup-syntax-highlighting-teaser.jpg"
categories: 
  - Framework
  - Bootstrap
  - Jekyll
tags: 
  - Terms
  - code
---

Frameworks can be used by developers to speed up development time by using templets that give structure to a website. Some of these frameworks include Bootstrap and Jekyll which give structure and other customization options to developers. To start off with, what is a frame work and why would be use one?

### Frameworks

A framework is prewritten code that gives the user structure to build their own apllications. Web frameworks specifically provide code that helps developers build their own websites. For the most part their are 2 different types of frameworks:

`Batteries included` - The code provided has a lot of high end integrations done for you. This means the code is very opinionated when it comes to how authentication, database connections, and the UI work. This also means you have a little room for customization but allows you to prototype quicker as it does a lot of the complex things for you.

`Batteries not included` - This means a lot of the choices on how to connect to a database or how to do authentication is left up to the developer. This allows for a highly customized application but might take a little bit longer to prototype as a developer might have to make some core decisions for themselves.

In the next sections I'll explain some popular frameworks and some code that can be used to customize them.

### Bootstrap

Bootstrap allows users to creat web pages that scale well on many devices such as PC, phones, and tablets. Bootstrap does this by letting the developer decide what code is placed in specific rows and columns so no matter what aspect ratio or device the code in each section will stay together and scale. There are specifically 12 columns and an unlimited amount of rows to work with.

Bootstrap can be added to a file as easily as adding a few lines in the header:

<img src="/Project1-Resume-Blog/images/Bootstrap_example.PNG" alt="Bootstrap_pic" width="500"/>

Here you can see the links in the header that give your file bootstrap as well as lines of code that break up your code into specific rows and columns.

### Jekyll

Finally, Jekyll allows users to quickly make static web pages without needing to know much HTML or CSS. A static page refers to a web page without any content that would change after a user would interact with it, such as a comment section.

Jekyll uses the programming language Ruby to create some of its files and to run locally on localhost:4000. Some of the commands look like:

`gem install jekyll bundler` - Installs jekyll and gem files to a directory.

`cd directory name` - Changes your directory.

`bundle exec jekyll serve` - builds the site on localhost.

For an example of what a page made from Jekyll might looks like just take a moment and look around this website, that right this website uses Jekyll! Jekyll files can be added to a remote repository on Github and can be used to make a website hosted on Github pages.

---

Thats everything for frameworks, check out my previous posts or look at Lesson 4 if you want to continue.
