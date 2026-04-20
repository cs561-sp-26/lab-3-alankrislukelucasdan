# CS 561 Lab 3: Branch `feature/window`

## Branch Author
Kristofer Soto

## Summary of Work Done in this Branch
Addition of features to enable browser history and state restoration functionality.

## Commits
| Commit ID | Commit Message | # Lines Changed
| --------- | ----------- | ---------------
| a872146 | adding new eventListener for load event to select first tab | 5
| d3cb3ac | adding restoreState function to manage state while navigating between tabs | 24
| 61c4dc5 | adding JSDoc for restoreState | 15
| c441bf2 | fixing bug with pop state event listener | 4

### Total Commits Made in this Branch: 4

## Cherry-pick Description 
Cherry-picked the floating action button CSS styling (#fab403b) since the .float-btn class
is used for the action buttons whose state is managed in the window.js file. 