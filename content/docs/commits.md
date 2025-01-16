---
draft: false
---

## What is a commit?

*TODO*

## Creating commits

```bash
git commit -m <commit message>
```

## Exercises

### Prerequisite

Create a local folder for all of your exercises:

```bash
mkdir exercises
cd exercises/
```

Download `pull.sh`:

```bash
curl -O https://github.com/git-mastery/scripts/blob/main/pull.sh
```

Give the script permissions:

```bash
chmod +x pull.sh
```

### Exercise 1

Fork the repository: <https://github.com/git-mastery/commit-1/fork>

Execute `pull.sh`:

```bash
bash pull.sh <your Github username> commit-1
```

#### Goal

Edit the `README.md` file to have any text.

Commit and push the change to the repository.

<!-- TODO: Include hints -->

### Exercise 2

Fork the repository: <https://github.com/git-mastery/commit-2/fork>

Execute `pull.sh`:

```bash
bash pull.sh <your Github username> commit-2
```

#### Goal

Add a new file and put in any content you want (non-empty). Create a commit for this file.

Edit the file and create another commit.

Push the change to the repository.