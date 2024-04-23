# Tips for git

## Repos

git remote add origin https://github.com/adriandbc/demo-repo2.git --> Connect local repo with remote repo (empty repo)
git remote -v --> Shows URLs of remote repositories when listing your current remote connections
git remove <repo-name> --> Disconnects the remote from the local repository

## Branch
git branch -r --> Lists all the remote branches

## Commits
git reset --hard 7d544a1b0ca6ca5515aae6750905494df82e0c29 --> Reset your local or remote to a Commit (hash)

## Push
git push -f origin main --> to force a git push
