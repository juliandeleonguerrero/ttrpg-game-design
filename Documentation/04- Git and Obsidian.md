---
tags:
  - documentation
---
# Git and Obsidian

Since Obsidian.md uses what is largely plaintext for editing, it works very well with git version control. This has many advantages over other backup options, including version and edit history, the ability to easily revert changes, branches (particularly useful for advanced collaboration with other writers) and more. 

Setup and best practice is detailed below.

# Setting up a git repo for your vault

## Cloning the repo

As noted in the [[README]], this repository can be cloned from GitHub, and has been marked as a template repository. Once cloned, you will immediately have your own fresh git repository.

## Obsidian Git plugin

If you lack technical savvy but wish to use git as your backup option of choice, or don't want to deal with the traditional git workflow, you may want to check out the Obsidian Git plugin. If you choose to do so and lack experience with git, it is **strongly recommended** that you read the documentation available [here](https://publish.obsidian.md/git-doc/Start+here).

[Obsidian Git by Denis Olehov](https://github.com/denolehov/obsidian-git) *MIT License*

## Initializing via terminal

If you have "installed" the vault via extracting the .zip file, open the root level of your vault in your terminal of choice, and type `git init` (assuming you have git installed on your device already). You can then proceed via typical command line workflows, or open the repo in your favorite GUI client for git.


# Before your first commit...

Consider setting up a .gitignore file. 

If you see yourself editing the vault across multiple devices/PCs, add the following line to your .gitignore:

```
.obsidian/workspace.json
```

The workspace.json file saves the layout and size options of your Obsidian vault when you were last editing. If this is synced across devices, this can cause appearance issues or initial awkwardness when first opening Obsidian again. This is most common between devices of varying screen sizes or dimensions. 

While a small inconvenience to fix upon opening, you'll (hopefully) be opening the vault dozens, if not hundreds of times. Save yourself some time now.

# Commit often

Making regular commits is important. Make sure your work isn't lost. And even more importantly, if you accidentally delete work you need, you'll want to make it easier on yourself to recover that file via previous commits.

It doesn't take long, and it can save a lot of effort in the future. 