# Contributing to agent-guard-mcp

Thanks for your interest in contributing!

## Development Setup

```bash
git clone https://github.com/dygogogo/agent-guard-mcp.git
cd agent-guard-mcp
go mod download
```

## Requirements

- Go 1.24+
- No CGO required (pure Go SQLite)

## Development Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feat/your-feature`)
3. Make your changes
4. Run tests: `make test`
5. Ensure `go vet ./...` passes
6. Submit a Pull Request

## Running Tests

```bash
# All tests with race detection
make test

# Coverage report
make cover

# Static analysis
make vet
```

## Code Style

- Run `gofmt` and `goimports` before committing
- Follow standard Go conventions
- Write table-driven tests for new functionality

## Reporting Issues

- Use GitHub Issues
- Include Go version, OS, and steps to reproduce

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
