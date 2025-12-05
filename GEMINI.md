# Mediationverse Extension

The **mediationverse** extension provides a comprehensive suite of tools for R package development, combining general best practices with specialized support for mediation analysis.

## Core Workflows

### 🚀 Setup & Planning

- `/r-init` - Initialize new package
- `/r-onboard` - Analyze existing package
- `/r-resume` - Resume work
- `/r-save` - Save progress

### 🛠️ Development

- `/r-check` - Run `devtools::check()` (CRAN standards)
- `/r-test` - Run `devtools::test()`
- `/r-docs` - Run `devtools::document()`
- `/r-s7` - S7 object-oriented programming
- `/r-fix` - Auto-fix common issues

### 📝 Documentation

- `/r-pkgdown` - Build website
- `/r-readme` - Generate README
- `/document-function` - Detailed roxygen2 headers
- `/format-quarto-math` - Format math for vignettes
- `/find-bibtex` - Find mediation citations

### 🔍 Quality & Review

- `/r-lint` - Tidyverse linting
- `/review-and-teach` - CRAN maintainer-style review
- `/validate-inputs` - Refactor to use `checkmate`
- `/finalize-task` - Generate commit messages

## Best Practices

- **Validation**: Use `checkmate` for defensive programming
- **Testing**: Use `testthat` (edition 3)
- **Documentation**: Use `roxygen2` and Quarto vignettes
- **Style**: Follow tidyverse style guide
