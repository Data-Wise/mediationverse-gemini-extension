# Mediationverse Gemini CLI Extension

A gemini-cli extension for R package development workflows, optimized for the mediationverse ecosystem of mediation analysis packages.

## Installation

Install the extension by running:

```bash
gemini extensions install https://github.com/data-wise/mediationverse-gemini-extension
```

Or install from a local path:

```bash
gemini extensions install /path/to/mediationverse
```

## Commands

### Development Workflow

| Command | Description |
|---------|-------------|
| `/r-check` | Run R CMD check with `--as-cran` flag |
| `/r-document` | Generate roxygen2 documentation |
| `/r-test` | Run testthat tests with coverage |
| `/r-build` | Full CRAN submission workflow |

### Documentation

| Command | Description |
|---------|-------------|
| `/document-function` | Generate roxygen2 headers |
| `/format-quarto-math` | Format LaTeX for Quarto vignettes |
| `/find-bibtex` | Find citations for mediation papers |

### Code Quality

| Command | Description |
|---------|-------------|
| `/review-and-teach` | CRAN-style code review with teaching |
| `/explain-simply` | Simple statistical explanations |
| `/generate-test-with-comments` | Generate annotated testthat blocks |
| `/validate-inputs` | Add checkmate input validation |

## License

Apache License 2.0
