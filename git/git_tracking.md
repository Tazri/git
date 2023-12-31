Track and Untrack
=================

## Track Files and Directories

> 🟢 Track files and directories are the files and directories thats git knows about.

## Untrack Files and Directories

> 🟢 The files and directories thats are not track called untrack files and directories.

## Git Status

> 🟢 `git status` command to see 

## Process to Tracking file

There is a three state to traking file in git. Here : 

- [Modified](#modified)
- [Staging](#staging)
- [Commiting](#commiting)

### Modified

> 🟢 In this state, file or folder are created and those file and folder are untracked.

**To see the untrack and track file used `git status` file :**

```bash
git status
```


### Staging

> 🟢 Staging means, marked untracked file which become tracked file. To staging file and folder used `add` command.


**Add single file :**
```bash
git add file_or_folder_name_with_path
```

**Add all file and folder of present directory :**
```bash
git add .
```

**Add whole file and folder :**
```bash
git add --all
```

> 🟢 If file and folder marked then those file and folder called staged file or folder.

> 🟢 If unmark the file or folder in git then use `reset` command. This process called unstaging.

```bash
# for spacific file or folder
git reset filename

# whole file and folder of present working directory
git reset .

# whole file and folder
git reset 
```

### Commiting

> 🟢 This is the last state of tracking a file. Git commit is used to create a snapshot of the staged changes along a timeline of a git projects history.

**Commit command used for commiting code :**

```bash
git commit -m "meaningfull message"
```

**Commiting with terminal editor :**
```bash
git commit
```

## Git Log

> 🟢 `git log` command display commited snapshots. 

```bash
git log
```

**Structure of a snapshot of commit :**
```bash
Author: authorName <user@email.com>
Date:   date when commited

    Here is the message for commit.
```

**To see git log in one line then use `--oneline` flag :**
```bash
git log --oneline
```

**Structure of a snapshot of commit if run --oneline flag :**
```bash
<commit id> commit message
```

## Go Back Previous Version of Commit

> 🟢 Below command use for go back previous version of commit.

```bash
git reset --hard commit_id
```

> 🟢 `git reflog` command used to see `reset --hard` history.

## Git rm command

> `git rm -f` or `git rm --force` command used for forcefully remove individual files or a collection of files from directory and stage.

```bash
git rm -f file_name
git rm --force file_name
```


