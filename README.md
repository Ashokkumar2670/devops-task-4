# DevOps Internship - Task 4: Build a Version-Controlled DevOps Project with Git

## Objective
Manage a DevOps project using Git best practices, branching strategies, tagging, and repository management.

## Deliverables & Workflows Completed
- **Repository Initialized:** Created local repository and linked with GitHub.
- **Branching Strategy:** Created `main`, `dev`, and `feature/login-page` branches.
- **Pull Requests (PR):** 
  - Merged `feature/login-page` into `dev`.
  - Merged `dev` into `main`.
- **Git Tags:** Created and pushed tag `v1.0.0` for version release.
- **Gitignore:** Configured `.gitignore` to exclude log files and sensitive data.

## Interview Questions & Answers

1. **What is Git?**
   - Git is a Distributed Version Control System (DVCS) used to track code changes, collaborate with developers, and manage source code history.

2. **What is the difference between merge and rebase?**
   - **Merge:** Combines two branches by creating a new merge commit, preserving complete history.
   - **Rebase:** Re-applies commits on top of another base tip, creating a linear history.

3. **What is a pull request?**
   - A event where a developer notifies team members that they have completed a feature and requests code review to merge into the target branch.

4. **How do you resolve merge conflicts?**
   - Identify conflicting files, manually edit to select correct changes between `<<<<<<<` and `>>>>>>>`, stage the file using `git add`, and finalize with `git commit`.

5. **What are Git tags?**
   - References pointing to specific commits in Git history, primarily used to mark release versions (e.g., `v1.0.0`).

6. **What is Git workflow?**
   - A set of guidelines or branching strategies (like Git Flow or GitHub Flow) that define how developers collaborate using Git.

7. **Explain git stash.**
   - `git stash` temporarily stores modified, uncommitted work so developers can switch branches without committing incomplete changes.

8. **What is the use of .gitignore?**
   - A text file specifying untracked files/folders (such as build outputs, temporary files, secrets) that Git should ignore.
