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

<Questions>
How to untrack current tracking files?

<Branch>
List branch: git branch
Switch branch: git checkout [branch name]
Add new branch: git checkout -b [new branch name]
Merge branch into current branch: git merge [the name of branch I wan to merge]
Remove branch: git branch -d [branch name]


#: hash tag of commit

<Move to a prvious commit>
Look at: "git chekout #"
Go back to[current baranch] (master): "git checkout [branch name] (master)"

<making a new branch from a previous commit>
Look at: "git chekout #"
Start new history from seeing commit:"git checkout -b {new branch name}"


<going back to a previous commit and restart new commit from there)
Going back to a previous commit: "git revert --no-commit #..HEAD"
Restart new commit from there: "git commit -m 'go back to #'"
