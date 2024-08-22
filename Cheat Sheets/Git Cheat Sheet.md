# Git Cheat Sheet & Useful Facts About Git


Git Commands  | Description
--------------|------------
git init | Create a new Git repository
git config --global user.name "name" | Sets the name you want to attach to your commit transactions 
git config --global user.email "email address" | Sets the email you want to attach to your commit transactions 
git config --global alias.arbitrary_name "command name" | Change the "command name" to arbitrary_name
git config --global core.editor "editor_name" | Set up your editor to "editor_name", e.g., "nano", "vim", etc. 
git add "file_name" | Add the file to staging index
git add . | Add all files from working directory to staging index
git status | List all new or modified files to be committed
git commit -m "message" | Add files from staging index to repository committed by the "message"
git commit --amend -m "new_message" | Change the commit message by using the amend flag
git diff | View difference between staging index and working directory
git diff "SHA1 hash" | Show changes between the working tree and the index or a tree, changes between the index and a tree, changes between two trees, or changes between two files on disk
git diff --staged | View difference between HEAD and staging index
git diff HEAD | View difference between HEAD and working directory
git diff --color--words branch1..branch2 | Show differences between branch1 and branch2 using color fonts
git diff [first-branch]...[second-branch] | show diffrence between 2 branches
git branch "branch_name" | Create a branch whose name is "branch_name"
git branch --m "old_name" "new_name" | Change the old name of the branch to new one 
git branch --d "branch_name" | Delete the branch
git branch | List branches
git branch -m "new" | Rename current branch to "new"
git checkout "branch_name" | Switch to "branch_name"
git checkout -b "branch_name" | Create the branch and switch to this branch
git checkout remotes/origin/"branch_name" | Switch to a remote "branch_name"
git checkout -- "file_name" | Discard changes in the working directory (i.e. replace the file in the working directory with the file in the staging index). Here -- means to stay in the same branch which  confirms that "file_name" is not the name of a branch otherwise it switches to "branch_name"
git checkout "SHA1 hash" -- "filename" | Switch to a specific commit (determined by SHA1 hash). This command is safe and does not overwrite local changes in the working directory. Here HEAD is not detached because of "--".
git merge "branch_name" | Incorporate changes from the named commits (since the time their histories diverged from the current branch) into the current branch
git log | Show committed files
git log --oneline | List one commit per line and it shows the first 7 characters of the SHA1 hash and the commit message
git log > file.txt | Save git log as file.txt
git log --follow "filename" | show the history of "filename" 
git log --since=2017-09-08 | show all commits since date 
git log --untile=2018-05-10 | show all commits untile date
git log --author="Author's Name" | show all commits of "Author's Name"
git log -n1 | show just the last commit
git log -n2 | show the last two commits
git log --grep="filename or partly name " | show just the commit about filename or partly name
git reflog | See what other commits your HEAD has pointed to in the past. This is useful when we lose some new commits using checkout to past commits
git ls-tree "branch_name" | List the contents of "branch_name", like SHA1 hash 
git rm "filename" | Remove  "filename"
git rm -r "foldername" | Remove  "foldername"
git mv "old filename" "new filename" | change name file
git mv "old filename" "name directory"/"new filename" | change directory and change name file
git tag | List all tags
git remote -v | List the URL of the remote repo
git remote add origin "URL"  | Associate your repo with remote 
git remote set-url origin "URL" | Update an existing remote
git push -u origin "branch_name" | Push "branch_name" to remote
git push --force-with-lease | Force with lease gives you the flexibility to override new commits on your remote branch, whilst protecting your old commit history
git pull origin "branch_name" | Pull the most recent changes from that remote branch
git fetch origin | Downloads new data from a remote repository. But it does not integrate any of this new data into your working files.
git clone "URL" | Copy a repo from URL
git rebase origin_branch | Merge in the requested branch (origin_branch in this case) and apply the commits that you have made locally to the top of the history without creating a merge commit 
git submodule add URL/User_name/module_repo name_repo | Add an existing Git repo (module_repo) of a user (User_name) as a submodule of the repo that you are working on. **Note that after implementing this command we should use two more commands "git add ..." and "git commit -m ..." to add the submodule to the former repo.** 
<br>

* Note that origin should be replaced with remote address if remote was not added. 
* Git's push --force is destructive because it unconditionally overwrites the remote repository with whatever you have locally. Instead of git push --force option, use git push --force-with-lease. See this article from [Atlassian](https://developer.atlassian.com/blog/2015/04/force-with-lease/).
* Note that the command **git checkout "SHA1 hash"** switches to a specific commit (determined by SHA1 hash) and **detached HEAD because there is no branch. When HEAD is detached, then it is necessary to point pointer to a branch by running: "git rebase HEAD branch_name" OR "git checkout old_branch_name" OR "git checkout -b new_branch_name"**.

## Git Reset Options

**`git reset`** is a powerful command that can modify the commit history in Git. It moves the `HEAD` pointer to a specified commit, and depending on the options used, it can also update the staging area and working directory. Because `git reset` can rewrite history, it should be used with caution, especially in shared repositories.

- **`git reset --soft "SHA1 hash"`**  
  Reset the position of the `HEAD` pointer without touching the index file or the working tree at all. This moves the files (after the new `HEAD` pointer is set) from the repository to the staging index.

