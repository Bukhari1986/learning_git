# Learning Git and GitHub from Codanics Aikachilla 2026

Day 6 thaught us the basics to advanced concepts of Git and GitHub. Below is a summary of what we learned:

> ## summary how to use git

1. create a directory for your project `mkdir learning_git`
2. navigate to the project directory using git bash `cd learning_git`
3. initialize a git repository in the project directory `git init` 
4. create a file in the project directory `touch readme.md`
5. add the file to the staging area `git add readme.md`
6. check the status of the git repository `git status`
7. issue the commit command to store the file with a message `git commit -m "readme file added, which is empty"`
8. check the status of the git repository `git status`
9. make changes to the file `readme.md`
10. check the status of the git repository `git status`
11. add the file to the staging area `git add readme.md`
12. check the status of the git repository `git status`
13. issue the commit command to store the file with a message `git commit -m "readme updated"`
14. or use `git commit -a -m "message"` to both add and commit changes in one step.
15. check the history of commits made to the git repository `git log`
16. revert back to a previous commit `git checkout <commit_hash>`
17. perform a hard reset `git reset --hard <commit_hash>`
18. perform a soft reset `git reset --soft <commit_hash>`
19. checkout a specific file from a previous commit `git checkout <commit_hash> -- <file_name>`
20. link the local git repository to an online hosting service like github using command as: `git remote add origin http//github.com/your_github_username/learning_git.git`
21. change the local main branch name to match the remote branch name: `git branch -M main`
22. push the local repository to github using the following command: `git push -u origin main`
23. after changes to the file, use the following commands to push the changes to github: `git add readme.md`, then `git commit -m "header corrected and git learning summary added"`, and lastly `git push`
24. this step 23 will push the changes to github.