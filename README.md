# CarpentryCon 2022: Skill-up: Beyond the SWC Git Lesson: Skills for Maintainers

Etherpad: https://pad.carpentries.org/cc2022-beyond-SWC-git-lesson

- You can potentially use "conventional commits"
  - https://www.conventionalcommits.org/en/v1.0.0/

- create an alias for `git log`
  - `git config --global alias.l 'log --oneline --graph --all'`

- `git switch -c <NAME>`:
  1. Create a branch called <NAME>
  2. Switch to that branch

- All you need to do is update the branch, and the PR will be updated too.

- Cleaing up after PR merge
  - Delete the branch on the remote
  - `git fetch --prune`: update local history
  - `git branch -d <NAME>`: delete the branch <NAME>
    - Note: lower-case d (use -D for force delete)

## Conflicts

Code to simulate a 2 branch conflict

```bash
git switch -c conflict_branch_1
echo "Changes to b1 commit 1" >> README.md
git status
git add README.md
git commit -m "b1 c1"
echo "Changes to b1 commit 2" >> README.md
git add README.md
git commit -m "b1 c2"

git switch main

git switch -c conflict_branch_2
echo "Changes to b2 commit 1" >> README.md
git add README.md
git commit -m "b2 c1"
echo "Changes to b2 commit 2" >> README.md
git add README.md
git commit -m "b2 c2"

git push origin conflict_branch_2
git push origin conflict_branch_1
```

## Rebaseing

1. `git fetch --prune`: update all your history stuff
2. update the branch you want to rebase against (usually `main`) using `git pull`
3. go to your branch with the conflict (or the one you want to rebase)
4. `git rebase main`: to update your branch with the new stuff from `main`
   1. fix conflicts as needed.
   2. follow the instructions from the git output.
   3. Usually, you fix up the `<<< === >>>` stuff
   4. `git add FILE`
   5. `git rebase --continue`
5. force update your remote branch: `git push --force-with-leases origin BRANCH`
6. you should be able to merge the branch now

## Text from rebaseing example

Changes to b1 commit 1
Changes to b1 commit 2
Changes to b2 commit 1
Changes to b2 commit 2
Changes to b1 commit 1
Changes to b1 commit 2
Changes to b2 commit 1
Changes to b2 commit 2
Changes to b2 commit 3

## Interactive rebase

1. go to your branch  you want to squash everything down
2. `git log --oneline --all`: know how many commits you want to squash down to
3. `git rebase -i HEAD~5`: where 5 is the number of commits (you can also pick the last commit)
4. follow instructions from the text editor
   1. to squash: replace the `pick` with `s`
   2. it will create a new commit
5. `git log --oneline`: eventuall you will have everything in 1 commit

## Branch protection stuff

Branch protection rules force you to practice collaboration on your own

```
git log --oneline --graph --all
git reset --hard <HASH>: force move current branch to location
```
