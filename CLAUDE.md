# Headlamp Agent Skills

This repository is the home for developing and maintaining Claude Code agent skills for Headlamp Kubernetes dashboard plugin development.

## Repository Structure

```
.claude/agents/          # Agent skill definitions (markdown with YAML frontmatter)
README.md                # Project documentation
```

## Agent Skill Format

Each skill is a markdown file in `.claude/agents/` with:

1. **YAML frontmatter** — `name`, `description`, `tools`, `model`
2. **System prompt** — Role and behavioral instructions
3. **Reference sections** — API docs, patterns, conventions, and code examples

## Guidelines

- Keep skills focused and practical — include API signatures, code patterns, and common pitfalls
- Use code blocks for all API examples
- Include test mock patterns where applicable
- Update skills when Headlamp APIs change
