Git Notes — Essential Commands

1. git init

Initializes a new Git repository.
Example: "git init"

2. git clone

Downloads a remote repository.
Example: "git clone https://github.com/USERNAME/REPO.git"

3. git status

Shows changed, staged, and untracked files.
Example: "git status"

4. git add

Stages files for the next commit.
Example: "git add README.md"

5. git commit

Records staged changes in the repository history.
Example: "git commit -m "Add project README""

6. git log

Displays commit history.
Example: "git log --oneline"

7. git diff

Shows unstaged changes.
Example: "git diff"

8. git push

Uploads local commits to a remote repository.
Example: "git push -u origin feature/git-notes"

9. git pull

Fetches and integrates changes from a remote branch.
Example: "git pull origin main"

10. git fetch

Downloads remote updates without integrating them into the current branch.
Example: "git fetch origin"

Additional Useful Commands

git branch

Lists local branches.
Example: "git branch"

git switch -c

Creates and switches to a new branch.
Example: "git switch -c feature/git-notes"

git remote -v

Shows configured remote repositories.
Example: "git remote -v"

git diff --staged

Shows changes staged for commit.
Example: "git diff --staged"

git merge

Integrates another branch into the current branch.
Example: "git merge feature/git-notes"

Typical Workflow

1. Check changes using "git status".
2. Stage files using "git add".
3. Review using "git diff --staged".
4. Commit using "git commit".
5. Upload using "git push".
