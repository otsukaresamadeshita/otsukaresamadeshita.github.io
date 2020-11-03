---
title: 'Split Mac Terminal and Other Shortcuts'
date: 2020-11-04
permalink: /posts/2020/1104/Split-Mac-Terminal/
tags:
  - terminal
  - beginner
  - mac
  - tmux
---

Let's make our terminal pretty and pretend like we're pro. 

Open a terminal and go to Terminal>preferences>profiles to choose your profile or create a custom one. I like 'novel'.

Get homebrew if you don't have it already.
Get tmux. `brew install tmux`
Start tmux in the terminal. `tmux`

Use the tmux shortcuts to create a split screen. By default, the shortcut to talk to tmux is (cntrl + b) together. Clicking these, letting go and clicking the next key will give us what we want. Clicking too slowly between cntrl+b or clicking cntrl+b with another key will not give us what we want. 

Get a split terminal either with `(control+b) then (shift + ')` or `(control+b) then (shift + 5)`. Navigate between the terminals with `(control+b) then (arrow_key)`. Clear unwanted text in panes with `clear` in the target panes.

Your terminal now looks like you know something.

There are a few shortcuts I think are indispensible:

`(control+c)` to cancel whatever the terminal is doing.
`(control+a)` and `(control+e)` to skip to beginning and end of a line.
Of course on mac, can't go without `(command+c)` and `(command+v)`: copy and paste.
`(control+u)`: clear the line.

