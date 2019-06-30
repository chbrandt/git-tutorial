# Git basics

* workflow
  * clone / init
  * add
  * push
  * fetch
  * pull
  * checkout

A typical workflow in your repository goes like:
1. `git pull` a fresh version from the remote repository;
2. `git branch` a new branch to make your changes;
3. `git checkout` to the new branch;
4. modify one of more files, maybe add/delete some too;
5. `git add` modified/new files;
6. `git commit` what's in the _index_;
7. `git checkout` back to the _master_ branch;
8. `git merge` the "new branch" into master;
9. `git push` back to the _origin_ (remote repo);
10. `git branch --delete` the "new branch".

And that is basically it!

This is a basic though complete and safe workflow. Steps `2, 3, 7, 8, 10` are
not necessary if you don't mind editing the `master` branch directly -- and
you will most probably do that if you don't share your repository -- but I'm
giving you here some (just _some_) guidance to a better experience.


## Everyday commands

* `git-init`
* `git-clone`
* `git-log`
* `git checkout`
* `git-branch`
* `git-add`
* `git-diff`
* `git-status`
* `git-commit`
* `git-reset`
* `git-merge`
* `git-rebase`
* `git-tag`
