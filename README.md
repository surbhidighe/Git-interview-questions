## Git-interview-questions

### :writing_hand: ----- In Progress ----- :writing_hand:

| S.No  | Questions |
| ------------- | ------------- |
| 1 | [What is Git](#1-what-is-git)  |
| 2 | [What is a repository in git](#2-what-is-a-repository-in-git)  |
| 3 | [What is the difference between Git and GitHub](#3-what-is-the-difference-between-git-and-github)  |
| 4 | [What is the purpose of git clone command](#4-what-is-the-purpose-of-git-clone-command)  |
| 5 | [Which command initializes an empty Git repository](#5-which-command-initializes-an-empty-git-repository)  |
| 6 | [What is a branch in Git](#6-what-is-a-branch-in-git)  |
| 7 | [How can we create a new branch in git](#7-how-can-we-create-a-new-branch-in-git)  |
| 8 | [How to switch branch on git](#8-how-to-switch-branch-on-git)  |
| 9 | [How can you delete a branch both locally and remotely](#9-how-can-you-delete-a-branch-both-locally-and-remotely)  |
---

### 1. What is Git
- Git is a free and open-source distributed version control system designed to manage source code and other file revisions. 
- Using Git, programmers have the ability to track changes made to their codebase over time, collaborate with other team members, and restore previous versions of their work when needed.

**[:top: Scroll to Top](#git-interview-questions)**

### 2. What is a repository in git
A git repository is a central location where all the files and directories for a project are stored, along with their complete version history. 

**[:top: Scroll to Top](#git-interview-questions)**

### 3. What is the difference between Git and GitHub
**Git** - Git is a distributed version control system that allows developers to manage and track changes to their codebase

**GitHub** - GitHub is a web-based platform that provides hosting for git repositories and also offers a range of collaboration tools.

**[:top: Scroll to Top](#git-interview-questions)**

### 4. What is the purpose of git clone command
The git clone command enables you to create a local copy of a remote repository.
```bash
git clone REPO_URL
----------------------
git clone https://github.com/surbhidighe/Git-interview-questions.git
```
**[:top: Scroll to Top](#git-interview-questions)**

### 5. Which command initializes an empty Git repository
'git init' command is used to initialize an empty git repository

**[:top: Scroll to Top](#git-interview-questions)**

### 6. What is a branch in Git
- A branch is a lightweight movable pointer to a commit
- It provides a way for developers to work on different parts of a project without affecting each other's work
- It helps to keep the codebase organized and reduces the risk of conflicts between changes made by different people.

**[:top: Scroll to Top](#git-interview-questions)**

### 7. How can we create a new branch in git
We can use below command to create a new branch - 
```bash
git branch <BRANCH_NAME>
```
**[:top: Scroll to Top](#git-interview-questions)**

### 8. How to switch branch on git
If you want to switch to an existing branch, you can use 'git checkout' command and pass the name of the branch you want to switch to.
```bash
git checkout feature

output - Switched to branch 'feature'
```
If you want to switch to a non-existing branch, you will need to use the -b option. It will first create a new branch and then switch to that branch.
```bash
git checkout -b bug-fixes

output - Switched to a new branch 'bug-fixes'
```
**[:top: Scroll to Top](#git-interview-questions)**

### 9. How can you delete a branch both locally and remotely
Git won't let you delete the branch you're currently on, so you'll need to switch to another branch before deleting the one you want to delete.
```bash
########### DELETE A BRANCH LOCALLY ###########

git branch -d <BRANCH_NAME>

########### DELETE A BRANCH REMOTELY ###########

git push <remote_name> --delete <BRANCH_NAME>

              OR
              
git push <remote_name> :<BRANCH_NAME>
```

**[:top: Scroll to Top](#git-interview-questions)**



