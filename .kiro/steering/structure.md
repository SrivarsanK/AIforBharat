# Project Structure

## Current Organization

```
.
├── .git/              # Git version control
├── .kiro/             # Kiro AI assistant configuration
│   └── steering/      # AI assistant guidance documents
└── .vscode/           # VSCode editor settings
```

## Directory Conventions

As the project grows, maintain clear separation of concerns:

- Configuration files should be at the root level
- Source code should be organized in a dedicated directory (e.g., `src/`)
- Tests should be co-located with source files or in a parallel structure
- Documentation should be easily discoverable

## File Naming

- Use consistent naming conventions across the project
- Follow language/framework-specific conventions when applicable
- Keep names descriptive but concise
