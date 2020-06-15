# yaml-pipeline

This repo contains a yaml file for the deployment CI/CD of a demo web app in azure.

This yaml will create a pipeline to maintain and deploy the "Parts Unlimited" DevOps Team project from Azure DevOps Labs as found here: https://azuredevopslabs.com/labs/azuredevops/prereq

It will trigger the build (test) and deploy steps when committing to the master branch. So that we have a working CI/CD process configured.

## Usage

Add the azure-pipeline.yml to the root of your .NET application repository.
This will automatically be picked up by the Azure DevOps pipeline.
