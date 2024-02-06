Git Commands
============

### 1. Core:

- `git init`
- `git clone`
- `git add`
- `git commit`
- `git status`
- `git diff`
- `git checkout`
- `git reset`
- `git log`
- `git show`
- `git tag`
- `git push`
- `git pull`

### 2. Branching:

- `git branch`
- `git checkout -b`
- `git merge`
- `git rebase`
- `git branch --set-upstream-to`
- `git branch --unset-upstream`
- `git cherry-pick`

### 3. Merging:

- `git merge`
- `git rebase`

### 4. Stashing:

- `git stash`
- `git stash pop`
- `git stash list`
- `git stash apply`
- `git stash drop`

### 5. Remotes:

- `git remote`
- `git remote add`
- `git remote remove`
- `git fetch`
- `git pull`
- `git push`
- `git clone --mirror`

### 6. Configuration:

- `git config`
- `git global config`
- `git reset config`

### 7. Plumbing:

- `git cat-file`
- `git checkout-index`
- `git commit-tree`
- `git diff-tree`
- `git for-each-ref`
- `git hash-object`
- `git ls-files`
- `git ls-remote`
- `git merge-tree`
- `git read-tree`
- `git rev-parse`
- `git show-branch`
- `git show-ref`
- `git symbolic-ref`
- `git tag --list`
- `git update-ref`

### 8. Porcelain:

- `git blame`
- `git bisect`
- `git checkout`
- `git commit`
- `git diff`
- `git fetch`
- `git grep`
- `git log`
- `git merge`
- `git push`
- `git rebase`
- `git reset`
- `git show`
- `git tag`

### 9. Alias:

- `git config --global alias.<alias> <command>`

### 10. Hook:

- `git config --local core.ho`

___

_A list of my commonly used Git commands_

*If you are interested in my Git aliases, have a look at my `.bash_profile`, found here: https://github.com/joshnh/bash_profile/blob/master/.bash_profile*

--

### 1. Core:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git init` | Initializes a local Git repository. | `git init` |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Creates a local copy of a remote repository. | `git clone ssh://git@github.com/[username]/[repository-name].git` |
| `git add` | Stages changes for the next commit. | `git add [file]` |
| `git commit` | Records changes to the repository. | `git commit -m "commit message"` |
| `git status` | Displays the current status of the working directory. | `git status` |
| `git diff` | Shows the differences between the working directory and the last committed version. | `git diff` |
| `git checkout` | Switches branches or restores working files. | `git checkout [branch/commit]` |
| `git reset` | Unstages changes in the staging area. | `git reset [file]` |
| `git log` | Displays a log of commits. | `git log` |
| `git show` | Shows the details of a specific commit. | `git show [commit]` |
| `git tag` | Adds a tag to a specific commit. | `git tag [tag-name]` |
| `git push` | Uploads local changes to a remote repository. | `git push [remote] [branch]` |
| `git pull` | Fetches changes from a remote repository and merges them. | `git pull [remote] [branch]` |


### 2. Branching:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git branch` | Lists, creates, or deletes branches. | `git branch [branch-name]`, `git branch -d [branch-name]` |
| `git checkout -b` | Creates a new branch and switches to it. | `git checkout -b [new-branch]` |
| `git merge` | Merges changes from one branch into another. | `git merge [branch-name]` |
| `git rebase` | Applies changes from one branch onto another. | `git rebase [base-branch]` |
| `git branch --set-upstream-to` | Sets up the tracking of a remote branch. | `git branch --set-upstream-to=[remote]/[branch]` |
| `git branch --unset-upstream` | Unsets the upstream information for the current branch. | `git branch --unset-upstream` |
| `git cherry-pick` | Applies changes from one branch to another. | `git cherry-pick [commit]` |

### 3. Merging:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git merge` | Merges changes from one branch into another. | `git merge [branch-name]` |
| `git rebase` | Applies changes from one branch onto another. | `git rebase [base-branch]` |

### 4. Stashing:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git stash` | Temporarily saves changes that are not ready to be committed. | `git stash save "stash message"` |
| `git stash pop` | Restores the most recently stashed changes and removes the stash. | `git stash pop` |
| `git stash list` | Lists all stashes made in the current repository. | `git stash list` |
| `git stash apply` | Applies changes from a specific stash onto the current branch. | `git stash apply [stash@{n}]` |
| `git stash drop` | Discards a specific stash. | `git stash drop [stash@{n}]` |

