# Mediationverse Gemini CLI Extension

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Gemini CLI](https://img.shields.io/badge/Gemini%20CLI-Extension-purple)](https://github.com/google-gemini/gemini-cli)
[![Version](https://img.shields.io/badge/version-1.2.0-green.svg)](NEWS.md)
[![Commands](https://img.shields.io/badge/commands-33-orange.svg)](GEMINI.md)
[![R Package Dev](https://img.shields.io/badge/R-Package%20Dev-blue.svg)](https://r-pkgs.org/)

> 🚀 R package development with **agentic workflows** — Planning, Interactive, and Autonomous modes

## Installation

```bash
gemini extensions install https://github.com/Data-Wise/mediationverse-gemini-extension
```

**New?** See the [Getting Started Guide](GETTING_STARTED.md) for a tutorial.

## Orchestration Patterns

| Pattern | Trigger | Behavior |
|---------|---------|----------|
| **Planning** | Complex tasks, new package | Plan → approval → execute |
| **Interactive** | Normal development | Step-by-step with user |
| **Agentic** | "go ahead", routine | Full workflow autonomously |

## Commands (33)

### 🚀 Setup & Planning

| Command | Description |
|---------|-------------|
| `/r-help` | Show help and command reference |
| `/r-init` | Initialize new package (planning-first) |
| `/r-onboard` | Analyze existing package |
| `/r-gather` | Quick package info (read-only) |
| `/r-feedback` | Submit bug report or feature request |

### 📋 Session Management

| Command | Description |
|---------|-------------|
| `/r-resume` | Resume previous work |
| `/r-save` | Save progress, end session |
| `/r-learn` | Add to LEARNINGS.md |
| `/r-plan` | Update planning docs |

### 📦 Development

| Command | Description |
|---------|-------------|
| `/r-check` | Run `devtools::check()` |
| `/r-test` | Create/run testthat tests |
| `/r-fix` | Auto-fix check issues |
| `/r-lint` | Tidyverse style linting |
| `/r-docs` | Generate roxygen2 docs |
| `/r-s7` | S7 class creation |
| `/r-usethis` | Run usethis commands |
| `/r-cran` | CRAN submission prep |
| `/r-updates` | Check package updates |

### 🌐 Website & Docs

| Command | Description |
|---------|-------------|
| `/r-readme` | Generate README.md |
| `/r-news` | Create/update NEWS.md |
| `/r-pkgdown` | Build pkgdown site |
| `/r-llm-docs` | Generate llms.txt for AI |
| `/r-quarto` | Quarto vignette workflow |

### 🔄 Git & CI/CD

| Command | Description |
|---------|-------------|
| `/r-git` | Branch management |
| `/r-release` | Merge dev→main, tag, return |
| `/r-actions` | Create GitHub Actions |
| `/r-ci` | Monitor CI status |
| `/finalize-task` | Generate commit message |

### ✅ Quality & Review

| Command | Description |
|---------|-------------|
| `/r-review` | CRAN code review |
| `/review-and-teach` | Review + explain |
| `/document-function` | Single function docs |
| `/validate-inputs` | Add checkmate validation |
| `/generate-test-with-comments` | Test with explanations |

## Session Workflow

```
START  → /r-resume
WORK   → Choose pattern above
END    → /r-save → /r-learn
WEEKLY → /r-updates
```

## Related Packages

- [RMediation](https://github.com/Data-Wise/RMediation)
- [medfit](https://github.com/Data-Wise/medfit)
- [probmed](https://github.com/Data-Wise/probmed)
- [medsim](https://github.com/Data-Wise/medsim)

## License

[Apache License 2.0](LICENSE)
