## git

* create a branch for each feature
* check `git diff` before each commit
* squash commits into one before merging branch
* rebase branch with `main` before asking review
* merge branch after approval
* delete branch after merge

## GitHub

* [use actions for CI](https://github.com/features/actions)
* [automatically delete head branches](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/configuring-pull-request-merges/managing-the-automatic-deletion-of-branches)
* [set default branch](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/changing-the-default-branch) if it differs from `main`

## Anti-patterns

* push forces to the `main` forbidden, revert changes from `main` with `git revert`
