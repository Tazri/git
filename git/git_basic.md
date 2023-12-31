Git
=====

**This page contains :**

- [Version Control System](#version-controls-system)
- [Git](#git)
- [Working Directory](#working-directory)
- [Local Repository](#local-repository)
- [Remote Repository](#remote-repository)
- [Line Encoding Type](#line-encoding-type)
- [Initialize the Git](#initialize-the-git)

## Version Controls System

> 🟢 Version control is practice of tracking and managing changes software source code time to time.

> 🟢 কোনো software এর জন্য কোড লেখলে পরে তা আবার পরিবর্তন হতে পারে, পরিবর্তন সহকারে software এর source কোড গুলো দক্ষতার সাথে ম্যানেজ করা পদ্ধতিকেই Version Controls বলা হয়। 


## Git

> 🟢 Git is a open source developer tools for used for source code management.

> 🟢 Git হচ্ছে একটি কমান্ড লাইন software যার মাধ্যমে source code manage করা হয়।

## Working Directory

> 🟢 Which directory open in terminal, and currently some process on, called Working Directory or Present Working Directory.

> 🟢 টার্মিনালে যে Directory খোলা থাকে বা যে Directory তে বর্তমান কাজ করা হচ্ছে তাকে Present Working Directory বা Working Directory বলে। 

**PWD command used for see present working directory name with full name :**
```bash
$ pwd
```

## Local Repository

> 🟢 Local Repository is a copy of a entire project's history and codebase that has on a developer's machine.

> 🟢 Developer Computer এ মূল প্রজেক্টের যে কপি থাকে তাকে Local Repository বলে।

## Remote Repository

> 🟢 Remote Repository are version of projects that are hosted on the internet or network somewhere.

## Line Encoding Type

**There are two type of line encoding format for text file :**

- LF (Line Feed) -> Used in unix, max and linux operating system.
- CRLF (Carrage Return Line Feed) -> Used in windows operating system.

**If git make the fie automatically convert lf to crlf then used `core.autocrlf:true` setting for this. Here how to configure this setting globally :**

```bash
$ git config --global core.autocrlf true
```

**For delete this setting :**
```bash
$ git config --global --unset core.autocrlf
```

## Initialize the git

**Used `git init` command to initialize the git in a directory :**

```bash
git init
```


<hr />

## [Go Back git.md](./git.md)
## [Go Back README.md](./../README.md)