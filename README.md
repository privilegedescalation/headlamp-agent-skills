# Headlamp Agent Skills

A collection of Claude Code agent skills for developing [Headlamp](https://headlamp.dev/) Kubernetes dashboard plugins.

## Available Skills

### headlamp-plugin-developer

A senior Headlamp plugin engineer agent that covers:

- Plugin registration APIs (`registerRoute`, `registerSidebarEntry`, `registerDetailsViewSection`, etc.)
- CommonComponents usage (`SectionBox`, `SimpleTable`, `NameValueTable`, `StatusLabel`, etc.)
- K8s module and KubeObject patterns
- CRD class definitions
- ApiProxy usage and service proxy URLs
- Theming and dark mode with CSS variables
- Testing mocks for Headlamp APIs
- Code quality conventions (TypeScript strict mode, functional components, accessibility)

## Installation

Copy the desired agent skill(s) from `.claude/agents/` into your project's `.claude/agents/` directory:

```bash
cp .claude/agents/headlamp-plugin-developer.md /path/to/your-headlamp-plugin/.claude/agents/
```

## Usage

Once installed in your Headlamp plugin project, Claude Code will automatically use the agent when building, extending, debugging, or reviewing Headlamp plugins.

## Contributing

Contributions are welcome! To improve an existing skill or add a new one:

1. Edit or create a markdown file in `.claude/agents/`
2. Follow the existing format (YAML frontmatter + detailed reference sections)
3. Test the skill against a real Headlamp plugin project
4. Submit a pull request
