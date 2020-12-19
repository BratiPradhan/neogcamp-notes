# GIT WORK FLOW

You can have any kind of git work flow

One which is useful for small teams is centralized workflow

- you have a origin branch: master/main
- then you have a specific branch for each member
- you first initialize your github repository
- then your teammates will clone it to there local machine with a seperate branch 
- then can do all the commits locally to their git repository
- if A member has pushed with (git push origin master) and B tries to push it, it will show error, because B member is not upto date to the origin branch
- before pushing it to the master, B member has to do **git pull --rebase orgin master**
- rebase is better way, because it will match every commit, if you have conflict in commit , it will show the conflict then and there
- you can see it with **git status**, your conflict files will be under "Unmerged paths: "
- then you can edit your file and say **git add git rebase --continue**
- now you can do **git push origin master"
- merging this way is better, so merge conflicts can be solved easily, rather than merging with one go with "git merge"





There are many more workflow, for large projects, you have distributed workflow, for one feature one branch, and everyone working under that repository
This is a better way to keep your master repository away from bugs and errors.
