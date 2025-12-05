# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2025-12-05

### Added

- **Agentic workflow orchestration patterns**
  - Planning, Interactive, Agentic modes
  - Session workflow (r-resume → work → r-save)

- **New commands (6)**:
  - `/r-gather` - Quick package info (read-only)
  - `/r-plan` - Update planning docs
  - `/r-release` - Merge dev→main, tag, return to dev
  - `/r-llm-docs` - Generate llms.txt for AI
  - `/r-quarto` - Quarto vignette workflow
  - `/r-updates` - Check package + CRAN policy updates

- **Enhanced commands**:
  - `/r-init` - Planning-first approach, S7 default
  - `/r-pkgdown` - build_llm_docs(), Bootstrap 5
  - `/r-resume` - Orchestration pattern detection
  - `/r-save` - Reflection/learning capture step

### Removed

- `/r-build` - Use `/r-check` + `/r-cran` instead
- `/r-document` - Use `/r-docs` instead

## [0.1.0] - 2025-12-05

### Added

- **Merged commands from r-package-dev-gemini**:
  - Setup: `/r-init`, `/r-onboard`, `/r-resume`, `/r-save`, `/r-learn`, `/r-usethis`, `/r-git`
  - Development: `/r-s7`, `/r-fix`, `/r-lint`, `/r-docs`
  - Documentation: `/r-readme`, `/r-news`, `/r-pkgdown`, `/r-actions`, `/r-ci`
- **Mediationverse specific commands**:
  - `/document-function`
  - `/review-and-teach`, `/generate-test-with-comments`
  - `/validate-inputs`, `/finalize-task`
