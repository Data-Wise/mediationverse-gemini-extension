# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2025-12-05

### Added

- **Help & Feedback**:
  - `/r-help` - Show help menu, commands, and documentation
  - `/r-feedback` - Submit bug reports and feature requests

- **GitHub Issue Templates**:
  - Bug report template
  - Feature request template

- **Documentation**:
  - `GETTING_STARTED.md` - Tutorial-style guide
  - Updated README with orchestration patterns

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

- Initial release with 27 commands
- Merged from r-package-dev-gemini
- Mediationverse specific commands
