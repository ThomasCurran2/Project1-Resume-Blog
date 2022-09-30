---
title:  "Workflow and Strategies"
modified: 2022-09-29T12:24:42-04:00
categories: 
  - Git
  - IDE
  - Terminal
tags:
  - practices
  - terms
---

Lesson 2 covers the different programs involved in a programmers workflow as well as some coding strategies that are used for coding collaboratively.

{% include base_path %}

{% include toc title="Getting Started" %}


## Workflow: Software and Terms

The standard workflow for a program involves and IDE, integrated development enviornment, where you can edit HTML, CSS, and Javascript code. Additionally, A terminal application that allows the user to utilize command line tools is involved to use Git ans its version control.

I personally use my computers built in command console to utilize Git and Notepad++ as my IDE. Check out Notepad++:

<img src="/Project1-Resume-Blog/images/Notepad++_image.jpg" alt="Notepad++_pic" width="500"/>
<a href="https://notepad-plus-plus.org/">NotePad++ Website</a>

These applications would be used to write code, use version control operations on it, and send the code to a remote repository. However, this strategy isn't the most effective when working with a large group of developers.


## Strategies: What are they and why use them?

There are many different ways to work with Git when collaborating with a team. To lessen the stress of multiple developers having to figure out conflicting files in a single main branch many strategies have been created to make development more efficient. Each of them have their pros and cons but here are some of the most popular ones:

`Truck based development` - Developers merge small, frequent updates to a main "trunk" or branch.

`Feature Branches` - When a team creates and works on a branch that is a copy of the main code to develop a new feature.

`Git Flow` - Uses a main and development branch to hold the current release version and development versions that have new features.

Workflow strategies have their pros and cons so one type might not be the best for every type of project due to various reasons. In general, these strategies streamline the development process and help to avoid the confusion that would come from multiple developers all pushing conflicting code to a singular main branch.

---

For the next blog post I'm going to be talking about Lesson 3, which is on frameworks, bootstraps, and Jekyll.

