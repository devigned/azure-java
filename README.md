# Azure Manifest of Projects
Repo manifest of projects for Azure SDKs.

# Getting Started
This will help you get started pulling down the projects using repo. This project contains a set of groups, which
correspond to the languages each of the projects are implemented. For example, java, node, ruby, etc...

## Install Repo
For folks that don't have repo, it can be installed a number of different ways. Here are a few quick links to help you
get started.
- Windows: https://github.com/esrlabs/git-repo
- Mac:
```bash
brew install repo
```
- Linux: http://source.android.com/source/downloading.html#installing-repo

## Init
The sets of projects can be pulled down all at once or by their individual groups. If init is run without specifying a
group, then the entire set of projects will be sync'd.

- To init for all projects:
```
repo init -u https://github.com/devigned/azure-manifest
```
- To init for a single group:
```bash
repo init -u https://github.com/devigned/azure-manifest -g <group>
```
 - Example: init with only the java group
 ```bash
 repo init -u https://github.com/devigned/azure-manifest -g java
 ```

## Sync
This command will clone the specified init group. Run sync with `repo sync`
