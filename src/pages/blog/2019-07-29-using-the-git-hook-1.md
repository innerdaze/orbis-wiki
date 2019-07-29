---
templateKey: blog-post
title: Using the Git Hook
date: 2019-07-29T09:45:26.786Z
description: How to use the Git hook for enforcing branch name conventions
featuredpost: true
featuredimage: /img/imbmgk02w6onylemtdrfnhtg1.svg
tags:
  - git
  - gitflow
  - git-flow
---
# Demo

asciinema ImBMGk02w6ONyLEMtdRfnHtG1

# Installation

Just run \`npm install\` in the project root to pull in the husky package.

# How It Works

When you attempt to commit staged changes, husky runs a script (scripts/git.enforce-branch-name.js) to validate the branch name.

If the branch name does not meet the spec, the commit process will terminate and you will be prompted to rename the branch and run the commit again.
