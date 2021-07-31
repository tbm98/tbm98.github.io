---
title: "Remove a Git Submodule"
date: 2021-07-31T14:41:11+07:00
draft: false
categories: [Git]
tags: [Git]
---

* Remove the submodule files from the working tree and index: `git rm --cached path_to_submodule`

* Remove the submodule's `.git` directory: `rm -rf .git/modules/path_to_submodule`

* Delete the now untracked submodule files: `rm -rf path_to_submodule`

source: {{< link "https://stackoverflow.com/a/1260982/12089581" >}}