- **`git reset --mixed "SHA1 hash"`**  
  Reset the position of the `HEAD` pointer and reset the index, but do not modify the working tree (i.e., the changed files are preserved but not marked for commit). It also reports what has not been updated.

- **`git reset --hard "SHA1 hash"`**  
  Move your current branch (typically `master`) back to point at the specified SHA1 hash, and make the files in your working tree and staging index the same as the versions committed in that SHA1 hash.

- **`git reset HEAD "file_name"`**  
  Unstage the specified file (`file_name`).

- **`git reset HEAD^`**  
  Remove your last commit from the history (i.e., pop the last commit).

## Git Revert Options

**`git revert`** is a command used to undo changes in a Git repository by creating a new commit that reverses the changes introduced by a previous commit. Unlike `git reset`, `git revert` does not modify the commit history, making it safer for use in shared repositories.

- **`git revert "SHA1 hash"`**  
  Create a new commit that undoes the changes introduced in the specified commit. This command is ideal for safely undoing changes without affecting the commit history.

- **`git revert -n "SHA1 hash"`**  
  Revert the specified commit but do not commit the changes automatically. This allows you to stage multiple reverts or make additional changes before committing.

- **`git revert --no-commit "SHA1 hash"`**  
  Similar to `-n`, this option applies the changes from the revert to the working directory and staging area without creating a new commit immediately, allowing further modifications before committing.

- **`git revert HEAD`**  
  Revert the most recent commit. This command creates a new commit that undoes the latest changes made to the repository.

- **`git revert HEAD~n`**  
  Revert the commit that is `n` commits before the latest commit (where `n` is the number of commits back from `HEAD`). This is useful for undoing changes made several commits ago.

- **`git revert --continue`**  
  Continue the revert process after resolving conflicts that arose during a previous `git revert` operation.

- **`git revert --abort`**  
  Abort the revert operation if there were conflicts or if you decide not to continue with the revert.

## Git Interactive Rebase (`git rebase -i`)

Interactive rebasing (`git rebase -i`) is a powerful tool in Git that allows you to modify your commit history. This includes actions like editing commit messages, squashing multiple commits into one, and reordering commits. Below is a guide to the commands available during an interactive rebase, as well as some additional commands to manage the rebase process.

### Commands in Interactive Rebase

During an interactive rebase, you’ll be presented with a list of commits. You can modify these commits using the following commands:

- **`pick`**: Use the commit as-is.
- **`reword`**: Change the commit message without altering the commit's contents.
- **`edit`**: Pause at the commit to allow for manual modifications (e.g., amending the commit).
- **`squash`**: Combine this commit with the previous one, keeping both commit messages.
- **`fixup`**: Like `squash`, but discards this commit’s message, keeping only the previous commit's message.
- **`drop`**: Remove the commit from the history.

### Example Usage
- This command will start an interactive rebase for the last n commits.
```
git rebase -i HEAD~n
```
- This will start an interactive rebase from the specified commit onward.
```
git rebase -i <commit-hash>
```
### Managing the Rebase Process

- During a rebase, you may encounter conflicts or need to perform other actions. The following commands help manage the rebase process:
```
git rebase --continue: Use this command to continue the rebase process after resolving conflicts or making changes.
git rebase --abort: Abort the rebase and return to the state before the rebase was initiated. This is useful if you decide not to proceed with the rebase.
git rebase --skip: Skip the current commit during the rebase process. This is helpful if a commit causes conflicts that you don't want to resolve.
```

## Aliases

- **git logg**: Display a graphic and readable log on one line using various colours
```
git config --global alias.logg "log --graph --decorate --oneline --abbrev-commit --all"
```

Alias | Code (Should be Run in Terminal) | Description
------|----------------------------------|------------
git logg | git config --global alias.logg "log --graph --decorate --oneline --abbrev-commit --all" | Display a graphic and readable log on one line using various colours

## Setup a Git Credential Helper
Rather than entering your GitHub username and password every time you push, you can setup a Git credential helper to manage this for you.

OS | Command 
---|--------
MAC | git config --global credential.helper osxkeychain
Linux | git config --global credential.helper 'cache --timeout=3600'

Once a credential helper is enabled, the next time you git push, you will add your credentials to the helper.

Certainly! Here's a concise Markdown guide for `git stash` without separate code blocks:

## Git Stash 
Git Stash is a useful feature when you want to save changes in your working directory temporarily without committing them. This allows you to switch branches or work on something else without losing your uncommitted changes.

- **Stash Your Changes**: Temporarily save your uncommitted changes.
  ```
  git stash
  ```

- **View Stashes**: See a list of all stashes.
  ```
  git stash list
  ```

- **Apply a Stash**: Reapply a specific stash without removing it from the list.
  ```
  git stash apply [stash@{n}]
  ```

- **Pop a Stash**: Apply the most recent stash and remove it from the stash list.
  ```
  git stash pop
  ```

- **Drop a Stash**: Delete a specific stash.
  ```
  git stash drop [stash@{n}]
  ```

- **Clear All Stashes**: Remove all stashes.
  ```
  git stash clear
  ```

- **Stash Untracked Files**: Stash both tracked and untracked files.
  ```
  git stash -u
  ```
