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

### Rebase Description 
In this branch, I had been editing this very readme and pushed 3 commits on GitHub. When I then edited my local copy of style.css, I was not able to push. So I ran git pull --rebase to bring my local branch into synchronicity, keeping both my remote and my local changes.

### Cherry Pick Description 
I was hacking on a second copy of .mode-page-content, trying stuff. I tried making everything red and bold and committed. Then I tried adding italic text decoration and committed. Then I decided, clean slate, removed all the rules and added a content: "" rule. The clean slate was too clean --- I wanted to add the italic rule back, leaving the red and bold alone. So I did git cherry-pick HEAD~1 to restore the previous rule I added. I resolved the conflict with 'Both' and got my desire.

### Merge Conflict Description
After the previous cherry pick success, it was time to push. However, I had been documenting my work in this very readme and saving the changes -- that was a commit under the rules of Github, and my local 'git push' complained the remote contained work I did not have locally. Now, it would be somewhat reasonable to explain there and then which specific files were different, but that is not why this edifice exists, so I must feel my way through. I tried 'git status', 'git fetch', and then 'git merge origin/ModePages', a mistaken command, but it told me "You have not concluded your cherry-pick (CHERRY_PICK_HEAD exists)." I did not realize you have to conclude a cherry-pick, so I committed and then did git push. 
