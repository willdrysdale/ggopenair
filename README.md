# ggopenair

This is work in progress. The aim is to move **openair** from `lattice` to `ggplot2` graphics. When **openair** started, `ggplot2` did not exist and in the early days of `ggplot2` it was slow and lacking many features. These issues have changed. There are several reasons for doing this:

- It will likely be easier to maintain the **openair** based on `ggplot2` rather than `lattice`
- `ggplot2` is actively being developed and there is a growing list of other packages that build on `ggplot2`
- It will be easier for users to modify plots 'after the fact'

## Installation

Installation of openair from GitHub is easy using the devtools
package. Note, because openair contains C++ code a compiler is also
needed. For Windows - for example,
[Rtools](http://cran.r-project.org/bin/windows/Rtools/) is needed.

```R
require(devtools)
install_github('davidcarslaw/ggopenair')
```

**This repository will gradually implement most (but not all) openair functions to `ggplot2`. The package should be considered experimental and unstable until it replaces openair**