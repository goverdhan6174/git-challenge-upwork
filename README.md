# Git Challenge
There are two branches, `add-echo` and `add-reverse`. The goal of this challenge is to use `git rebase` to bring both commits onto master. When finished there should be no merge commits or branching. Without forking.

## Completed
How I attempt this challenge:
1) Clone the repo https://github.com/Interlincx/challenge-git.git
2) create the local branches of add-echo and add-reverse {git checkout origin/<branch-name>}
3) first checkout to add-echo branch and rebase to master and merger it. (First merge the add-echo because "add echo route" commit was below the "add reverse route" commit).
4) repeat step 3 on add-reverse branch and result in conflict at test/routes.js lib/server.js lib/api.js (resolve the conflict by accepting both changes but at routes.js rearrange the few lines to resolve it)
5: git remote set-url origin `https://github.com/goverdhan6174/git-challenge-upwork.git`and the push to origin

