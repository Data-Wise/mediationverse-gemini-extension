# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2025-12-05

### Added

- Initial release of mediationverse Gemini CLI extension
- **Development commands**:
  - `/r-check` - Run R CMD check with CRAN best practices
  - `/r-document` - Generate roxygen2 documentation
  - `/r-test` - Run testthat tests
  - `/r-build` - Full CRAN submission workflow
- **Documentation commands**:
  - `/document-function` - Generate roxygen2 headers
  - `/format-quarto-math` - Format LaTeX for Quarto/RMarkdown
  - `/find-bibtex` - Find BibTeX citations for mediation papers
- **Code quality commands**:
  - `/review-and-teach` - CRAN maintainer-style review with teaching
  - `/explain-simply` - Simple statistical explanations
  - `/generate-test-with-comments` - Generate annotated testthat blocks
  - `/validate-inputs` - Refactor to use checkmate validation
  - `/finalize-task` - Summarize session and generate git commit message