### 5. Remotes:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git remote` | Lists all remote repositories associated with the current project. | `git remote -v` |
| `git remote add` | Adds a new remote repository. | `git remote add [remote-name] [repository-url]` |
| `git remote remove` | Removes a remote repository. | `git remote remove [remote-name]` |
| `git fetch` | Fetches changes from a remote repository but does not merge them. | `git fetch [remote-name]` |
| `git pull` | Fetches changes from a remote repository and merges them into the current branch. | `git pull [remote-name] [branch-name]` |
| `git push` | Uploads local changes to a remote repository. | `git push [remote-name] [branch-name]` |
| `git clone --mirror` | Clones a remote repository along with all its branches and tags. | `git clone --mirror [repository-url]` |

### 6. Configuration:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git config` | Gets and sets repository or global options. | `git config [--local | --global] [key] [value]` |
| `git global config` | Sets a global configuration option for Git. | `git config --global [key] [value]` |
| `git reset config` | Unsets a configuration option. | `git config --unset [key]` |

### 7. Plumbing:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git cat-file` | Provides content or type and size information for repository objects. | `git cat-file -p [object]`, `git cat-file -t [object]` |
| `git checkout-index` | Copies files from the index to the working directory. | `git checkout-index -a -f --prefix=[path]/` |
| `git commit-tree` | Creates a new commit object. | `git commit-tree [-p <parent>] <tree>` |
| `git diff-tree` | Compares content and mode of blobs found via two tree objects. | `git diff-tree [-r] <commit>` |
| `git for-each-ref` | Displays information about references. | `git for-each-ref [--format=<format>]` |
| `git hash-object` | Computes the object ID value for a given file. | `git hash-object -t <type> -w <file>` |
| `git ls-files` | Shows information about files in the index and the working tree. | `git ls-files [--stage]` |
| `git ls-remote` | Shows references in a remote repository. | `git ls-remote [remote]` |
| `git merge-tree` | Shows the changes between three tree objects. | `git merge-tree <base> <branch1> <branch2>` |
| `git read-tree` | Reads tree information into the index. | `git read-tree <tree-ish>` |
| `git rev-parse` | Parses Git revision (object) identifiers. | `git rev-parse [options] <args>` |
| `git show-branch` | Shows the branches and their commits. | `git show-branch [options] [branch1 ...]` |
| `git show-ref` | Outputs references in a human-readable format. | `git show-ref [--hash] [refs]` |
| `git symbolic-ref` | Read or modify symbolic references. | `git symbolic-ref [options] [refs]` |
| `git tag --list` | Lists tags. | `git tag --list` |
| `git update-ref` | Updates the object name stored in a ref safely. | `git update-ref [options] <ref> <newvalue> <oldvalue>` |

### 8. Porcelain:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git blame` | Shows who last modified each line of a file. | `git blame [file]` |
| `git bisect` | Helps find the commit that introduced a bug. | `git bisect [start] [end]` |
| `git checkout` | Switches branches or restores working files. | `git checkout [branch/commit]` |
| `git commit` | Records changes to the repository. | `git commit -m "commit message"` |
| `git diff` | Shows the differences between the working directory and the last committed version. | `git diff` |
| `git fetch` | Fetches changes from a remote repository but does not merge them. | `git fetch [remote-name]` |
| `git grep` | Searches the working directory for lines matching a regex pattern. | `git grep [pattern]` |
| `git log` | Displays a log of commits. | `git log` |
| `git merge` | Merges changes from one branch into another. | `git merge [branch-name]` |
| `git push` | Uploads local changes to a remote repository. | `git push [remote-name] [branch-name]` |
| `git rebase` | Applies changes from one branch onto another. | `git rebase [base-branch]` |
| `git reset` | Unstages changes in the staging area. | `git reset [file]` |
| `git show` | Shows the details of a specific commit. | `git show [commit]` |
| `git tag` | Adds a tag to a specific commit. | `git tag [tag-name]` |

### 9. Alias:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git config --global alias.<alias> <command>` | Creates a shortcut or alias for a Git command. | `git config --global alias.[alias-name] [original-command]` |

### 10. Hook:

| Command | Description | Syntax |
| ------- | ----------- | ------ |
| `git config --local core.hooksPath <path>` | Sets the path to the directory where Git hooks are stored for a specific repository. 
| `git config --local core.hooksPath [path]` |
