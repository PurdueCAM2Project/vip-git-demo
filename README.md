Tutorial
=========

We will be using this repository to learn a bit about how to use git.
The idea is to learn a bit about git's [distributed workflow](https://git-scm.com/book/en/v2/Distributed-Git-Distributed-Workflows) concept.
After explaining the overall approach, we're going spend time doing it--as opposed to talking about it.

Basics
============

- git clone
- git pull
- git config --global --list
- git config --global user.name "Your Name"
- git config --global user.email "youraddress@yourdomain.com"
- git status
- git remote -v
- git remote add _short name_ _remote URI_
- git pull from an alternate remote

GitHub vs. Git
================

- GitHub and Git are not one in the same
- git is a general-purpose framework for version control
- GitHub is a platform for hosting a git project
- Many other platforms _use_ git: Bitbucket, Overleaf, etc.
- GitHub is a social coding platform - makes working with pull requests a snap

Interactive Session
======================

Please wait until the lecture begins before performing any of these steps.


- Create a fork of this repository.

  - You can press the Fork button on the [vip-git-demo](https://github.com/PurdueCAM2Project/vip-git-demo) page.i
  - Or you can just click [here](https://github.com/PurdueCAM2Project/vip-git-demo#fork-destination-box) to do the fork into your own GitHub account.

- Once you have a fork, you should see vip-git-demo as a project in your own account. You should also see the Fork count increase by one (on the main PurdueCAM2Project/vip-git-demo) page.

- Clone a copy of your own forked project. Do not clone the PurdueCAM2Project/vip-git-demo repository. You will not have access to push any modifications (and will be frustrated).

- Add an upstream link for pulling changes from the main PurdueCAM2Project/vip-get-demo repository.

- Follow Dr. Thiruvathukal's instructions for making some initial changes and commits to the project.

- Commit your changes.

- Return to your page at GitHub and issue a pull request.

- Pull changes from the upstream repository.

Our ultimate goal is to replicate the _integration manager_ workflow pattern described in the Git Documentation. We are using GitHub to make this workflow even more seamless.
