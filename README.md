# SoBA Web Curriculum

### Lesson 1: Git, HTML, Intro CSS

#### Overview

For this lesson you will create a new GitHub account for yourself ~ if you do not already have one ~ fork this repository to your own account, and clone it to your local machine for development. You will then complete the assignments as outlined in the instructions below and in the assignment web pages.

#### Instructions

**GITHUB**

Git is a version control system. It allows you to track changes to your source files, explore development alternatives on branches that are independent of one another, and roll back changes that you have made in error. It's awesome.

GitHub works with Git and allows us to collaborate on software projects. We can each edit a project's files without overwriting each other's work. Using git you can associate remote GitHub repositories with your local git repositories and then push and pull changes to and from the remote to your local machine.

In order to do this, you need to set up a GitHub account.

**Assignment 1**

Create a new GitHub account. You will need to set up SSH keys, which will require interacting with the Terminal. Follow GitHub's instructions and work on this with your fellow students who already have experience setting up accounts.

[https://help.github.com/articles/generating-ssh-keys](https://help.github.com/articles/generating-ssh-keys)

We will be distributing your homework assignments via GitHub. A repository will be created for each lesson and posted to this account. You will need to *fork* this repository to your own GitHub account, effecitvely creating a copy of it for you to work on, and then *clone* that repository to your computer so you can edit it.

**Assignment 2**

Fork this repository to your own GitHub account. Just press the Fork button at the top right of the page.

At this point, you should stop reading these instructions and start reading the instructions from your own copy of the repository!

**Assignment 3**

Now that you have your own personal copy of the assignment, you should download it to your machine by cloning it. Cloning the repository will initialize a new git repository on your computer and associate it with the remote repository in your account.

You'll find more information about cloning a repository at [https://help.github.com/articles/fork-a-repo](https://help.github.com/articles/fork-a-repo)

You should now have a copy of the repository on your local machine!

**Assignment 4**

Before you begin editing the HTML files for this assignment, you should create a development branch. Branching in git allows you to edit files while preserving their original content. Git makes it easy to switch back and forth between branches to see the effects of your changes as well as to merge branches when you are ready to keep your changes.

Create a new 'development' branch in your local git repository. All changes to your html should be made in this branch. Only when you are satisfied with the changes should you merge them back into your main branch.

You can read more about git branching at [http://git-scm.com/book/en/Git-Branching-Basic-Branching-and-Merging](http://git-scm.com/book/en/Git-Branching-Basic-Branching-and-Merging). This is part of an excellent free book on git.
	
**HTML5**

**Assignment 5**

You will find the rest of the instructions for this assignment embedded in the HTML files in the *html-lesson* directory. You will be converting plain text into HTML; add the required HTML tags. Each file includes additional instructions in the form of comments. I suggest approaching the assignment in the following order:

* index.html
* people.html
* resources.html
* suggestions.html
* syllabus.html

Use Python's built-in SimpleHTTPServer module to view your changes. **Never** view an HTML file directly in a web browser. Always access it through a (local) server.

In the terminal:

	cd soba-web-html-css
	python -m SimpleHTTPServer

You have three excellent resources to assist with the homework:

1. Each other!
2. [The Mozilla Developers Network](https://developer.mozilla.org/en-US/)
3. [The always amazing StackOverflow](http://stackoverflow.com/)

**CSS**

**Assignment 6**

You will find the rest of the instructions for this assignment embedded in the HTML files in the *css-lesson* directory. 

In index.html you will be addeding properties to the style declarations to produce the desired styling. 

In selectors.html you will be adding selectors and their properties to change the appearance of the page. 

**WRAP UP**

**Assignment 7**

Recall that you have been working in a development branch in your repository. When you are finished editing the HTML, checkout the master branch, merge your changes, and push them to your GitHub account. Refer to the resources mentioned in the GitHub section above if you do not know how to do this.