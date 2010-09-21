!SLIDE title-slide center

![git-scm.com](wiki.png)

# Git - Quick-n-dirty

!SLIDE bullets incremental

# Who am I

* Jochen Kramer, AKRA GmbH
* RubyTuesday? Started learning Rails at Qype in 2006
* Am using Git for 1 year now

!SLIDE

# What is Git?

## Git is a free & open source, distributed version control system

!SLIDE bullets incremental

# Git - Plumbing and Porcelains

* The low-level part of Git is called plumbing

* <em> Besides providing a version control system, the Git project provides a generic low-level toolkit for tree history storage and directory content management </em>

* The interfaces and frontends are called porcelains

!SLIDE bullets incremental

# A short history of Git

* 03 April 2005: Development started by Linus Torvalds

* 16 Juni 2005: first Kernel release with Git

* 26 July 2005: Junio Hamano is the Git maintainer

!SLIDE bullets incremental

# Given I am a developer, why Git?

* commit your changes locally

* use local branches without (to much) pain

* merge changes without (to much) pain

* share branches easily remote

!SLIDE bullets incremental
 
# Some Git Glossary (for SVN users) #

* Repository: local - init a repository, remote - clone a whole repository to the local filesystem

* Branches & Tags: You have cloned the whole Repository, everything is included

* Revisions: SHA1 Hash for Revision Identification (distributed)

!SLIDE commandline

# How to use Git? #

    $ git init

    $ touch a_file
    
    $ git add .
    
    $ git ci -m 'initialized new project with a_file'

!SLIDE

# How to use Git (interactive) #
  
## let's open a shell ...

!SLIDE commandline

# Typically VCS Commands with Git #

    $ git checkout
    $ git diff
    $ git show
    $ git status
    $ git log
    $ git checkout -b <name>
    $ git merge 

!SLIDE commandline

# How would I use git distributed

## rails from _github.com_

    $ git clone git://github.com/rails/rails.git
    
    $ git pull
    
    $ git push (core contributer only, sorry)

!SLIDE bullets incremental

# Octopus? Fork?

* Octupus merge (many heads to be merged into one branch)

* Fork is technically a clone, but on _github.com_ it's the users interaction via public, cloned git repositories and pull requests

!SLIDE

# References #

#### Books

* [The Git Community Book][git-community-book] on git-scm.com
* [Pro Git][pro-git], Scott Chacon, 08.2009

#### Videos

* [Gittin down to the Plumbing][git-plumbing-src2010], Scott Chacon on the _Scottish Ruby Conference 2010_ (did this again on the _Euruko 2010_)
* [Git Cast][git-casts], nice Video Casts with one topic: Git

#### Slides

* [Getting Git][getting-git], Scott Chacon
* [Git 101][git-101], Scott Chacon

#### Online Reference

* [Main Git Page][git-scm] on git-scm.com
* [Git Tips][mislav-git-tips] from mislav
* [Git SVN Crash Course][git-svn]
* [Git Ready][git-ready]
* [Git Cheat Sheet][git-cheat-sheet]

#### Release Management

* [Git branching model][git-flow] Some Ideas for release management, including git-flow commands (think svk)

[git-flow]: http://nvie.com/posts/a-successful-git-branching-model/
[git-plumbing-src2010]: http://video2010.scottishrubyconference.com/show_video/11/0
[pro-git]: http://progit.org/book/
[git-community-book]: http://book.git-scm.com/
[git-casts]: http://www.gitcasts.com/
[git-scm]: http://git-scm.com/
[mislav-git-tips]: http://mislav.uniqpath.com/2010/07/git-tips/
[git-svn]: http://git.or.cz/course/svn.html
[git-ready]: http://gitready.com/
[git-cheat-sheet]: http://cheat.errtheblog.com/s/git/
[getting-git]: http://www.slideshare.net/chacon/getting-git
[git-101]: http://www.slideshare.net/chacon/git-101-presentation
[github]: http://github.com/
