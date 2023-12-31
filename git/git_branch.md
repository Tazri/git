Git Branch
===========

This file contains : 

- [Branch Command](#branch-command)
- [Making the git branch](#making-the-git-branch)
- [Switching Branch](#switching-branch)
- [Rename the branch](#rename-the-branch)
- [Deleting Branch](#deleting-branch)
- [Merging Branch](#merging-branch)


<hr />

## Branch Command

> 🟢 A branch is a new/sperate verson of the main or any other repository.

**Use `branch --list` command see how many branches are created :**

```bash
git branch --list
git branch -l
git branch
```

## Making the git branch

**Here is a command to create git branch :**
```bash
git branch <new_branch_name>
```

**Another way is :**
```bash
git checkout -b <new_branch_name>
```

## Switching Branch

**`switch` command to use switch branch :**

```bash
git switch branch_name_to_switch
```

**`checkout` command to use switch branch :**
```bash
git checkout branch_name_to_switch
```

## Rename the branch

> 🟢 First goto the branch, and use `git branch -m` command to rename the branch.

```bash
git branch -m <new_branch_name_for_renaming>
```

## Deleting Branch

**`git branch -d` command to delete branch. If any here is exist then the branch dose not deleting. Here is command :**

```bash
git branch -d branch_name
```

**`git branch -D` to Delete branch even some change exist :**

```bash
git branch -D branch_name
```

## Merging branch

**Use `git merge` command merge to branch. Here is command syntax :**

```git
git merge <branch_name> <with_merging_branch>
```

<hr />

## [< Go Back git.md](./git.md)

## [< Go Back README.md](./../README.md)