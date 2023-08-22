``
git remote prune origin
``

To delete all local branches that are already merged into the currently checked out branch:  
``
git branch --merged | egrep -v "(^\*|master|main|dev)" | xargs git branch -d
``
