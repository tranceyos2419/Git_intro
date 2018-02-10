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

#: hash tag of commit

<Move to a prvious commit>
Look at: "git chekout #"
Go back to[current baranch] (master): "git checkout [branch name] (master)"

<going back to a previous commit and restart new commit from there)>
Going back to a previous commit: "git revert --no-commit #..HEAD"
Restart new commit from there: "git commit -m 'go back to #'"


<Branch>
List branch: git branch
Switch branch: git checkout [branch name]
Add new branch: git checkout -b [new branch name]
Merge branch into current branch: git merge [the name of branch I wan to merge]
Remove branch: git branch -d [branch name]

<making a new branch from a previous commit>
Look at: "git chekout #"
Start new history from seeing commit:"git checkout -b {new branch name}"


<Questions>
{How to untrack current tracking files?}
Step 1. Add the folder path to your repo's root .gitignore file.
[path_to_your_folder/]

Step 2. Remove the folder from your local git tracking, but keep it on your disk.
[git rm -r --cached path_to_your_folder/]

Step 3. Push your changes to your git repo.

<GitHub>
[Authentication]
Generate SSH-key with puffy-Gen
Copy ssh-rsa to GitHub
Save public and private keys to somewhere safe

[Add local files to git repository]
Connect github to local folder: git remote add origin https://github.com/tranceyos2419/Git_intro.git
Checkout: git remote -v
Push local files to GitHub: git push -u origin master
