# Overview

This package contains RMarkdown templates for use by DPC's Recovery Tracking and Analytics Branch. It works well with RStudio.

# Version

This is a first version of the package and is a minimum viable product. It contains a single PDF report template with table of contents formatting and custom fonts.

# Installation

Installation is straightforward but requires `devtools`.

```
if (!requireNamespace("devtools")) install.packages("devtools")
devtools::install_github("dpc-michaelean-odonnell/rtabtemplates")
```

# Usage

Usage is also straightforward. After installation in `RStudio`, just go to `File > New File > RMarkdown > From Template`  and then select `RTAB report template`.
