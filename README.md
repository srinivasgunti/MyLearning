Git Tutorial

$git init
- To initialize a repo to git.

$git remote add origin https://github.com/srinivasgunti/MyLearning.git
- git knows where to pull and push your code.

$git branch
-To display all the local branches.

$git push -u origin master
-  -u  : To set which upstream branch on git hub do you want later pushes and pulls.
-  From later point you can just use push or pull.
-  Do this step every time you are on new branch.

$ git pull origin master
- Be on the feature branch and do a git pull to get all the changes from master before pushing your chagnes.
- It's effectively doing git fetch origin, git merge origin/master.
