# readxlsb

Import data from 'Excel' binary (.xlsb) workbooks into R.

Compatibility updates by Renova.

Version 0.1.61.9001 is a metadata-only change: the stale optional `Date` field was removed from `DESCRIPTION`. No R, C++ or documentation file was changed.

## Install

From R-universe:

```r
install.packages("readxlsb", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or the exact release tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/readxlsb@renova-0.1.61.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

readxlsb was written by Michael Allen (maintainer). License: GPL-3 (see [COPYING](COPYING)).
