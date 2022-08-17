## 1) Create 4 commits into master branch with minor changes in file that is already exist.
## 2) Execute command “git reset --hard HEAD~4”
## 3) Are you able to restore changes of third commit? Describe your steps how to do that.
Yes, i can restore changes. I used 'git reflog', found my commit(hash). Then I make merge with branch 'main' my lost commit.