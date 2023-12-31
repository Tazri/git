Git Config
===========

This file contains details about git config command. Here is table of contains : 

- [--list](#list)
- [Set Git Configuration](#set-git-configuration)
- [Edit Configuration](#edit-configuration)

<hr />

## --list

**To see git configuration list locally :**

```bash
git config --list
```

**To see global git configuration use `--global` flag :**

```bash
git config --global --list
```

## Set git configuration

**Syntax to set git spacific configuration :**

```bash
git config configuration.name "value"
```

**Do this for globally :**
```bash
git config --global configuration.name "value"
```

**Syntex to unset git spacific configuration :**
```bash
git config --unset configuration.name
```

**Do this for gobally :**
```bash 
git config --global --unset configuration.name
```

## --edit configuration

> 🟢 `--edit` flag used for configure git setting in terminal editor :

**Locally :**
```bash
git config --edit
```

**Gobally :**
```bash
git config --global --edit
```


<hr />

## [< Go Back git.md](./git.md)

## [< Go Back README.md](./../README.md)