# Git-it
# https://github.com/jlord/git-it-electron

Challenges
1.
git --version
git config --global <PROPERTY: user.name> "Your Name"
git config --global <PROPERTY: user.name>
git config --global <PROPERTY: user.email> "youremail@example.com"
git config --global <PROPERTY: user.email>

2.
git init
git status

3.
git add <FILE: readme.txt>
git commit -m <MESSAGE: "Created readme">
git diff
git add .

4.
git config --global <PROPERTY: user.username> <USerNamE>
git config --global <PROPERTY: user.username>

5.
git remote add <REMOTE_NAME: origin> <URL>
git remote set-url <REMOTE_NAME: origin> <URL>
git pull <REMOTE_NAME: origin> <BRANCH_NAME: master>
git remote -v
git push <REMOTE_NAME: origin> <BRANCH_NAME: master>

6.
git clone <URL_FROM_GITHUB>
git remote add <REMOTE_NAME: upstream> <URL>
git remote set-url <REMOTE_NAME: upstream> <URL>

7.
git branch <BRANCH_NAME: add-th-santos>
git checkout <BRANCH_NAME: add-th-santos>
git add -A
git branch -m <NEW_BRANCH_NAME>
git checkout -b <BRANCH_NAME: add-th-santos>
git branch

8.

9.
git fetch --dry-run

10.

11.
git merge <BRANCH_NAME: add-th-santos>
git branch -d <BRANCH_NAME: add-th-santos>
git push <REMOTE_NAME: origin> --delete <BRANCHNAME: add-th-santos>
git pull <REMOTE_NAME: upstream> <BRANCH_NAME: gh-pages>

* useful commands
git log
git reset --hard

* tips
git add -A  |   stages All
git add .   |   stages new and modified, without deleted
git add -u  |   stages modified and deleted, without new
git add -A  |   is equivalent to git add .; git add -u
