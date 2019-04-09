---
title: Eclipse new Java project and add to GitHub
---

These steps were followed to create a totally new Eclipse project, in sync with GitHub

* In GitHub, create a totally blank project (no readme, no license, no nothing)
* In Eclipse, created a Java project named 'snippet-collector'.
  * Project root is in a folder synced with the cloud. Perhaps redundant, but there will be sources not managed by Git, so a backup is needed
  * Used my_root / root_cloud / root_eclipse / Snippet Collector / snippet-collector
  * Folders follow my naming convention, last one uses github naming convention
* In Eclipse, create a first SnippetCollectorApp class, including the main() function


{% include_relative footer_java.md %}
