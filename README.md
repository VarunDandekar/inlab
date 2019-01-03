# Inlab

This project contains client code. Basic architecture is to keep client code in github and host it from [here](https://harshkasyap.github.io/inlab/). It should resemble like a framework, which accepts variety of data from server and oraganise accordingly. For testing progress, server database/authentication can be used in firebase. At same time, server data migration should be taken care of.

## Development Strategy

* master branch is production branch, which should be running live. It should only be accepting changes from another stable branch develop.
* develop branch should also be a stable branch at any point of time, which should be forked/branched by developers. No changes should be accepted without a PR.
* creator/collaborators if unable to fork, create a feature branch for development.