# Terraform Example
This repository contains some Terraform example configurations to use for experimenting and testing atlantis workflows based on some specific use cases used in Catosplace Infrastructure as Code workflows

## Terraform Module
These modules are the base Terraform modules, these do not need an atlantis apply as the only apply required is done by the test framework.

## Terraform Live Modules
These are organisation modules, that are used to configure aspects of modules that should not be able to change.
## Terraform Live
This the live repository, which utilises Terragrunt to structure all of the modules used by an organisation