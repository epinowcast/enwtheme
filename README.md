# A `pkgdown` theme for Epinowcast

This repository hosts the [`pkgdown`](https://pkgdown.r-lib.org/) website theme that we use across Epinowcast community packages.
To use the theme, install this repository as an R package using:

```r
devtools::install_github("epinowcast/enwtheme")
```

Then, include the following text in your `_pkgdown.yml` file:

```
template:
  package: enwtheme
```

See [here](https://github.com/epinowcast/epidist/blob/main/_pkgdown.yml) for an example from the [`epidist`](https://github.com/epinowcast/epidist/) package.

Once you have done this, please alter your package's `DESCRIPTION` file to include:

```
Config/Needs/website:
    epinowcast/enwtheme
```

Again, see [here](https://github.com/epinowcast/epidist/blob/main/DESCRIPTION) for an example from `epidist`.
