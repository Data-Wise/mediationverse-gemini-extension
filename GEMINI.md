# Mediationverse Extension

R package development toolkit with **agentic workflows** for efficient programming.

## Orchestration Patterns

| Pattern | Trigger | Behavior |
|---------|---------|----------|
| **Planning** | Complex tasks, new package | Plan → approval → execute |
| **Interactive** | Normal development | Step-by-step with user |
| **Agentic** | "go ahead", routine | Full workflow autonomously |

## Session Workflow

```
START  → /r-resume (load context)
WORK   → Choose pattern above
END    → /r-save → /r-learn
WEEKLY → /r-updates
```

---

## Commands (33)

### 🚀 Setup & Planning

| Command | Purpose |
|---------|---------|
| `/r-help` | Show help and command reference |
| `/r-init` | Initialize new package (planning-first) |
| `/r-onboard` | Analyze existing package |
| `/r-gather` | Quick package info (read-only) |
| `/r-feedback` | Submit bug report or feature request |

### 📋 Session Management

| Command | Purpose |
|---------|---------|
| `/r-resume` | Resume previous work |
| `/r-save` | Save progress, end session |
| `/r-learn` | Add to LEARNINGS.md |
| `/r-plan` | Update planning docs |

### 📦 Development

| Command | Purpose |
|---------|---------|
| `/r-check` | Run devtools::check() |
| `/r-test` | Create/run testthat tests |
| `/r-fix` | Auto-fix check issues |
| `/r-lint` | Tidyverse style linting |
| `/r-docs` | Generate roxygen2 docs |
| `/r-s7` | S7 class creation |
| `/r-usethis` | Run usethis commands |
| `/r-cran` | CRAN submission prep |
| `/r-updates` | Check package updates |

### 🌐 Website & Docs

| Command | Purpose |
|---------|---------|
| `/r-readme` | Generate README.md |
| `/r-news` | Create/update NEWS.md |
| `/r-pkgdown` | Build pkgdown site |
| `/r-llm-docs` | Generate llms.txt for AI |
| `/r-quarto` | Quarto vignette workflow |

### 🔄 Git & CI/CD

| Command | Purpose |
|---------|---------|
| `/r-git` | Branch management |
| `/r-release` | Merge dev→main, tag, return |
| `/r-actions` | Create GitHub Actions |
| `/r-ci` | Monitor CI status |
| `/finalize-task` | Generate commit message |

### ✅ Quality & Review

| Command | Purpose |
|---------|---------|
| `/r-review` | CRAN code review |
| `/review-and-teach` | Review + explain |
| `/document-function` | Single function docs |
| `/validate-inputs` | Add checkmate validation |
| `/generate-test-with-comments` | Test with explanations |

---

## Best Practices

- **OOP**: S7 (default for all packages)
- **Validation**: checkmate
- **Testing**: testthat (edition 3)
- **Documentation**: roxygen2, Quarto
- **Style**: tidyverse guide
