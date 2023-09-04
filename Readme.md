# Useful Scripts for Jenkins Plugin Update

This folder contains Groovy and Python scripts designed to help Jenkins administrators identify plugins that need updating. These scripts focus particularly on the plugins that are being managed from our team.

## Scripts Overview

### Groovy Scripts

- **find-update-needed-plugins.groovy**: 
  - Lists all Jenkins plugins which require an update, showing both their current and latest versions.

- **find-update-needed-plugins-old-versions.groovy**: 
  - Lists all Jenkins plugins with their current version.

- **find-update-needed-plugins-new-versions.groovy**: 
  - Lists all Jenkins plugins with their latest available version.

### Python Scripts

- **compare-managed-jenkins-plugins-version.py**: 
  - Compares the full list of Jenkins plugins requiring updates to the subset of plugins being managed. Helps determine which managed plugins need to be updated.

- **merge-update-needed-plugins.py**: 
  - Updates the version numbers of managed plugins to the latest available version.

## Example TXT Files

For a better understanding of the scripts and their input/output formats, we've included some sample `.txt` files in the repository. These files represent typical lists of managed plugins and their version numbers.

🚨 **Note**: The version numbers in these example files are outdated and for demonstration purposes only. Please do not use them directly for plugin management. Always ensure you're working with the latest version numbers when using the scripts.


