# Contributing
(WIP)

All work is tracked using Milestones and Issues. Any issue that is unassigned is up for grabs.

1. Claim an Issue (or file a new one).
2. Fork the Repo.
3. Make your changes and update your Fork.
4. Create a Pull Request to submit your change for review.

## Claiming an Issue

1. Assign the issue to yourself
2. Add the "in progress" label
3. Leave a comment indicating you are working on the issue.

## Pull Request Submissions

### Commit Guidelines

* Minimal commits per issue. If the issue requires more than one commit, make sure they are grouped appropriately. I recommend adding checkboxes to the issue for clarification. Please do not submit a change with a lot of one-off commits with vague messages. 
  * If you need help with this, mention it in your PR and I can always rebase it down for you or pair with you to show you how.
* Commit messages should mention the issue and indicate whether they resolve the issue or are related to it.
  * Closes: "Resolves Issue #1" (see Github closes syntax - https://help.github.com/articles/closing-issues-using-keywords/)
  * Part of multiple commits: "Part of Issue #1"
* Only commit code-related files you changed or data archives. Please do not include extra files like ".DS_Store"

### Code Style Guidelines

* Be consistent with existing methods, packages, and naming conventions. Tidyverse is preferred.
* Everything must be reproducible back to the data pull. Do not add a CSV without also including how to get it via code.
* Do not "manually" update the "latest" folder. All files should go into an archive and then a central method should add them to the "latest" folder all at once.
* Do not commit API keys, passwords, or other sensitive information. Use params and environment variables.
