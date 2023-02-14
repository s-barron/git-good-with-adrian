# git-wth-adrian
This repository is used to practice git commands and github workflows for the Git Good with Adrian workshop.

# Practice Instructions
## Part 1: Setup
1. Install git on your machine and create a github account
2. On local machine, create a directory `C:\users\<yourname>\dev\`
3. Navigate to the directory `C:\users\<yourname>\dev\`
4. Clone this repository to your local machine in current directory
5. Pull latest changes from upstream remote repository
    - If there is no upstream remote repository, add it with the following command
        - `git remote add upstream https://github.com/AdrianCapacite/git-good-wth-adrian.git`
    - Pull latest changes from upstream remote repository
      - `git pull upstream master`

## Part 2: Make your changes
1. Create a new branch with your name
2. Create a new file with your name containing the following:
    - Your name
    - Your favorite programming language
3. Add the file to the staging area
4. Commit the file to the local repository
5. Merge changes into the master branch
6. Push changes to the remote repository

## Part 3: Create a pull request
1. Log into github
2. Navigate to the upstream remote repository
3. Create a pull request
4. Wait for approval

# Git Syntax
## Basic Commands
| Command | Syntax | Description |
| --- | --- | --- |
| `git clone` | `git clone <repository_url>` | Makes a copy of a remote repository onto your local machine. |
| `git pull` | `git pull <remote> <branch>` | Copies and merges changes from the remote repository to your local repository. |
| `git push` | `git push <remote> <branch>` | Copies and merges changes from your local repository to the remote repository. |
| `git add` | `git add <file_name>` | Adds changes made in the working directory to the staging area. |
| `git commit` | `git commit -m "<commit_message>"`<br>`git commit -a` | Commits changes to the local repository.<br>`-a` attribute specifies to commit changes straight from working directory to repository. Ignnores untracked files. |

## Branching Commands
| Command | Syntax | Description |
| --- | --- | --- |
| `git branch` | `git branch` | Lists all branches in the local repository. |
| `git branch` | `git branch <branch_name>` | Creates a new branch in the local repository. |
| `git checkout` | `git checkout <branch_name>` | Shows the specified branch or commit in the working directory. |
| `git branch -d` | `git branch -d <branch_name>` | Deletes the specified branch in the local repository. |
| `git merge` | `git merge <branch_name>` | Merges the specified branch into the current branch. |
| `git rebase` | `git rebase <branch_name>` | Replays commits from the current branch on top of the specified branch. |

## More Commands
| Command | Syntax | Description |
| --- | --- | --- |
| `git status` | `git status` | Shows the status of the working directory and staging area. |
| `git log` | `git log` | Shows the commit history for the current branch. |
| `git diff` | `git diff` | Shows the difference between the working directory and the staging area. |
| `git revert` | `git revert <commit_hash>` | Undos a specific commit with a new commit. |
| `git reset` | `git reset <commit_hash>`<br>`[--soft] [--mixed] [--hard]` | Moves head to the specified commit.<br>`--soft` keeps changes after specified commit in index<br>`--mixed` keeps changes after specified commit only in working directory<br>`--hard` discards all changes after specified commit |


# Additional resources
- Git Crash course: [brandon1024](https://gist.github.com/brandon1024)/[GITCRASHCOURSE.MD](https://gist.github.com/brandon1024/14b5f9fcfd982658d01811ee3045ff1e)
- Git Cheat Sheet: [https://training.github.com/downloads/github-git-cheat-sheet/](https://training.github.com/downloads/github-git-cheat-sheet/)
- Visual Git Cheat Sheet: [https://ndpsoftware.com/git-cheatsheet.html](https://ndpsoftware.com/git-cheatsheet.html)
