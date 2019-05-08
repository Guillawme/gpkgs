# Install R packages I use all the time

This is a dummy R package that uses the dependency resolution mechanism to
install all the packages I use all the time in only one command. It only
requires the `devtools` package to be installed, then the following command
will install all my favorite packages:

```r
devtools::install_github("Guillawme/gpkgs")
```

This package can then be removed, as it does not provide any code or data.
