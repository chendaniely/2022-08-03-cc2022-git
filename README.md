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

Changes to b1 commit 1
Changes to b1 commit 2
Changes to b2 commit 1
