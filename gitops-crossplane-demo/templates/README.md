# Repository Setup

This repository is configured with git hooks to enforce conventional commit messages.

## Setting up Git Hooks

Run these commands to enable the git hooks:

```bash
# Make the hook executable
chmod +x .githooks/commit-msg

# Configure git to use the hooks
git config core.hooksPath .githooks
```

## Commit Message Format

Commits must follow the conventional commits format:
- Format: `<type>[optional scope]: <description>`
- Types: fix, feat, build, docs, style, refactor, perf, test, chore
- Example: `feat(auth): add login functionality` 