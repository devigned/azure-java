# Azure Manifest of Projects
Repo manifest of projects for Azure SDKs.

# Getting Started
This will help you get started pulling down the projects using repo. This project contains a set of groups, which
correspond to the languages each of the projects are implemented. For example, java, node, ruby, etc...

## Init
The sets of projects can be pulled down all at once or by their individual groups. If init is run without specifying a
group, then the entire set of projects will be sync'd.

- To init for all projects, run `repo init -u https://github.com/devigned/azure-manifest`
- To init for a single group, run `repo init -u https://github.com/devigned/azure-manifest -g <group>`
 - Example: `repo init -u https://github.com/devigned/azure-manifest -g java` for the java group.

## Sync
This command will clone the specified init group. Run sync with `repo sync`
