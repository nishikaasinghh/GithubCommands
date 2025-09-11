# GithubCommands

🔹 Setup & Configuration

1. git --version # Check Git version
2. git config --global user.name "Your Name" # Set your Git username
3. git config --global user.email "you@example.com" # Set your Git email
4. git config --list # Show Git configuration
5. git help <command> # Show help for a command

🔹 Starting a Repository 
6. git init # Initialize a new Git repository 
7. git clone <url> # Clone a repository from GitHub 
8. git remote add origin <url> # Connect local repo to remote 
9. git remote -v # List remote connections 
10. git status # Check repo status

🔹 Basic File Operations 
11. git add <file> # Add a file to staging 
12. git add . # Add all files to staging 
13. git reset <file> # Unstage a file 
14. git reset --hard # Reset changes (danger: removes changes) 
15. git rm <file> # Remove a file from repo & working dir

🔹 Committing Changes 
16. git commit -m "message" # Commit with a message 
17. git commit -am "message" # Add & commit tracked files 
18. git log # Show commit history 
19. git log --oneline # Compact commit history 
20. git show <commit-id> # Show details of a commit

🔹 Branching 
21. git branch # List branches 
22. git branch <name> # Create new branch 
23. git checkout <name> # Switch to branch 
24. git checkout -b <name> # Create & switch branch 
25. git branch -d <name> # Delete branch

🔹 Merging & Rebasing 
26. git merge <branch> # Merge a branch into current 
27. git rebase <branch> # Reapply commits on top of another branch 
28. git diff # Show file differences 
29. git diff --staged # Show staged differences 
30. git stash # Save uncommitted changes temporarily

🔹 Pushing & Pulling 
31. git push origin <branch> # Push branch to remote 
32. git push -u origin <branch> # Push & set upstream branch 
33. git pull # Fetch & merge from remote 
34. git fetch # Fetch latest changes without merging 
35. git push origin --delete <branch> # Delete remote branch

🔹 Tags & Releases 
36. git tag # List tags 
37. git tag <tagname> # Create a tag 
38. git tag -d <tagname> # Delete a tag 
39. git push origin <tagname> # Push a tag to remote 
40. git push --tags # Push all tags

🔹 Undo & Fix 
41. git checkout -- <file> # Discard changes in file 
42. git revert <commit-id> # Undo a commit (safe) 
43. git reset --soft <commit-id> # Reset but keep changes staged 
44. git reset --hard <commit-id> # Reset & delete changes 
45. git clean -fd # Remove untracked files & dirs

🔹 Collaboration & Info 
46. git blame <file> # Show who last modified each line 
47. git shortlog -s -n # Show commit count per author 
48. git cherry-pick <commit-id> # Apply specific commit 
49. git archive --format=zip HEAD > latest.zip # Export repo as zip 
50. git reflog # Show history of all Git actions
