# Git Repositories

Version control systems are necessary tools for teams that
collaborative work on software projects together.  Even if you are
working independently, there are other benefits such as the proper
storing an labelling of versions (think: snapshots that you can
rollback to, or compare against on demand) and more robust backups if
you use a central repository or multiple clients.  To help us be more
comfortable with git, we will handle project submissions and grading
using git.

This document is a quick-start guide to ensure that you are able to
setup a repository & push and pull to a repository.  You are referred
to https://swcarpentry.github.io/git-novice/ for a more thorough
description and introduction to git.

## Installing Git

* If you are using a MacOS or Linux operating system, git should (by
default) be already installed for you.  Check by opening a terminal and typing
```shell
git version
```

* If you are using a windows system, or if you git isn't installed in
your Linux or MacOS, I recommend a graphical version of Git (e.g.,
Smartgit, https://www.syntevo.com/smartgit/ which has a free
non-commercial license if you agree to their terms) or one of these
tools: https://git-scm.com/downloads/guis The GitHub Desktop looks
good, but I have not used it before.

* After you have installed git, you will now be able to create and
 manage local git repositories on your system.

## Central Repositories

We will use a central (remote) repository to coordinate our
repositories.  The plan is for each student to own and manage their
own repositories.  The TA and myself should be added as collaborators
so that we can provide feedback on your notebooks.

* The first step is to select a site to host your remote repository.
Most companies manage their own central repository servers. We
unfortunately do not have our own centrally managed git servers at
Michigan Tech.  We will use http://github.com to host our
repositories.  This is probably the most famous git repository
because many open source software projects are hosted there.  A good
alternative (for academics) is http://bitbucket.org, which has the
added benefit of allowing you to host private repositories without
additional effort.  