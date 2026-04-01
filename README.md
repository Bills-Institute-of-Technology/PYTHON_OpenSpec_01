# PYTHON_OpenSpec_01

An initial evaluation and training project for exploring AI OpenSpec in a Python development context. The focus is on learning and evaluating OpenSpec's spec-driven workflow features rather than building production Python code.

## Environment

- **Python**: 3.12.10
- **Virtual environment**: `.venv` (standard `venv` module)
- **IDE**: Windsurf with Claude Code

## AI Tooling

This project uses [AI OpenSpec](https://github.com/aispec/openspec) — a spec-driven development workflow that integrates with Claude Code. OpenSpec artifacts are stored in the `openspec/` directory.

The following OpenSpec slash commands are available via `.claude/commands/opsx/`:

| Command | Purpose |
|---|---|
| `/opsx:propose` | Propose a new change and generate all artifacts |
| `/opsx:explore` | Think through ideas and clarify requirements |
| `/opsx:apply` | Implement tasks from an OpenSpec change |
| `/opsx:archive` | Archive a completed change |

## Project Structure

```
PYTHON_OpenSpec_01/
├── .claude/            # Claude Code skills and slash commands
├── .venv/              # Python virtual environment (not tracked)
├── openspec/
│   ├── config.yaml     # OpenSpec project configuration
│   ├── changes/        # Active and archived change proposals
│   └── specs/          # Specification documents
└── .gitignore
```

## License

MIT License — Copyright Bill's Institute of Technology, 2026
