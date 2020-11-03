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

Get a split terminal either with `(cntrl+b) then (shift + ')` or `(cntrl+b) then (shift + 5)`. Navigate between the terminals with `(cntrl+b) then (arrow_key)`. Clear unwanted text in panes with `clear` in the target panes.

