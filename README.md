# 🚀 Basics Git Commands

## git init
> Initialize an existing directory as a Git Repository.

## git status
> Show modified files in working directory, staged for your next commit.

## git add [file]
> Add a file as it looks now to your next commit (stage).

## git add .
> This will stage all the files.

## git add -A
> When -A is used , all files in the entire working tree are updated ( old version of Git used to limit the update to the current directory and its subdirectories ).

##  git commit -m “message”
> Commit your staged content as a new commit snapshot.

## git restore - - staged [filename]
> Restore working tree files. By specifying - -staged will only restore the index. ( Used to discard changes in working directory ).

## rm -rf [filename]
> Remove a file.

## git log
> Show all commits in the current branch’s history.

## git reset [commit_hashcode] 
> Reset current HEAD to the specified state.

## git stash
> Save modified and staged changes.

## git stash list
> List stack-order of stashed file changes.

## git stash pop 
> Remove a single stashed state from the stash list and apply it to the top of the current working tree state.

## git stash clear
> Remove all the stash entries. Note that those entries will then be subject to pruning and may be impossible to recover.

## git branch -M main
> With -m or -M option, <oldbranch> will be renamed to <newbranch>. If <newbranch> exists, -M must be used to force the rename to happen.

## git remote add origin [url]
> (git remote → Manage set of tracked repositories.) Update all the branches set to track remote ones, but not merge any changes in.

## git remote -v
> Show remote urls after name.

## git push -u origin main
> Transmit local branch commits to the remote repository branch.

## git branch
> List your branches. * a will appear next to the currently active branch.

## git branch [branch_name]
> Create a new branch at the current commit.

## git checkout [branch_name]
> Switch to another branch and check it out into your working directory.

## git fetch - - all - - prune
> Best utility for cleaning outdated branches. It will connect to a shared remote repository remote and fetch allremote branch refs.

## git reset - - hard [upstream/main]
> Resets the index and working tree. Any changes to tracked files in the working tree since <commit> are discarded. Any untracked files or directories in the way of writing any tracked files are simply deleted.

## git pull [upstream main]
> Fetch and merge any commits from the tracking remote branch.

## git clone [url]
> Retrieve an entire repository from a hosted location via URL.

## git rebase -i [hash_code]
> Used to combine different commits into one single commit.

<br />

## Merge Conflict:-
> It occurs when two people made change in the same line, now git will get confused, which commit should it push or not.
