---
title: "Git Submodules"
date: 2020-09-18T02:15:44+08:00
draft: true
---
## What is git submodules
Submodules allow you to include or embed one or more repositories as a
sub-folder inside another repository.

## add submodule
`git submodule add -b master https://github.com/<USERNAME>/<USERNAME>.github.io.git public`

## download content
older version may not download submodule conten,
using 
`git submodule update --init --recursive`
to download content.

## doc
https://github.blog/2016-02-01-working-with-submodules/
