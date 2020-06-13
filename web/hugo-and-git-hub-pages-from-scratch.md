---
title: Hugo and GitHub Pages from scratch
---
# Create a new Github Pages site based on Hugo

Creating a new GitHub Pages site based on Hugo, and following this page, assumes
* A GitHub account exists
* Hugo is installed
* Git is installed
* A DNS tool is available to set the custom domain

## Create local website
cd above-project, and
```
websites> hugo new site workout
```

## Add a theme
* Download the zip from https://github.com/Vimux/mainroad
* Inside there is a single folder. Copy it to ...\workout\themes
* You will get someting like ...\workout\themes\Mainroad-master
* Rename folder "Mainroad-master" to "mainroad"

{% include_relative footer_web.md %}
