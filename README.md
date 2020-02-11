# Feature Branch

This is a guided exercise for a pair of students, walking through how to create
an use feature branches. Within your pair, decide who should play the role of
**Student 1** and **Student 2**.

## Setup

Continue working in the `workflow_practice` repository from the earlier mergeConflicts activity

## Feature Branches

Feature branches are useful for - you guessed it - building out a feature in
isolation. Work on one feature branch won't affect work on another and they can
be merged back in to master when ready.

This application is a simple website built with React. Both students will be
creating a feature branch, building out a new component on their feature branch
then pushing their feature branch to GitHub and creating a pull request.

## Steps

**Student 1**

Create a feature branch called `home-page`. Inside of `Home.js` build out a
simple component called `<Home>` that renders an `<h1>` with "Home" in it.

**Student 2**

Create a feature branch called `about-page`. Inside of `About.js`, build out a
simple component called `<About>` that renders an `<h1>` with "About" in it.

**Both Students**

Add and commit your changes. Then push them up to the remote version of your
feature branch (`git push origin <branch_name>`). On GitHub, make a pull request
from your branch for your changes to be merged in.

Student 1 should merge Student 2's pull request and vice versa. If there are
merge conflicts, go a head and resolve them.

**Both Students** Check out `master` and pull the latest changes. You should
have both the `<Home>` and `<About>` components now.
