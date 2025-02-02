
<!-- README.md is generated from README.Rmd. Please edit that file -->

# JDCruncheR

The primary objective of the JDCruncheR package is to provide a quick
and easy access to the JDemetra+ cruncher (JWSACruncher) from R. The
cruncher is a tool to update a JDemetra+ workspace, without having to
open the software itself. The latest version can be downloaded here:
<https://github.com/jdemetra/jwsacruncher/releases>. Fore more
information, please refer to the wiki page:
<https://github.com/jdemetra/jwsacruncher/wiki>.

With JDCruncheR, you can also generate a *quality report* based on the
cruncher output. This report is a summary of the seasonal adjustment
diagnostics. It can be used to spot the most problematic series which
will require a finer analysis. This is most useful when dealing with a
great number of series, which renders impossible the examination of
every diagnostic for every series in a reasonable time.

There are two ways to install the JDCruncheR package:

  - using the devtools package:

<!-- end list -->

``` r
# install.packages("devtools")
devtools::install_github("InseeFr/JDCruncheR", build_vignettes = TRUE)
```

  - from the **.zip** or **.tar.gz** file, that can both be found here:
    <https://github.com/InseeFr/JDCruncheR/releases>. For more info on
    the package installation and the cruncher configuration, please
    refer to the [wiki](https://github.com/InseeFr/JDCruncheR/wiki).
