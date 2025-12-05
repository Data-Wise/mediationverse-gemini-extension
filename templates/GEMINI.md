# Project Context for Gemini

> Place this file at the root of your R package repository as `GEMINI.md`

## Package Overview

**Name**: [Package Name]
**Purpose**: [One-line description]
**Version**: [Current version]

## Quick Start

```r
# Installation
devtools::install_github("username/package")

# Basic usage
library(packagename)
result <- main_function(data)
```

## Key Files

| File | Purpose |
|------|---------|
| `R/main.R` | Core functions |
| `R/utils.R` | Helper utilities |
| `tests/testthat/` | Unit tests |
| `vignettes/` | Documentation |

## Architecture

```
package/
├── R/              # Function definitions
├── man/            # Generated documentation
├── tests/          # testthat tests
├── vignettes/      # Quarto vignettes
└── DESCRIPTION     # Package metadata
```

## Development Commands

When working on this package, use these commands:

- `/r-check` - Run R CMD check
- `/r-docs` - Generate documentation
- `/r-test` - Run tests
- `/validate-inputs` - Add checkmate validation

## Coding Standards

- Use `checkmate` for input validation
- Follow tidyverse style guide
- Document with roxygen2
- Test with testthat (edition 3)

## Dependencies

- **Core**: [list key dependencies]
- **Suggests**: [list optional dependencies]

## Common Tasks

### Adding a new function

1. Create function in `R/`
2. Add roxygen2 documentation
3. Run `/r-docs`
4. Add tests in `tests/testthat/`
5. Run `/r-check`

### Updating vignettes

1. Edit `.qmd` files in `vignettes/`
2. Use `/format-quarto-math` for equations
3. Run `quarto render`

## Notes for Gemini

- This package uses S7 classes (not S3/S4)
- Prefer `checkmate::assert_*` over `stopifnot()`
- Run checks from parent directory: `R CMD check --as-cran ../packagename`
