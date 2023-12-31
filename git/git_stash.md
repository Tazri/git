Git Stash
==========

> 🟢 The git stash command, takes uncommitted changes (staged and unstaged), saves them away for later use, and then reverts them from working copy.

**Command to stashing :**
```git
git stash
```

**Command to see git stashes :**
```git
git stash list
```

**Command to see in details git stashes :**
```git
git stash show -p
```

## Apply the git stash on working directory

**Command to apply last git stash :**
```git
git stash pop
```

**Command to apply spacific stash using stash id :**
```git
git stash apply stash@{stash_id}
```

<hr />

## [< Go Back git.md](./git.md)

## [< Go Back README.md](./../README.md)