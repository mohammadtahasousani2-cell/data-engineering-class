\# Activity 2 — Git Workflow



\## Objective

Demonstrate a basic collaborative Git workflow using a feature branch, meaningful commits, and a pull request.



\## Workflow

1\. Start from the `main` branch and update it.

2\. Create a feature branch for the activity.

3\. Add and update project files on the feature branch.

4\. Commit each logical change with a clear message.

5\. Push the feature branch to GitHub.

6\. Open a pull request from the feature branch to `main`.

7\. Review and merge the pull request.



\## Git Commands

```bash

git switch main

git pull origin main

git switch -c feature/chapter-2

git add chapter-2/README.md

git commit -m "docs: add activity 2 git workflow"

git push -u origin feature/chapter-2





