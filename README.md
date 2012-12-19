git-django-hooks
================

Some helper GIT hooks for my Django projects

##Installation

 * install GitPython to your environment (pip install GitPython)
 * copy hooks that you want to use to .git/hooks directory (ensure that they executable)
 * edit constants if needed
 
That's it.

##Hooks

### post-checkout
This script is made for lazy me, who tired of managing my local test DB
when trying out something that will alter it while developing a Django projects.
This script makes a copy of a local SQLite DB file on checkouts fo every branch, 
therefore making it easy to get a working version of a DB
after experements with db in some branch.

