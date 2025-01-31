---
title: Git Mastery Setup
type: docs
weight: 2
draft: false
---

# Git Mastery Setup

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
