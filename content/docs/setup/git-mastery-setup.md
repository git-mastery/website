---
title: Git Mastery
type: docs
weight: 2
draft: false
---

# Git Mastery Setup

{{% hint warning %}}
Ensure that you have properly setup Git and Github as per the [previous guide](/docs/setup/prerequisite-setup)!
{{% /hint %}}

Create an empty folder to store all of your exercises.

```sh
mkdir exercises
cd exercises/
```

Get the download script.

{{% hint info %}}
We use this script to download exercises so store it with the `exercises/` folder
{{% /hint %}}

```sh
curl -O https://raw.githubusercontent.com/git-mastery/scripts/refs/heads/main/download.sh
```

This script will use Github CLI to automate the forking and cloning process.

For each exercise, run the following commands:

```sh
bash download.sh <exercise name>
```

Work on the exercises locally by executing the Git commands necessary. Once done, you can typically use the included `submit.sh` script in each exercise.

```bash
bash submit.sh
```

## Diagnostic exercise

To ensure that you have setup your local machine correctly to start using Git Mastery, try running the following diagnostic exercise.

Download the exercise to your local machine.

```sh
bash download.sh diagnostic
```

Change directory into the exercise.

```sh
cd diagnostic/
```

Run the following commands inside the exercise.

{{% hint info %}}
Essentially, we're creating an empty commit just for the autograder to detect and output whether Git Mastery was setup correctly.
{{% /hint %}}

```sh
git commit --allow-empty -m "Test commit"
```

Push the commit to your fork.

```bash
bash submit.sh
```

This should automatically create a pull request for this exercise which you can see here: <https://github.com/git-mastery/diagnostic/pulls> using the following format: `[Github username] [diagnostic] Submission`.

If everything went well, you should see the following success message on the pull request.

<div style="text-align: center;">
  <img src="success.png" width="800px" />
</div>

Hurray! You are now ready to begin on your journey to mastering Git! Follow the lessons on the sidebar to start!
