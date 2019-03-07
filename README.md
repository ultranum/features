# Git Features - Branch, Checkout, Merge, Resolve

## Branch a repo
Branching a git project allows you to have a seperate version of the same project so that you can develop without fear of damaging the main project (ie adding new feature)

Changes made on a new branch are not made to master branch

## Checkout a branch

To switch branches on the local machine, the branch must be checked out. (In terminal, it is 'git checkout branchname'). Branches must be committed and pushed separately to the git repository.

Oftentimes, local branches are not synced to the git repository until the developer is confident that the branch may be implemented.

##Merging a branch into another

Once the branched version is ready to be implemented into another branch. (Often the master, but it could be another branch). The branch can be merged into a parent branch. The current checked out version is the branch that is being merged into.

## Resolving a conflict

When two different versions of the same file are merged, (There are committed changes to the same file in different branches). Those conflicts must be resolved. Most IDEs have an in-built tool to resolve conflict, but it can be done at the source code level as well.

Note: The branch cannot make any further commits until all conflicts are resolved.