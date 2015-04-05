# Versions #
Gowut release versions are in the form of:
```
major.minor.maintenance
```
For example: `0.7.0`


# Repositories #
There are 2 main repositories. The **default** repository contains the releases. This is what a `go get` command will download and install. The default repository contains only "merge" commits.

The **dev** repository is used to develop the project, and it contains all the development commits.

## Branches ##
Each release with a different minor version gets its own branch in the **dev** repository named after the major and minor version, for example `0.7`.

## Tags ##
Each release version gets a tag both in the **default** and in the **dev** repository named after the release version, for example `0.7.0`