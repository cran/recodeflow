- Modified Rbuildignore with: assets, R/test-generator, CONTRIBUTING.md, vignettes
- Modified examples in rec_with_table roxygen comments to fit 100 line limit

# recodeflow 0.1.0.1

- Updated the maintainer email address to a working address (`ysequeira@ohri.ca`).
- Fixed two broken URLs in the documentation.
- Replaced `class(x) == "..."` comparisons with `is.factor()`/`inherits()` to
  follow current R guidance; no change to behaviour for supported inputs.

# recodeflow 0.1.0 (First Version)

- Added rec_with_table functionality
- Added variables and variable_details PMML conversion
- Added vignettes explaining package release
