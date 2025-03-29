# GitHub Basics

This repository provides a fundamental guide to using Git and GitHub. It covers essential Git commands for repository initialization, tracking changes, branching, merging, and pushing code to a remote repository.

## Getting Started

To begin using Git, initialize a new repository in your project folder:

```sh
git init
```

## Tracking Changes

Check the current state of your Git repository:

```sh
git status
```

Stage files for commit:

```sh
git add file_name  # Stage a specific file
git add .          # Stage all changes in the directory
```

Unstage a file:

```sh
git rm --cached file_name
```

Commit staged changes with a message:

```sh
git commit -m "Your commit message"
```

View commit history in a compact format:

```sh
git log --oneline
```

## Branching & Merging

Create a new branch:

```sh
git checkout -b branch_name
```

Switch to an existing branch:

```sh
git checkout branch_name
git switch branch_name
```

Merge a branch:

```sh
git merge branch_name
```

## Pushing to GitHub

Link your local repository to a GitHub repository:

```sh
git remote add origin https://github.com/armaanepiic/Github-Basics.git
```

Rename the default branch to `main`:

```sh
git branch -M main
```

Push the `main` branch to GitHub and set it as the upstream branch:

```sh
git push -u origin main
```

Push another branch to GitHub:

```sh
git push -u origin "another branch name"
```

## Contributing

Feel free to fork this repository, create a new branch, make changes, and submit a pull request.

## License

This project is open-source and available under the MIT License.

