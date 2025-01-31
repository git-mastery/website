---
weight: 1
---

# Introduction

## What is Git?

Git is a [version control system](https://www.atlassian.com/git/tutorials/what-is-version-control) first created by Linus Torvalds with the aim of managing software changes over time. It is not the first version control system (SVN and Mercurial existed before it) but it is one of the most commonly used ones.

At a high level, version control systems track the "history of changes" of a piece of software over time. Git, in particular, emphasizes the use of a decentralized collaborative workflow, allowing teams to collaborate and work on a codebase without an active connection to the centralized repository.

## Local and remote repositories

Git relies on the core concept of a repository, which is essentially a parent folder that Git is added to to monitor the changes of the folder and its contents (including sub-folders).

These repositories can exist on both your local machines or remotely on an external server (or [self-hosted](https://about.gitea.com/)). This guide will look at both instances.

[Github](https://github.com) is an example of a hosted remote Git server where you can create remote repositories and work on them locally (while pushing changes remotely, hence the "decentralized" nature of Git).

{{% hint info %}}
We will be covering how you can get your local repository changes to a remote repository like Github and vice versa in a following lesson!
{{% /hint %}}
