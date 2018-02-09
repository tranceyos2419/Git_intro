git init
git status
git add
git commit
git reset HEAD 

git log
git checkout
git revert

git chekout #
git checkout master


<Look at a prvious commit>
git chekout # (look at)
git checkout [branch name] (go back to [current baranch] (master))

<making a new history from a previous commit>
git chekout # (look at)
git checkout -b {new branch name} (Start new history from seeing commit)


<going back to a previous commit and restart new history from there)
git revert --no-commit #..HEAD
git commit -m 'go back to #'
