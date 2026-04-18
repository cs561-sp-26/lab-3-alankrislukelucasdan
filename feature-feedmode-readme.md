# CS 561 Lab 3: Branch `feature/feedmode`

## Branch Author
Alan Wallace (wallalan@oregonstate.edu)

## Summary of Work Done in this Branch
Addition of a new tab/panel to the application which will allow for the user to submit social media feed posts

## Commits

| Commit ID | Commit Message | # Lines Changed
| --------- | ----------- | ---------------
| f5108f4 | Added dialog for adding a new post to the feed | 18
| 7558f63 | Added Feed mode tab to display the feed content when the Feed button is clicked | 13
| d34dc01 | Added button for feedMode to reference the panel that will be created | 8
| 1d652a3 | Adding global css focus and button styles in order to make my buttons and focus behaviors look better. | 14

### Total Commits Made in this Branch: 4

### Merge Conflict Description
I encountered a rebase merge conflict when pulling a new version of `main`, which then attempted to replay my modified version of `main` on top of it with code merged from the `feature/feedmode` branch into the `main` branch.  The conflict occurred in `index.html` on line 51.  I resolved the conflict by combining both branches and placing my code at the appropriate location in the incoming file.  The commit ID for this is `9d680d4`.

### Rebase Description 
I rebased an early version of the `feature/feedmode` branch onto `main` branch commit `9c95d37` in order to have the latest version for publishing some CSS style updates that could be used by others.  Commit `1d652a3` was then merged to main.

When pulling the latest before merging, I also I encountered a rebase merge conflict when pulling a new version of `main`, which then attempted to replay my modified version of `main` on top of it with code merged from the `feature/feedmode` branch into the `main` branch.  The conflict occurred in `index.html` on line 51.  I resolved the conflict by combining both branches and placing my code at the appropriate location in the incoming file.  The commit ID for this is `9d680d4`.
