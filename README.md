# Holbaek Olink

This project is for analyses of Olink data in The Holbaek Study


## Brief description of folder and file contents


The following folders contain:

- `data/`: metadata - DO NOT push to github
- `doc/`: Rmd
- `R/`: R scripts

## Installing project R package dependencies

If dependencies have been managed by using `usethis::use_package("packagename")`
through the `DESCRIPTION` file, installing dependencies is as easy as opening the
`olink.Rproj` file and running this command in the console:

    # install.packages("remotes")
    remotes::install_deps()

You'll need to have remotes installed for this to work.

## Resource

For more information on this folder and file workflow and setup, check
out the [prodigenr](https://rostools.github.io/prodigenr) online
documentation.
