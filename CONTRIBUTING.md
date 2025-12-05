# Contributing to mediationverse-gemini-extension

Thank you for your interest in contributing!

## How to Contribute

### Reporting Issues

- Use GitHub Issues to report bugs or suggest features
- Include the Gemini CLI version and the command you tried

### Adding New Commands

1. Create a new `.toml` file in `commands/`
2. Follow the structure:

   ```toml
   description = "Short description"
   prompt = """
   <PERSONA>
   You are an expert in...
   </PERSONA>

   <OBJECTIVE>
   What this command does.
   </OBJECTIVE>

   <INSTRUCTIONS>
   1. Step one
   2. Step two
   </INSTRUCTIONS>

   <OUTPUT>
   Expected output format.
   </OUTPUT>
   """
   ```

3. Assign an **orchestration pattern**:
   - **Planning** — for complex tasks needing approval
   - **Interactive** — for step-by-step guidance
   - **Agentic** — for autonomous execution

4. Update `GEMINI.md` with the new command
5. Update `README.md` command table
6. Update `NEWS.md` changelog

### Pull Requests

1. Fork the repository
2. Create a feature branch from `dev`
3. Make your changes
4. Submit a pull request to `dev`

## Code Style

- Use clear, descriptive command names with hyphens (e.g., `r-check`)
- Include `<PERSONA>`, `<OBJECTIVE>`, `<INSTRUCTIONS>`, `<OUTPUT>` sections
- Default to S7 for OOP, checkmate for validation

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.
