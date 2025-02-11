---
title: Content
type: docs
---

# Welcome to Git Mastery!

{{% hint info %}}
Git Mastery is a Git education tool designed to make learning Git fun by introducing core Git
concepts through fun and interactive puzzles designed to put these concepts to practice immediately.
{{% /hint %}}

Master Git by completing exercises on your local machine!

## Why Git Mastery?

Traditionally, Git is often viewed as a sequence of commands to get from state {{< katex >}}A{{< /katex >}} (having some changes locally) to state {{< katex >}}B{{< /katex >}} (having those changes on a Git server like Github).

As a result, most students will often focus on memorizing a series of commands without actually understanding what each command does. So, when they encounter state {{< katex >}}A'{{< /katex >}} (say a merge conflict), they are often unable to "get unstuck".

<div style="text-align: center;">
  <img src="docs/git-education.png" width="200px" />
</div>

By completing various exercises that requires the use of various Git commands, students will start developing an intuition for what each command does. This intuition will allow them to visualize and appropriately apply the exact commands needed to "get unstuck".

## How it works

Git Mastery relies only on Git and Github to perform the autograding. By leveraging [Github Actions](https://github.com/features/actions) and several self-published Python packages (like [`difflib-parser`](https://pypi.org/project/difflib-parser/) and [`git-autograder`](https://pypi.org/project/git-autograder/)), our workflows will grade your attempts at every exercise, giving you concise feedback on what went wrong, and recording your progress for your teachers to refer to.

## Are you ready?

Ready to level up your Git knowledge?

Start by [setting up your local environment](/docs/setup/prerequisite-setup), followed by [setting up your local machine to work with the Git Mastery exercises](/docs/setup/git-mastery-setup), and dive straight into [our curated lessons](/docs/lessons)!

## Credits

The lesson contents were adapted from the [NUS Hackers Orbital Git workshop material](https://wiki.nushackers.org/orbital/git) (because [Jiahao](https://woojiahao.com), the primary developer of Git Mastery was the person who had also written the NUS Hackers Orbital Git workshop material).
