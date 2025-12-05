# Getting Started with Mediationverse Extension

> A tutorial guide to efficient R package development with agentic workflows.

## Quick Start (5 minutes)

### Install the Extension

```bash
gemini extensions install https://github.com/Data-Wise/mediationverse-gemini-extension
```

### Your First Command

```bash
# In your R package directory
gemini

# Then try:
/r-gather
```

This gives you a quick overview of any R package.

---

## Choose Your Path

### New Package?

```
/r-init
```

This will:

1. Ask about your package (name, purpose, features)
2. Create a development plan
3. Wait for your approval
4. Build the package skeleton

### Existing Package?

| Situation | Command | What it does |
|-----------|---------|--------------|
| Quick look | `/r-gather` | Read-only summary |
| Start developing | `/r-onboard` | Creates planning docs |
| Resume work | `/r-resume` | Loads previous context |

---

## Session Workflow

Every coding session follows this pattern:

```
┌─────────────────────────────────────┐
│ START: /r-resume                    │
│   • Loads context from LEARNINGS.md │
│   • Checks git status               │
│   • Suggests what to work on        │
└─────────────────────────────────────┘
              ↓
┌─────────────────────────────────────┐
│ WORK: Choose your pattern           │
│   • Planning: complex tasks         │
│   • Interactive: normal dev         │
│   • Agentic: routine tasks          │
└─────────────────────────────────────┘
              ↓
┌─────────────────────────────────────┐
│ END: /r-save → /r-learn             │
│   • Saves session progress          │
│   • Captures what you learned       │
│   • Suggests commit message         │
└─────────────────────────────────────┘
```

---

## Common Scenarios

### 1. Create a New Package

```
/r-init
```

Follow the prompts:

- Name your package
- Describe its purpose
- List key features

Agent creates plan → You approve → Package built.

### 2. Fix Failing R CMD Check

```
/r-check
```

Agent will:

- Run `devtools::check()`
- Identify errors/warnings
- Suggest fixes
- Ask before applying

### 3. Build Website

```
/r-pkgdown
```

Creates or updates your pkgdown site with proper configuration.

### 4. Release to CRAN

```
/r-cran      # Prepare submission
/r-release   # Merge dev→main, tag version
```

---

## Command Cheatsheet

| Task | Command |
|------|---------|
| Get help | `/r-help` |
| Start session | `/r-resume` |
| End session | `/r-save` |
| Check package | `/r-check` |
| Run tests | `/r-test` |
| Fix issues | `/r-fix` |
| Generate docs | `/r-docs` |
| Build site | `/r-pkgdown` |
| Release | `/r-release` |
| Weekly updates | `/r-updates` |
| Report bug | `/r-feedback` |

---

## Tips & Best Practices

### 1. Use S7 for OOP

All new packages default to S7 classes (not S3/S4).

### 2. Use checkmate for Validation

```r
checkmate::assert_numeric(x, lower = 0)
```

### 3. Weekly Package Checks

Run `/r-updates` weekly to stay current on:

- S7, devtools, pkgdown updates
- CRAN policy changes

### 4. Let the Agent Learn

End sessions with `/r-save` to capture learnings that persist across sessions.

---

## Need Help?

| What | Command |
|------|---------|
| Review code | `/r-review` |
| Learn while reviewing | `/review-and-teach` |
| Document function | `/document-function` |
| Validate inputs | `/validate-inputs` |

---

## Next Steps

1. Run `/r-gather` on an existing package
2. Or start fresh with `/r-init`
3. Explore commands in [README.md](README.md)
