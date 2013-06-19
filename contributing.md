# How to contribute

I love my project but it's not perfect, and you can help me to offer good UI modules. You can submit an issue, an idea, a fix of modules, or new modules.

## Getting started

* Make sure you have a [GitHub account](https://github.com/signup/free)
* Submit a ticket for your issue, assuming one does not already exist.
    * Clearly describe the issue including steps to reproduce when it is a bug.
    * Make sure you fill in the earliest version that you know has the issue.
* Submit a ticket for an idea of new module, with the prefix [idea]
* Fork the repository on GitHub

## Branchs

This project has several branchs

* master : official and stable version
* develop : version for test, before master
* features/$module_name : a branch by experimental module

## Making changes

* Clone your fork
    * For a fix, create a new branch from the branch where you find issue
    * For a new module, create a new branch from master
* Never do your changes on master
* Create a new branch by change
* The name of your new branch must be
    * fix/$branch/$title_issue : for a fix on the branch $branch
    * module/$new_module_name : for a new module

## Submitting changes

* Submit a fix
    * for an issue on master, do your pull request on develop branch
    * for an issue on develop, do your pull request on develop branch
    * for an issue on branch of module, do your pull request on the same branch
* Submit a new module
    * do your pull request on develop branch

## Syntax

* Two spaces, no tabs
* KSS comments