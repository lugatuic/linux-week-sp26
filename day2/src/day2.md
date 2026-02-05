---
title: Linux Week Day 2
subtitle: Demystifing the Terminal 
author: Humzah Khan
date: 2/3/2026
---

# 
unix...

# 
![](assets/unixbook.png)

# 
from unix system V to macOS

# 
![](assets/sh.png)

# 
bash
(also fish, zsh)

* colors
* auto-complete
* "command not found" handler

# 
bash scripting will be covered in day 3

# (guided) scavenger hunt
I'll *try* to guide you through using a real terminal.

# phase 1
log into a remote container!
https://doom.acmuic.org

you will be greeted by a nice message before you are dropped into the bash shell.

`/usr/bin/guy`
`/bin/guy`
`./guy`

`./start.sh`

# phase 2
`cd uicLUG/wantsYou/toType/ls -al/`

you might want to type `ls -al` once you get there

`'\ '`

`uicLUG!`

# phase 3

`grep` and `tr`
(search text, translate/filter characters)

there's also:

* `awk` and `sed` (pattern scan, stream editor)
* `head` and `tail` (view start, view end)

and for managing files:

* `cp`
    * `cp -r`
* `mv`
* `rm`
    * `rm -r`

* `sudo rm -rf --no-preserve-root`

# phase 4
got root?

Nobody likes logging in as root
use `sudo` instead!
(or `su`: substitute user)


