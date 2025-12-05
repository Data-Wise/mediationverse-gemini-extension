# Contributing to mediationverse-gemini-extension

Thank you for your interest in contributing!

## How to Contribute

### Reporting Issues

- Use GitHub Issues to report bugs or suggest features
- Include the Gemini CLI version and the command you tried

### Adding New Commands

1. Create a new `.toml` file in `commands/`
2. Follow the existing format:

   ```toml
   description = "Short description of the command"
   prompt = """
   Your prompt here...
   """
   ```

3. Update `GEMINI.md` to list the new command
4. Update `README.md` with the command description

### Pull Requests

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Code Style

- Use clear, descriptive command names with hyphens (e.g., `r-check`, `validate-inputs`)
- Write prompts that are specific to R package development
- Include context about the mediationverse ecosystem where relevant

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.
