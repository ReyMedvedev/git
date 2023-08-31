Clone a remote repository to your local machine<br>
`git clone <repository_url>`

Pull changes from a remote repository and merge into the current branch<br>
`git pull origin <branch_name>`

Push local commits to a remote repository<br>
`git push origin <branch_name>`

List local branches and show the active branch<br>
`git branch`

Switch to a different branch or commit<br>
`git checkout <branch_name/commit_hash>`

Stage changes for commit<br>
`git add <file_name>`

Commit staged changes with a message<br>
`git commit -m "Your commit message here"`

Check status of working directory and staged changes<br>
`git status`

Display commit history<br>
`git log`

Merge changes from one branch into another<br>
`git merge <branch_name>`

Reapply commits from one branch onto another<br>
`git rebase <base_branch>`

List remote repositories connected to your local repository<br>
`git remote -v`

Fetch changes from a remote repository without merging<br>
`git fetch origin`

Unstage changes or move HEAD to a specific commit<br>
`git reset <file_name/commit_hash>`

Create and manage tags to mark specific points in history<br>
`git tag -a <tag_name> -m "Tag message"`

Temporarily save changes that are not ready to be committed<br>
`git stash`

Add a new remote repository<br>
`git remote add <remote_name> <repository_url>`

Remove a remote repository<br>
`git remote remove <remote_name>`

Configure Git settings (username and email)<br>
`git config --global user.name "Your Name"`
`git config --global user.email "your@email.com"`

Search for specific text in files<br>
`git grep "search_text"`
