# R-universe Package Repository

![r-universe](https://jesse-smith.r-universe.dev/badges/:total)

This repo contains a `packages.json` file that [R-universe](https://r-universe.dev)
uses to index R packages on my Github account. The corresponding R-universe package
repository is at [https://jesse-smith.r-universe.dev]. You can install packages
from here automatically by adding this repo to the `repos` option in R
(the recommended place is in a project-level or user-level `.Rprofile`):

```{r}
options(repos = c(
  jesse_smith = "https://jesse-smith.r-universe.dev", # Add this repository
  getOption("repos") # Make sure all existing repositories are kept
))
```
