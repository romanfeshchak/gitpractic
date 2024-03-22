# Instructions for Setting Up a New Project "new-project"

This repository contains instructions and steps for setting up a new project "new-project" along with a development branch.

## Creating a New Repository on GitHub

1. Log in to your GitHub account (or create a new one if you don't have it yet).
2. Go to the [create a new repository page](https://github.com/new).
3. In the "Repository name" field, enter the repository name "new-project".
4. Choose the repository access: public or private.
5. Click the "Create repository" button.

## Cloning the Repository Locally

1. Open a terminal on your computer.
2. Use the `cd` command to navigate to the directory where you want to save your project.
3. Run the command: git clone <repository_url>

## Creating a Development Branch

1. Navigate into the project directory using `cd`.
2. Run the command: git checkout -b development

## Committing Changes in the Development Branch

1. git commit -m "Add new feature in development branch"

## Merging the Development Branch into the Main Branch

1. Switch to the main branch using the command: git checkout main
2. Merge the development branch into the main branch: git merge development

## Pushing Changes to GitHub

1. Push the changes to GitHub using the command: git push origin main
That's it! You have successfully created a new repository on GitHub, created a development branch, added committed the changes, and merged the development branch into the main branch.
