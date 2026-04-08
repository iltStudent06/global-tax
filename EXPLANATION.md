The branching strategy you used and why:
I created a dedicated branch for each feature or enhancement to keep work isolated and prevent unfinished changes from impacting the main branch. Only changes that have been tested and reviewed are merged into main, ensuring the main branch remains stable and always ready for production deployment.

Your commit philosophy (how you decided what constitutes a single commit):
I used atomic commits, where each commit represents one logical change. This keeps the history easy to follow and makes it simpler for reviewers to understand the implementation and for the team to identify or revert specific changes if needed.

How you would improve this repository for a production environment:
To improve this repository for a production environment, I would standardize commit messages to include the related Jira ticket number so changes are easily traceable back to requirements and discussions. I would also enable branch protection rules on main to require pull requests and 1–2 approvals before merging. Finally, I would add a rollback strategy such as versioned releases so we can quickly redeploy a previous stable version if issues are found after release.
