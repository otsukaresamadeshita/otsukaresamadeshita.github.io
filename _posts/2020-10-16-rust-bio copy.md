---
title: 'Reading SAM files: Rust Bio and Noods'
date: 2020-10-16
permalink: /posts/2020/1016/rust-bio/
tags:
  - rust
  - bio
  - beginner
  - getting started
---

In rust, there are only a few options for reading SAM and BAM files. The first is using rust bio's htslib bindings. I found that although useful, it was a binding to the htslib library. Due to this, it became clear that the user needs to install things, compile, etc. while creating a multitude of dependencies. It felt like it was trying to take advantage of htslib but in the process was becoming unwieldly. I think the user of rust htslib isn't really looking for all the functionality of htslib, otherwise they'd be using htslib directly, but rather to just read in the files. 

Next, we have noodles. This project was written completely in rust and is a library to read files only. I spent a few days working with this project and there were highs and lows. Originally, it seemed very easy to set up with the recommended git support through cargo dependencies. I did the example just fine afterward, but when I started trying to use the modules it became clear that git support was limited. This led me to clone and run noodles locally with [a tutorial](https://github.com/otsukaresamadeshita/noodles/blob/master/command_line_tutorial.md), but this was closed as a PR. I think prospective users will find this tutorial useful, and have thus kept the git branch. I would recommend using cloning and then using noodles, but maybe I was just unlucky. 

In the end, I went for a custom approach.
