# Basic Git Commands Tutorial

This tutorial covers essential Git commands to help you work with repositories, branches, commits, and more.

## 1. Cloning a Remote Repository

To clone a remote repository into your local machine, use the `git clone` command.

### Command

```
git clone <repository_url>
```

<repository_url>: The URL of the repository you want to clone.

#### Example

```bash
git clone https://github.com/user/repository.git
```

This command will create a local copy of the remote repository in your current directory.

2. Creating a New Branch

Branches in Git allow you to work on separate features or changes without affecting the main project.
Command

````bash

git branch <branch_name>

    <branch_name>: The name of the new branch you want to create.

Example

```bash

git branch feature-xyz

````

This command will create a new branch called feature-xyz. 3. Switching to an Existing Branch

To switch between branches, use the git checkout command.
Command

```bash

git checkout <branch_name>
```

    <branch_name>: The name of the branch you want to switch to.

Example

```bash

git checkout feature-xyz
```

This command will switch your working directory to the feature-xyz branch. 4. Creating and Switching to a New Branch

To create a new branch and switch to it immediately, combine the checkout command with the -b option.
Command

```bash

git checkout -b <branch_name>
```

    <branch_name>: The name of the new branch to create and switch to.

Example

```bash

git checkout -b new-feature
```

This command will create a new branch called new-feature and switch to it. 5. Adding Changes to the Staging Area

Before committing changes, you need to add them to the staging area using git add.
Command

```bash

git add <file_name>
```

    <file_name>: The file(s) you want to add to the staging area.

Example

```bash

git add index.html
```

This command adds index.html to the staging area, preparing it for the next commit. 6. Committing Changes with a Descriptive Message

Once you've staged changes, you can commit them to the repository with a message that describes the changes.
Command

```bash

git commit -m "Commit message"
```

    -m "Commit message": A descriptive message explaining the changes in this commit.

Example

```bash

git commit -m "Add new feature to homepage"
```

This command commits the changes with the message "Add new feature to homepage." 7. Pulling Changes from the Remote Repository

To fetch and integrate changes from a remote repository, use git pull.
Command

```bash

git pull origin <branch_name>
```

    origin: The default name for the remote repository.
    <branch_name>: The branch you want to pull changes from.

Example

```bash

git pull origin main
```

This command fetches changes from the main branch of the remote repository and merges them into your current branch. 8. Pushing Changes to the Remote Repository

After committing changes locally, you can push them to the remote repository using git push.
Command

```bash

git push origin <branch_name>
```

    origin: The name of the remote repository.
    <branch_name>: The branch you want to push changes to.

Example

```bash

git push origin feature-xyz
```

This command pushes the changes from the feature-xyz branch to the remote repository.
