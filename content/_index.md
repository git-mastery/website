---
title: Content
type: docs
---

# Git Mastery

Welcome to Git Mastery!

Git Mastery is a Git education tool designed to make learning Git fun by introducing core Git
concepts through fun and interactive puzzles designed to put these concepts to practice immediately.

## How it works?

All exercises in Git Mastery are to be completed through your local development environment (all you need is your terminal!). By using Github Actions, we are able to perform autograding on exercise packet submissions to determine your progress on each exercise and provide concise pointers for improvement.

## Getting started

Create an empty folder to store all of your exercises.

```sh
mkdir exercises
cd exercises/
```

Download the pull script. We will use this script to retrieve the exercise packets so it's best to store it with the exercises folder you created before this.

```sh
curl -O https://raw.githubusercontent.com/git-mastery/scripts/refs/heads/main/pull.sh
```

For each exercise packets, fork the associated repository (linked in each exercise) and use the pull script to download the exercise into your exercises folder.

```sh
bash pull.sh <your Github username> <exercise packet name>
```

Work on the exercises locally by executing the Git commands necessary. Once done, you can then push your changes to your fork of your repository and make a pull request to the original exercise packet repository for the autograder to start.

## Are you ready?

Interested in levelling up your Git knowledge? Check out the various courses we have published on the left sidebar!