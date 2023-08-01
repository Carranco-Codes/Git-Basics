# Git-Basics
![Header Template@1x_1](https://github.com/Carranco-Codes/Git-Basics/assets/10298176/48ead034-6f2c-4353-b5cb-46343052175a)
These commands can be accessed through GitHub’s Git Cheat Sheet. GitHub is a tool that is required
at just about every job. However, it is so typical of a tool that even if it isn’t listed as a requirement, just
know that your employer will most likely expect you to have an understanding of GitHub. That said, these are the most basic commands you must know.

## Basic Commands
| Command                               |  Description                                                            |
|---------------------------------------|-------------------------------------------------------------------------|
| git init                              | Initialize an existing directory as a Git repository                    |
| git clone [url]                       | Retrieve an entire repository from a hosted location via URL            |
| git status                            | Show modified files in working directory, staged for your next commit   |
| git branch                            | List your branches. A * will appear next to the currently active branch |
| git branch [branch-name]              | create a new branch at the current commit                               |
| git checkout                          | Switch to another branch and check it out into your working directory   |
| git pull                              | Fetch and merge any commits from the tracking remote branch             |
| git add [file]                        | add a file as it looks now to your next commit (stage)                  |
| git commit -m “[descriptive message]” | Commit your staged content as a new commit snapshot                     |
| git push                              | Transmit local branch commits to the remote repository branch           |

## Objectives
- [ ] Create a new git project in your folder
- [ ] Clone a repo to your local environment
- [ ] Create a new branch
- [ ] Check the status of your project
- [ ] Checkout a branch
- [ ] Pull the latest information from your repository
- [ ] Make a change to your file and add those files to the stage
- [ ] Commit those files and add a descriptive message to the commit
- [ ] Push your changes to your remote repository

## Terms
|            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Branch     | A "branch" is a line of development. The most recent commit on a branch is referred to as the tip of that branch. The tip of the branch is referenced by a branch head, which moves forward as additional development is done on the branch. A single Git repository can track an arbitrary number of branches, but your working tree is associated with just one of them (the "current" or "checked out" branch), and HEAD points to that branch.                                                                                 |
| Checkout   | The action of updating all or part of the working tree with a tree object or blob from the object database, and updating the index and HEAD if the whole working tree has been pointed at a new branch.                                                                                                                                                                                                                                                                                                                            |
| Commit     | "As a noun: A single point in the Git history; the entire history of a project is represented as a set of interrelated commits. The word ""commit"" is often used by Git in the same places other revision control systems use the words ""revision"" or ""version"". Also used as a short hand for commit object. As a verb: The action of storing a new snapshot of the project’s state in the Git history, by creating a new commit representing the current state of the index and advancing HEAD to point at the new commit"  |
| Pull       | Pulling a branch means to fetch it and merge it. See also git-pull.                                                                                                                                         |
| Push       | Pushing a branch means to get the branch’s head ref from a remote repository, find out if it is an ancestor to the branch’s local head ref, and in that case, putting all objects, which are reachable from the local head ref, and which are missing from the remote repository, into the remote object database, and updating the remote head ref. If the remote head is not an ancestor to the local head, the push fails.                                                                                                      |
| Repository | A collection of refs together with an object database containing all objects which are reachable from the refs, possibly accompanied by meta data from one or more porcelains. A repository can share an object database with other repositories via alternates mechanism.                                                                                                                                                                                                                                                         |
| Fork       | A git fork is a copy of a repository. This copy lives on your profile and allows you to clone a repository and have access to make changes to the files. |
