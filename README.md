
#  Git Commands
1.  Basic Commands
- `git init` :- to initalize a git repo.
- `git status` :- currnet status of git repo.
- `git add . or file_name` :- move works to staging area.
- `gitcommit -m  "commit message"`
- `Create a .gitignore` :- file and add files/ folders that doesn't need tracking.      

2. Seeing Commands
- `git log` :-see details for all the commits.
- `git log --oneline` :- 1 liner details for all commits.
- `git log --stat` :- details of changes on commit level.
- `git log -p` :- see code changes on commit leve.
- `git show <sha id> ` :-  see changeson specific commit.
- `git checkout <sha id>` :- used to swich your working repo to the stae of the repo at specific commits.
- `git checkout master` :- to go back to your previous branch.

3. Branching and Merging
- `git branch <name> <sha id>` :- create a new breach.
- `git branch` :- lists all branches.
- `git checkout <branch>` :- switch to another branch.
- `git log --oneline --all` :- see commits of all branches.
- `git log --oneline --all --graph` :- graph of commit for all branches.
- `git branch -d / -D <branch>` :- deletes a branch.
- `git merge <branch>` :- run from master / main.
