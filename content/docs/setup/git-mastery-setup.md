---
title: Git Mastery Setup
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

Download the pull script.

{{% hint info %}}
We use this script to download exercises so store it with the `exercises/` folder
{{% /hint %}}

```sh
curl -O https://raw.githubusercontent.com/git-mastery/scripts/refs/heads/main/pull.sh
```

For each exercise, fork the associated repository (linked in each exercise) and use the above `pull.sh` script to download the exercise into your exercises folder.

```sh
bash pull.sh <your Github username> <exercise packet name>
```

Work on the exercises locally by executing the Git commands necessary. Once done, you can then push your changes to your fork of your repository and make a pull request to the original exercise packet repository for the autograder to start.

## Diagnostic exercise

To ensure that you have setup your local machine correctly to start using Git Mastery, we have prepared a diagnostic exercise for you to verify.

Fork the [`diagnostics` repository](https://github.com/git-mastery/diagnostic/fork) and keep the repository name as it is.

Download the exercise to your local machine.

```sh
bash pull.sh <your Github username> diagnostic
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
git push -u origin main
```

Create a pull request on the exercise's repository. You can leave all of the other fields blank.

{{% hint warning %}}
For instructions to create a pull request, refer to this [page](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork).

We will cover pull requests in a bit, but no knowledge of pull requests is necessary for this diagnostic exercise.
{{% /hint %}}

<div style="text-align: center;">
  <img src="pr.png" width="800px" />
</div>

If everything went well, you should see the following success message on the pull request.

<div style="text-align: center;">
  <img src="success.png" width="800px" />
</div>

Hurray! You are now ready to begin on your journey to mastering Git! Follow the lessons on the sidebar to start!
