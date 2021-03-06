
<!-- README.md is generated from README.Rmd. Please edit that file -->

# datadevtools

<!-- badges: start -->

<!-- badges: end -->

The tidyverse has made package development a lot easier. In the past,
there was a lot of work with using tools like `package.skeleton`, the
pseudo-latex for documentation of each R function, and so on. This made
it hard to create high quality R packages. There was a lot of manual
work to make sure that things were documented properly. That has now
been made easier thanks to `devtools`, and `roxygen2`. More people can
now quite easily write a high quality package.

We are still in the past a bit with the current state of data sharing
tools. There is the same opportunity here with data tooling as there was
with package development tools like `devtools`. The aim of
`datadevtools` is to automate checks for your data, and make it easy to
do things like:

  - Add Metadata file
  - Add a README (and paste the metadata file here)
  - Add attribution/citation information
  - Add data appropriate licenses
  - Share on a cloud service
  - Perform general data formatting checks
  - Run checks on the data source (like in
    [checkers](https://github.com/ropenscilabs/checkers))
