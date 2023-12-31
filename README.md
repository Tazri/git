command/config
===============

### Listing

**To see git configuration list locally :**

```bash
git config --list
```

**To see global git configuration use `--global` flag :**

```bash
git config --global --list
```
<hr />

### Adding

**Syntax to set git spacific configuration :**

```bash
git config configuration.name "value"
```

**Do this for globally :**
```bash
git config --global configuration.name "value"
```

### Removing

**Syntex to unset git spacific configuration :**
```bash
git config --unset configuration.name
```

**Do this for gobally :**
```bash 
git config --global --unset configuration.name
```


### Editing

> 🟢 `--edit` flag used for configure git setting in terminal editor :

**Locally :**
```bash
git config --edit
```

**Gobally :**
```bash
git config --global --edit
```