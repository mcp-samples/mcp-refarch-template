# mcp-refarch-template
MCP Reference Architecture Template Repository

Use this as a template for creating more reference architectures

The recommended way is to create the following structure

* README.md - Contains all the step by step instructions on how to create/run the reference architectures on top of mcp
* templates - Store heat templates, k8s templates or cloud formation tempaltes
* images - Store any images to display on this reference architectures (referenced in the README.md)

# How to submit a new ref arch

## Step 1 Request a new repository under mcp-samples

Contact one of the owners of the *mcp-samples* organization and request him to create a new repository. Repositories will follow the naming convention mcp-refarch-name-of-arch

Example:

* mcp-refarch-drupal
* mcp-refarch-multi-az-wordpress
* mcp-refarch-vault
* mcp-refarch-kuberntes-itsio

## Step 2 Clone the new repository and add your content

Clone the new repository, create a new feature branch and add your content following the structure mentioned above. Add the instructions for this reference architecture to the README.md using markdown or plain text. 

Submit your new refarch with a new pull request.

# How to request a new ref arch

If you rather have one of the existing contributors to create a new reference architecture please submit a issue under this repository, issues under each of the reference architecture repositories are left for fixes of their own.

 
