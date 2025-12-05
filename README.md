# Mediationverse Gemini CLI Extension

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Gemini CLI](https://img.shields.io/badge/Gemini%20CLI-Extension-purple)](https://github.com/google-gemini/gemini-cli)

A comprehensive [Gemini CLI](https://github.com/google-gemini/gemini-cli) extension for R package development, combining general best practices with specialized tools for the **mediationverse** ecosystem.

## Installation

```bash
gemini extensions install https://github.com/Data-Wise/mediationverse-gemini-extension
```

## Commands

### 🚀 Setup & Planning

| Command | Description |
|---------|-------------|
| `/r-init` | Initialize a new package with development plan |
| `/r-onboard` | Analyze and onboard an existing package |
| `/r-resume` | Resume work from previous session logs |
| `/r-save` | Save progress and update planning docs |
| `/r-learn` | Update knowledge base |
| `/r-usethis` | Run `usethis` setup commands |
| `/r-git` | Manage Git branches and status |

### 🛠️ Development Workflow

| Command | Description |
|---------|-------------|
| `/r-check` | Run `devtools::check()` with CRAN settings |
| `/r-test` | Run `devtools::test()` |
| `/r-build` | Full CRAN submission build workflow |
| `/r-docs` | Run `devtools::document()` |
| `/r-document` | Generate roxygen2 documentation (alias) |
| `/r-s7` | Create S7 classes and methods |
| `/r-fix` | Auto-fix common R CMD check issues |

### 📝 Documentation & Website

| Command | Description |
|---------|-------------|
| `/r-readme` | Generate README with badges |
| `/r-news` | Create/update NEWS.md |
| `/r-pkgdown` | Build pkgdown website |
| `/r-actions` | Setup GitHub Actions |
| `/r-ci` | Check CI workflow status |
| `/document-function` | Generate detailed roxygen2 headers |

### 🔍 Code Quality & Review

| Command | Description |
|---------|-------------|
| `/r-lint` | Lint code with tidyverse style |
| `/r-review` | General code review |
| `/review-and-teach` | CRAN maintainer-style review with teaching |
| `/validate-inputs` | Refactor to use `checkmate` validation |
| `/finalize-task` | Summarize session and generate commit message |

### 🎓 Teaching & Explanation

| Command | Description |
|---------|-------------|
| `/generate-test-with-comments` | Generate annotated testthat blocks |

## Usage Examples

### Start a new feature

```
/r-git create a new branch for feature-x
```

### Check your package

```
/r-check
```

## Related Packages

- [RMediation](https://github.com/Data-Wise/RMediation)
- [medfit](https://github.com/Data-Wise/medfit)
- [probmed](https://github.com/Data-Wise/probmed)
- [medsim](https://github.com/Data-Wise/medsim)

## License

[Apache License 2.0](LICENSE)
