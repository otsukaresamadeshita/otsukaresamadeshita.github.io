---
title: 'git'
date: 2020-10-15
permalink: /posts/2020/1015/git-ssh/
tags:
  - git
  - bio
  - beginner
  - from zero
  - getting started
---

Git will stop asking you for your credentials every time you push or pull if you simply use `git config credential.helper store` and push to a url related to your account, so you could store your credentials starting from zero by [making a new repository](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/create-a-repo) at github.com, going to your command line, typing `git config credential.helper store`, then the code that git recommends to start a repo:


`echo "# reponame here" >> README.md`
`git init`
`git add README.md`
`git commit -m "first commit"`
`git branch -M main`
`git remote add origin https://github.com/yourusername/yourrepo.git`
`git push -u origin main`

Don't forget to replace your repo in the `git remote add` line.

After this you can see your credentials by using `nano ~/.git-credentials` on your computer.

[git credential store official documentation](https://git-scm.com/docs/git-credential-store)
[stackoverflow](https://stackoverflow.com/questions/35942754/how-to-save-username-and-password-in-git-gitextension)
