## Git Branches notes

##### _What is a branch?_

##### A branch creates a working repo that "branches" from the main repo in order that we may work on a feature without directly editing main.

##### _The branch workflow_

1. Create a branch with the following command: git switch -c <"name of branch">
2. Switch to the branch using the following command: git switch <"name of branch">
3. Commit changes to code as normally using git commit -m
4. When you are ready to push the code onto github use the following command: git push -u origin <"name of branch"> .. (n.b the "-u" is only necessary for the initial push to github. thereafter may use "git push")
5. You may push and pull to and from this branch on github until you are ready to merge the changes to main. To pull from the branch use the following command: git pull
6. To merge the branch to main you must approve the pull request generated on github by your initial push. To do this you must share the pull request with your teme and review the changes.
7. To pull the updated main repo into your local git use "git pull origin main".
