# Welcome to Your First GitHub Project!

## This README will walk you through the steps of pushing your code to GitHub and creating pull requests (PRs) for review.

### Prerequisites:

A GitHub account (free to create) - [create github account](https://github.com/join)
Git installed on your local machine [Download](https://git-scm.com/downloads)
A code editor of your choice (e.g., Visual Studio Code, Sublime Text)

# Pushing Your Code to GitHub

## Clone the Repository:
Open a terminal or command prompt and navigate to your desired local directory. Run the following command, replacing <URL> with the HTTPS clone URL provided by GitHub when you created the repository:

``` Bash
git clone <URL>
```
This creates a local copy of your repository on your machine.

## Make Changes:
Open the cloned folder in your code editor and make your desired changes to the files.

## Stage Your Changes:
Use Git to tell it which changes you want to include in your next commit. In your terminal, navigate to your project directory and run:

```Bash
git add .
```

The . tells Git to add all modified files. You can also add specific files using git add <filename>.

## Commit Your Changes:
Create a snapshot of your staged changes with a descriptive message using:

```Bash
git commit -m "Your informative commit message"
```
Replace "Your informative commit message" with a brief explanation of what you changed. Good commit messages help others understand your code's evolution.

## Push Your Changes:
Finally, push your local commits to the remote repository on GitHub:

```Bash
git push origin main
```
Replace main with the branch name you want to push to (usually main for the main branch).

## Creating a Pull Request (PR)

+ Navigate to Your Repository on GitHub:
  Go to your repository's page on GitHub in your web browser.

+ Click "Pull Requests":
 Look for the "Pull requests" tab or button and click it.

+ Create New Pull Request:
 Click the button to create a new pull request.

+ Compare Branches:
 GitHub will automatically detect your local branch and suggest the main branch for comparison. Confirm these.

+ Write a Clear Title and Description:
 Provide a concise title that summarizes your changes and a detailed description explaining what you did and why.

+ Submit Pull Request:
 Once satisfied, click the button to submit your pull request.

# Congratulations!

You've successfully pushed your code to GitHub and created a pull request for review. Others can now review and discuss your changes before merging them into the main branch.


 
