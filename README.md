# Git File Tracking, Commit Management, and Repository Maintenance

## 1. Git File Tracking Overview

Git file tracking is the process of monitoring and managing changes made to files within a repository. It enables developers to record modifications, compare versions, and restore previous states when required. Every file in a Git repository is either tracked or untracked. Tracked files are included in version control and are monitored for changes, while untracked files are newly created files that Git has not yet been asked to follow.

The core purpose of Git file tracking is to maintain a reliable record of project documents, source code, configuration files, and related assets. This allows multiple contributors to work together in a structured and organized manner. Tracking files with Git makes it possible to create snapshots of the project at different points in time so that progress can be reviewed without losing earlier work.

Important Git commands for file tracking include:
- git status: shows the current state of the working directory and staging area.
- git add: stages files for tracking or updates their state before commit.
- git rm: removes a file from the repository and optionally from the working directory.
- git checkout or git restore: retrieves previous versions of files when needed.

This process helps maintain a clean and accurate project history, allowing teams to know what changed, when it changed, and by whom.

## 2. Commit Management

Commit management is a central feature of Git that allows developers to save sets of changes with descriptive messages. A commit represents a snapshot of the repository at a specific moment in time. It captures the current state of tracked files and preserves it in the project history.

Each commit should be meaningful and precise. A clear commit message helps team members understand the purpose of the change without reading the entire code. Commit messages should explain what was changed and why it was necessary. For example, a commit could be described as "Add user authentication validation" or "Fix merge conflict in dashboard component".

Good commit management practices include:
- Making small, focused commits rather than large unrelated changes.
- Writing clear and descriptive commit messages.
- Staging only the files needed for the current task.
- Reviewing changes before committing.
- Using branches to keep work separate and organized.

Common commit commands include:
- git commit -m "message": creates a commit with a short message.
- git log: displays the history of commits.
- git diff: shows changes between working files and previous versions.
- git revert: creates a new commit that undoes an earlier change safely.

Proper commit management improves collaboration, reduces confusion, and supports efficient debugging and project maintenance.

## 3. Repository Maintenance

Repository maintenance refers to the ongoing care and organization required to keep a Git repository healthy, efficient, and easy to use. This includes managing branches, cleaning up outdated files, monitoring merge history, and ensuring that all team members work with a consistent repository structure.

A well-maintained repository reduces errors and supports long-term project sustainability. Maintenance tasks often include:
- Creating and deleting branches when work is complete.
- Merging feature branches into the main branch carefully.
- Resolving conflicts before final integration.
- Removing unnecessary or duplicate files.
- Keeping documentation and configuration up to date.
- Backing up important branches and tags.

Git branches such as Cricket, Football, and Basketball can be used to organize work according to different tasks or development streams. Branches allow isolated work, which reduces the risk of interfering with the main project. Once a branch is complete, it can be merged into the main branch after review and testing.

Useful repository maintenance commands include:
- git branch: lists project branches.
- git checkout or git switch: moves between branches.
- git merge: combines changes from one branch into another.
- git pull: updates the current branch with changes from the remote repository.
- git push: sends local commits to a remote repository.

Repository maintenance helps ensure that the project remains reliable, secure, and ready for collaboration over time.

## 4. Conclusion

In summary, Git is an essential tool for file tracking, commit management, and repository maintenance. It allows teams to monitor updates, capture project changes with meaningful commits, and keep the repository organized through proper branch and merge practices. By following structured Git workflows, developers can reduce errors, improve teamwork, and maintain a clear history of project development.

The combination of file tracking, well-managed commits, and regular repository maintenance ensures that software projects remain stable, scalable, and easy to manage. A disciplined use of Git practices supports efficient collaboration and lays the foundation for successful long-term project development.

### File Details
- File Name: ABC001
- New File Name: ABC002

### Branches Used
- Cricket
- Football
- Basketball
