# git_practice
Practicing Command

1. `git init`
  a. created a git repository at local
2. `git remote add origin https://github.com/jay2202/git_practice.git`
3. `git add .`
4. `git commit -m "initial commit"`
5. `git checkout -b 'brach name'`
   a. create a new branch
6. `git checkout master`
7. `git merge 'branch name'`
   a. merge `branch name` to `master`
   b. any conflict happen then you have to resolve conflict then merge
   c. now push.
8. `git clone -b master https://github.com/jay2202/git_practice.git` clones your repo to another remote system
9.  `git tag 'tag name'` 
    a. `git push --tags` push your tag to remote repo 
    b. normal push dont push tags to remote
10. before pushing clonned repo, first use command `git pull`, otherwise conflicts happen.
