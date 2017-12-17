---
layout: post
title: "Tmux tutorial"
categories: Tutorials
description: a tutorial on tmux
---

tmux is a software application that can be used to multiplex several virtual consoles, allowing a user to access multiple separate terminal sessions inside a single terminal window or remote terminal session.  

-----

**Before entering tmux (in terminal)**

`tmux ls` = show all the sessions  

`tmux a -t [session name]`= attach to a tmux session  

`tmux new -s [session name]` = create a new session  

`tmux rename -t [session old name] [session new name]` = rename a session  

-----
**After entering tmux**

`C-a` + `d` = detach

`C-a` + `s` = list all the sessions

`C-a` + `$` = rename the current session

`C-a` + `c` = create a new window

`C-a` + `,` = rename the current window

`C-a` + `1` = to a window 1

`C-a` + `t` = show a clock

`C-a` + `?` = show shortcuts

`C-a` + `%` = vertical split

`C-a` + `"` = horizontal split  

---
### References

[cheatsheet1](http://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/)

[cheatsheet 2](http://harttle.land/2015/11/06/tmux-startup.html)

[cheatsheet 3](https://gist.github.com/henrik/1967800)
