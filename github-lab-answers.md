1) git init
2) git add -A
3) git commit 

1) git pull origin master
2) git rm
3) git revert (commit code)
4) so you can remove any additional changes after the commit 
5) if you made a change that broke your code and you want to revert to a working version.

1) git branch
2) git checkout <name>
3) to make and then test changes that aren't on the master or "production" branch.

1) you would use git merge if you have two branches with unique commits, and want to merge them into one branch (such as the master branch).
2)git push -u origin master