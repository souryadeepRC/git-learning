# git-learning
Git learning repo

### CASE - 1 :: Parent branch
------------------------
    1.  Create a parent branch from develop
    2.  User-1 made some commits in parent branch and push
    3.  User-2 made some commits in that branch and push
    4.  User-1 take pull and add again commits and push
    5.  USer-2 will add some commit


## NOTE:
git push origin --delete GLC-1-merge-conflict-issue


when ^1 4v

do git pull --rebase

git push --force-with-lease

git reflog
cat ~/.bash_history | grep git

How to Use `git stash list`
------------------------

 __1. Show the List of Stashes:__
    
    git stash list 
    
    stash@{0}: WIP on main: 1234567 Commit message
    stash@{1}: WIP on feature-branch: 89abcde Another commit message

 __2.  View Detailed Information About a Specific Stash:__
    
    git stash show stash@{n}

_By default, this command shows a summary of the changes. To see a more detailed diff of the stash, use the -p (or --patch) option:_

    git stash show -p stash@{0}


 __3.  Apply a Stash:__

    git stash apply stash@{n}

 __4.  Drop a Stash:__
    
    git stash drop stash@{n}

  __5.  Clear All Stashes:__

    git stash clear


