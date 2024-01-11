# Steps to do Git Merge
1. `git checkout -b <branch_name>` - Create and checkout branch
2. `echo "Some content at $(date)"` - Introduce a change to readme file
3. `git add <filename>` - Stage the changes
4. `git commit -m "<commit_message>"` - Commit changes into branch
5. `git checkout main` - Switch to main branch
6. `git merge <branch_name>` - Merge changes from feature branch into main
