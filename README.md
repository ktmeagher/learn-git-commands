# learn-git-commands
A project that can be used to learn git commands

## git cherry-pick command
git cherry-pick <commit-hash> to cherry-pick a commit from another branch.

git cherry-pick -n <commit-hash> to cherry-pick the commit but it won’t commit the changes. It will only stage all the changes.

git cherry-pick —continue or git cherry-pick —abort when you face conflicts while cherry-picking.

git cherry-pick -m to mention the parent branch number when you are cherry-picking a merge commit.

git cherry-pick A..B to cherry-pick a series of commits.