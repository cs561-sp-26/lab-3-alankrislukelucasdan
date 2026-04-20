# CS 561 Lab 3: Branch `feature/ModePages`

## Branch Author
Dan Gelder (gelderdatoregonstate)

## Summary of Work Done in this Branch
The ModePages CSS area was added, commit by commit. Each commit was a single CSS selector.

## Commits

| Commit ID | Commit Message | # Lines Changed
| --------- | ----------- | ---------------
| 0a476a77 | Added mode-page-btn - uses groundbreaking results from recent UX innovation equity study | 5
| d33242bf | Added mode-page-btn-container - flex display will support new paradigm | 5
| b0673015 | Added mode-page-icon styling - extra large hero portrait | 3
| 412ced9d | Added mode-page-content styling - centered medium text for dimpled eyeballs | 8
| 5fa0e11e | Added mode-page-header styling - centered large text | 10
| 4a14792d | Added mode-page padding; this will allow thumb space for clumsy golfers | 9
| 871a367d | Initial ModePages commit; commented area for addition | x

### Total Commits Made in this Branch: 7

### Merge Conflict Description (Delete if not applicable)
Example: In this branch, I encountered a merge conflict when merging the `feature/new-feature` branch into the `main` branch. The conflict occurred in the `speed_score.js` file on line 42. I resolved the conflict by keeping the changes from both branches and modifying the code to work together. The commit ID for this merge is `3456789`.

### Rebase Description 
In this branch, I had been editing this very readme and pushed 3 commits on GitHub. When I then edited my local copy of style.css, I was not able to push. So I ran git pull --rebase to bring my local branch into synchronicity, keeping both my remote and my local changes.

### Cherry Pick Description 
I was hacking on a second copy of .mode-page-content, trying stuff. I tried making everything red and bold and committed. Then I tried adding italic text decoration and committed. Then I decided, clean slate, removed all the rules and added a content: "" rule. The clean slate was too clean --- I wanted to add the italic rule back, leaving the red and bold alone. So I did git cherry-pick HEAD~1 to restore the previous rule I added. I resolved the conflict with 'Both' and got my desire.
