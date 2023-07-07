# My git template
Basic template for hooks to facilitate updating ctags when codebase changes
also adds an exclude for `.tags`, which is the name of the ctags file generated

To make this default template: `git config init.templatedir /path/to/repository/git-template`
- Then, upon initializing or cloning a repository, the contents of info and hooks directories should be replaced with the contents of the git-template/ in this repository

These hooks were copied from an article titled [Getting started with Ctags with Vim and Git by Aaron Young](https://geekdude.github.io/tech/ctags/). This repository will be edited as my workflow evolves, but feel free to use this git emplate as needed.
