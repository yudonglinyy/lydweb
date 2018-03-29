---
title: git note
date: 2018-03-14 16:27:48
tags:
- git
- hexo
---

## push all source hexo to github

```yaml
# _config.yaml
deploy:
  - type: git
    repo: git@github.com:<username>/<username>.github.io.git
    branch: master
  - type: git
    repo: git@github.com:<username>/<username>.github.io.git
    branch: src
    extend_dirs: /
    ignore_hidden: false
    ignore_pattern:
        public: .

```
