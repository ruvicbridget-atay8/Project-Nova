# Part 2: Git Troubleshooting Practice
## Overview: This exercise addresses 10 Git troubleshooting scenarios utilizing the Project-Nova repository.
## Problems and Solutions
### 1. The "Oops, wrong file" Problem
**Solution:** Used git restore --staged .env to unstage the file without deleting it.
### 2. The "Typo in the message" Problem
**Solution:** Used git commit --amend -m "Fixed authentication practice typo" to correct the commit message.
### 3. The "Forgot a file" Problem
**Solution:** Added styles-practice.css and used git commit --amend --no-edit.
### 4. The "I hate these changes" Problem
**Solution:** Practiced creating and removing a temporary file to understand file restoration.
### 5. The "Wrong Branch" Problem
**Solution:** Practiced git reset HEAD~3 --hard while preserving the commits on another branch.
### 6. The "Detached HEAD" Problem
**Solution:** Created recovery-branch using git switch -c recovery-branch.
### 7. The "Undo a pushed mistake" Problem
**Solution:** Used git revert to undo a previous commit.
### 8. The "Accidental Deletion" Problem
**Solution:** Created recovered-practice to point to an earlier commit.
### 9. The "Ghost Files" Problem
**Solution:** Used git status to identify the staged deletion of delete-practice.txt.
### 10. The "Pushed to the void" Problem
**Solution:** Created and then deleted the practice remote branch testing-junk.
## Conclusion: This activity helped me practice Git troubleshooting, commit correction, file management, commit recovery, and branch management.
