This is my My First exercise to push the local repository github

Git Stash:
git stash is used to temporarily save your uncommitted changes so you can work on something else without committing incomplete work.
It is especially useful when a developer is working on one feature but suddenly needs to switch to another branch to fix an urgent issue.
The important point is:
Git Stash temporarily stores your uncommitted changes and gives you a clean working directory.



Git Cherry-Pick:

Copy of specific commits from one branch to another branch.

Suppose you have 10 feature branches out of it you want to 8 feature branches to main.

So you can create the another promotion branch from the main in that branches we have to include the only 8 branches changes.

git checkout feature/US-0001 main (creating new branch from main)

Git cherry-pick <Commit-Id-1>  <Commit-Id-2>  …. <Commit-Id-8>

Git checkout main (swtich to main)

Git merge feature/US-0001. (mereging the new feature branch into main)

