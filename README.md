# Terraform Beginner Bootcamp 2023

##Semantic versioning

This project is going to user Semantic Versioning for the Project.

[semver.org] (https://semver.org)

The general format:

**MAJOR.MINOR.PATCH** , eg. '1.0.1'

Given a version number MAJOR.MINOR.PATCH, increment the:

    MAJOR version when you make incompatible API changes
    MINOR version when you add functionality in a backward compatible manner
    PATCH version when you make backward compatible bug fixes

Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.


### Workling on env variables ##

We use environemnt variables to pass some value to the system & use the viarable name fo rreference

A good example would be exporting the http proxu on a linux system

export http_proxy="http://ip:3128"
or
export http_proxy="http://fqdn:3128"

We can print env variable using echo $http_proxy

e.g

http_proxy="http://ip:3128"

export $http_proxy

### End of env vars### 