# squash_lesson
Repository to learn about squash

# Content of repository

This repository conteins 4 commits.

The porpuse is how I can squash commit to only one.

## For the test of squash, execute:

  * clone this repository
  * git log
  * you should see all commits.
  * get the first, should be this: 26d5a5d
  * git checkout 26d5a5d
  * execute cherry-pick for all commits with the option -n
  * should be like this:
    * git cherry-pick -n 6946382
    * git cherry-pick -n 6031422
    * git cherry-pick -n 4fc5bb1

  In this step, the commits message are show be only "Initial commit"
