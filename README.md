# Mediationverse Gemini CLI Extension

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Gemini CLI](https://img.shields.io/badge/Gemini%20CLI-Extension-purple)](https://github.com/google-gemini/gemini-cli)

A [Gemini CLI](https://github.com/google-gemini/gemini-cli) extension for R package development workflows, optimized for the **mediationverse** ecosystem of mediation analysis packages.

## Installation

```bash
gemini extensions install https://github.com/Data-Wise/mediationverse-gemini-extension
```

> **Requires** Gemini CLI v0.4.0 or newer. See [installation instructions](https://github.com/google-gemini/gemini-cli#-installation).

## Commands

### Development Workflow

| Command | Description |
|---------|-------------|
| `/r-check` | Run `R CMD check --as-cran` with best practices |
| `/r-document` | Generate roxygen2 documentation |
| `/r-test` | Run testthat tests |
| `/r-build` | Full CRAN submission workflow |

### Documentation

| Command | Description |
|---------|-------------|
| `/document-function` | Generate complete roxygen2 headers |
| `/format-quarto-math` | Format LaTeX math for Quarto/RMarkdown vignettes |
| `/find-bibtex` | Find BibTeX citations for mediation papers |

### Code Quality & Review

| Command | Description |
|---------|-------------|
| `/review-and-teach` | CRAN maintainer-style code review with teaching |
| `/explain-simply` | Explain statistical concepts simply |
| `/generate-test-with-comments` | Generate annotated testthat test blocks |
| `/validate-inputs` | Refactor to use checkmate input validation |

## Usage Examples

### Check your package for CRAN

```
/r-check
```

### Generate documentation for a function

```
/document-function
```

Then select or paste the function you want documented.

### Get a simple explanation

```
/explain-simply what is the distribution of product method?
```

## Related Packages

This extension is designed for the mediationverse ecosystem:

- [RMediation](https://github.com/Data-Wise/RMediation) - Confidence intervals for mediation effects
- [medfit](https://github.com/Data-Wise/medfit) - Model fitting for mediation
- [probmed](https://github.com/Data-Wise/probmed) - Probability of mediation
- [medsim](https://github.com/Data-Wise/medsim) - Simulation for mediation studies

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

[Apache License 2.0](LICENSE)

## Author

Davood Tofighi, PhD
