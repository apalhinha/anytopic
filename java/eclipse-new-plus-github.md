---
title: New Java project, Eclipse and GitHub
---

# Context

These steps were followed to create a totally new Eclipse project, in sync with GitHub

# Step by step

* In GitHub, create a totally blank project (no readme, no license, no nothing)
* In Eclipse, created a Java project named 'snippet-collector'.
  * Project root is in a folder synced with the cloud. Perhaps redundant, but there will be sources not managed by Git, so a backup is needed
  * Used my_root / root_cloud / root_eclipse / Snippet Collector / snippet-collector
  * Folders follow my naming convention, last one uses github naming convention
    * Eclipse configuration:
	* Location: ...\Snippet Collector\snippet-collector (folder is there)
	* Project name: snippet-collector
* In Eclipse, create a first SnippetCollectorApp class, including the main() function
* In Eclipse,
  * Team
  * Share Project
  * Use or create repository in parent folder of project
  * Create repository
  * Finish
* In Eclipse,
  * Select the 'Git Repositories' window
  * Add all files to 'staged changes'
  * Commit and push
  * Dialog will ask 'origin' repository>
    * URI: https for the git repository in GitHub, https://github.com/apalhinha/snippet-collector.git
	* Host: Github.com
	* Repository path: all from the URI, after github.com, /apalhinha/snippet-collector.git
	* User and password needed
* In Eclipse, create a README.md file
  * Menu File - New - File
  * Select the 'snippet-collector \[snippet-collector master\] folder as parent folder
  * Name the file README.md
  * Type some content, its the entry point in the GitHub portal
* In Eclipse, create a license file
  * Menu File - New - File
  * Select the 'snippet-collector \[snippet-collector master\] folder as parent folder
  * Name the file LICENSE
  * Copy+paste the intended license text
    * Use [https://choosealicense.com/](https://choosealicense.com/){:target="_blank"} to select the license
	* In case you want the MIT License (permissive, copy-write notice o be kept), get it from [https://choosealicense.com/licenses/mit/](https://choosealicense.com/licenses/mit/) {:target="_blank"}
	* Remember to fix the year and your name

# Read Materials
* Key concepts appear in a [Youtube video](https://www.youtube.com/watch?v=ptK9-CNms98) by TheChernoProject

{% include_relative footer_java.md %}
