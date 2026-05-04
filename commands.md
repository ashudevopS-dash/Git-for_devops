1. Repository Setup
Initialize repo → git init
Clone repo → git clone <repo_url>
2. Check Status & History
Check changes → git status
View commits → git log
Short log → git log --oneline
3. Add & Commit
Add one file → git add filename
Add all files → git add .
Commit → git commit -m "message"
4. Branching
Create branch → git branch branch_name
Switch branch → git checkout branch_name or git switch branch_name
Create + switch → git checkout -b branch_name
5. Merge
Merge branch → git merge branch_name
6. Remote (GitHub)
Add remote → git remote add origin <repo_url>
Push → git push origin branch_name
Pull → git pull origin branch_name
Fetch → git fetch
7. Undo Mistakes
Unstage file → git reset filename
Undo last commit (keep changes) → git reset --soft HEAD~1
Undo last commit (delete changes) → git reset --hard HEAD~1
8. Compare Changes
See changes → git diff
See staged changes → git diff --staged
9. Stash (Temporary Save)
Save work → git stash
Apply stash → git stash apply
10. Ignore Files
Stop tracking file → git rm --cached filename
