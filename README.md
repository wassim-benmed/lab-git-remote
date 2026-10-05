# Lab 3: Working with Git remote repositories

**Student:** Wassim Ben Mohamed
**Course:** DevOps

## Repositories
- Lab repo: https://github.com/wassim-benmed/test-demo
- Report repo: https://github.com/wassim-benmed/lab-git-remote

## Stages completed
1. **GitHub repo creation**: created `test-demo` with a README, edited it from the web UI, cloned it.
2. **Remotes**: `git remote`, `git remote -v`, `git remote show origin`.
3. **Fetch / pull**: second clone built manually in `fetch-test` with `git init`, `git remote add origin`, `git fetch`, `git pull`.
4. **Push**: local README change committed and pushed to `main`.
5. **Remote branch**: created `feature-1` locally and pushed it with `git push origin feature-1`.
6. **Pull Request**: introduced an error on `main`, fixed it on branch `fix-typo`, opened PR #1, merged it, then ran `git pull origin main`.

> Note: I worked alone, so the PR was made between two branches of the same repository, without a fork.

## Proof
- `git-log.txt`: commit graph showing the merge of PR #1
- `git-remote.txt`: configured remotes
- `git-branches.txt`: local and remote branches

## Screenshots
![PR merged](screenshots/pr-merged.png)
