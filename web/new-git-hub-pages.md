---
title: New GitHub Pages site from scratch
---
# Create a new Github Pages solution

Creating a new GitHub Pages site assumes
* A GitHub account exists
* You know how to sync files from your desktop to GitHub (in this example, with GitHub Desktop)

Steps are

1. Create a repository in GitHub
   1. Initialize with a Readme File
   1. Use a .gitignore for Jekyll
1. On Settings, set GitHub Pages acting over the Master Branch, and select a Theme
   1. In case you want a custom domain, setup the redirect in DNS several hours (or days) before setting a custom domain in GitHub
1. On GitHub Desktop, File - Clone a Repository
   1. Use root-projects/root-myproject/myproject-pages
      1. root-projects assuming all will remain in a given place. This one I have in sync with cloud backups
	  1. root-myproject assuming the project has other parts that will not be kept in GitHub. This is the location
	  1. myproject-pages, the folder total in sync with GitHub
   1. Consider copying the _layouts default index.html
1. Set the Google Analytics tag

{% include_relative footer_web.md %}
