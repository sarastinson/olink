# Holbaek Olink

This project is for analyses of Olink data in The Holbaek Study

## Brief description of folder and file contents

The following folders contain:

- `data/`: Results and assay metadata - DO NOT push to github    
- `doc/`: Contains Rmd files  
- `R/`: Contains R scripts  

## Installing project software dependencies

If dependencies have been managed by using `usethis::use_package("packagename")`
through the `DESCRIPTION` file, installing dependencies is as easy as opening the
`olink.Rproj` file and running this command in the console:

    # install.packages("remotes")
    remotes::install_deps()

You'll need to have devtools installed for this to work.

## Resource

Check out the [prodigenr](https://lwjohnst86.github.io/prodigenr) online
documentation for details on this setup and workflow.
