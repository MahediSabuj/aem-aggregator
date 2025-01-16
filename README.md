# AEM Multi-Module Maven Project
This aem-aggregator uses git submodules to include all the other AEM maven fullstack repos to deploy to AEM cloud enviroment.

## Submodules
The list of the other repos included as submodule are:

* [aem-commons](https://github.com/MahediSabuj/aem-commons)
* [aem-site](https://github.com/MahediSabuj/aem-site)

## How to clone

To clone this repository with all the submodule projects initialized and updated run the following command:

    git clone --recursive git@github.com:MahediSabuj/aem-aggregator.git

## Update the submodules to the latest

To update the git submodules to the latest commit run the following commands:

    git submodule update --remote 
    
To update individual submodule to the latest commit run the following commands:

    git submodule update --remote aem-commons

## Add a git submodule

To add a new git submodule to aem-aggregator repo run the following commands:

    git submodule add -b <branch> <repo>
