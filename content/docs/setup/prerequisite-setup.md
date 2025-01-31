---
title: Prerequisite Setup
type: docs
weight: 1
draft: false
---

# Prerequisite Setup

{{% hint danger %}}
It is very important that these steps are done correctly to ensure that you can follow along.
{{% /hint %}}

{{% hint info %}}
This guide assumes that you are using [Git Bash (for Windows)](https://git-scm.com/downloads) or the terminal (for MacOS and Linux) as we will be using bash commands.\
\
If you are facing issues with running certain commands (especially on Windows), please consider using Git Bash instead.
{{% /hint %}}

## Git

Follow the installation steps for your [operating system (OS) here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

To ensure that everything is working, run the following commands:

```bash
git version
```

You should see text like this:

```bash
git version 2.48.1
```

Once Git is setup on your local machine, do some initial configuration:

```bash
git config --global user.email "<your email>"
```

```bash
git config --global user.name "<your name>"
```

## Github

Setup Github by following the instructions below.

1. Create a [new Github account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github) _if you don’t have an account_
2. Connecting to [Github with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
   1. Generate a new SSH key
   2. Add the SSH key to Github

To verify that Github is working, refer to [this guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection?platform=mac) and run the given command (`ssh -T git@github.com`) to ensure that your SSH connection is working correctly.

## Setting up Git Mastery

Once you have completed the setup for Git and Github, please refer to the [next guide to setup Git Mastery for your local machine](/docs/setup/git-mastery-setup)!
