EXPERIMENT 1
git clone repolink 
cd reponame 
code . 
gitadd .
git commit -m "message" 
git push

EXPERIMENT 2
git branch feature-branch
git checkout feature-branch
git add .
git commit -m "message"
git checkout main
git merge feature-branch
(make changes)
git stash
git checkout feature-branch
git stash apply

EXPERIMENT 3
git clone repolink
git branch -v
git checkout -b feature-branch
git branch -v
git fetch origin
git add .
git commit -m "message"
git rebase origin
git checkout main
git merge --no-ff  feature-branch -m ”message”

EXPERIMENT 4
git add .
git commit -m "message"
git push
git log  —oneline 
git tag  v1.0 (commit id) 
git tag
git push origin v1.0

EXPERIMENT 5
git add .
git commit -m "message"
git push
git branch feature-branch
git add .
git commit
git status
git log --oneline 
git checkout feature-branch 
git cherry-pick id

EXPERIMENT 6
git log --oneline 
git show (commit id)
//open new terminal //
git log --author=" " --after="(//yesterday date//) "    --before="(//tmr date//)"
git log -n 5
git revert (“first id”)
