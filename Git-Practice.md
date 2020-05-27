# Git prictice Scenarios

**Scenarios from 1-6 from this website https://www.katacoda.com/courses/git:**

The Command | It work
-------- | --------
`git init` | create a new repository
`git status` | view which files have changed between your working directory and what's been previously committed to the repository
`git add file|directory` | add changes to the staging area
`git commit -m "<commit message>"` | moves files from staging to the repository and records the time/date, author and a commit message that can be used to add additional context and reasoning to the changes such as a bug report number.
`.gitignore file` | if there are particular files or directories you never want to commit
`git diff` | compare against an older version
`git diff --staged` | To compare the changes in the staging area against the previous commit
`git log` | allows you to view the history of the repository and the commit log.
`git show` | to view the changes made in the commit you need to use the the command.
`git remote add origin` | allow you to share changes from or to your repository. 
`git push origin master` | to push changes to a remote repository
`git pull origin master` | allows you to sync changes from a remote repository into your local version.
`git checkout .` | will replace everything in the working directory to the last committed version.
`git reset` | will move files back from the staging area to the working directory.
`git reset --hard` | will be the files removed from the staging area and the working directory is taken back to the state of the last commit.
`git revert` | allows you to undo the commits
`git fetch` | downloads changes into a separate branch which can be checked out and merge. 
`git checkout -b <new branch name>` | will create and checkout the newly created branch.
`git branch <new branch name> <starting branch>` | takes an existing branch and creates a separate branch to work in. At this point both branches are identical.
`git checkout <new branch name>` | To switch to a branch
`git branch -va` | List all the branches with their last commit message using
`git checkout master` + `git merge new_branch` | Merge the commits in your new branch back into master.
` git push <remote_name> <branch_name> ` | if you want to push a branch to a remote
`git branch -d <branch_name>` | Cleaning up branches.
