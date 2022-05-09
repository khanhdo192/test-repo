git init - Turn an existing directory into a git repository

git remote add origin [url] - Set a new remote

git add . - add all file change

git add -u - add file except untracked file

git commit -m "message' - create commit

git push origin [branch-name] - Pushes branch to the origin

git push origin --delete [remoteBranchName] - Delete branch remotely

git clone [url] - Clone (download) a repository that already exists on Github

git branch [branch-name] - Creates a new branch

git checkout [branch-name] - Switches to the specified branch and updates the working directory

git branch -d [branch-name] - Delete branch locally

git branch -m [new-branch-name] - Rename the current branch

git fetch - Downloads all history from the remote tracking branches

git merge [branch] - Combines the specified branch’s history into the current branch

git pull - Updates your current local working branch with all new commits from the corresponding remote branch

git stash - save current change

git stash save "message" - save current change with message

git stash list - show all stash

git stash apply "stash@{index}" - apply stash u want to code

git stash pop "srash@{index}" - apply and delete stash in stash list

git stash show - show stash diff

git stash branch [branch-name] "stash@{index}" - create new branch with stash u want and delete stash in list

git stash drop "stash@{index}" - delete stash u want

git stash clear - delete all stash

git rebase [branch-name] - apply all commit to branch

git rebase -i - open interactive rebase

git show - output metadata and content changes of the specified commit

git diff - show content differences between two branches

git log - show history activity

rm -rf .git - delete local repo

.gitignore - exclude files from being tracked with Git
