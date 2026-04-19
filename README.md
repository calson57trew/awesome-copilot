# awesome-copilot

> A curated list of awesome GitHub Copilot instructions, prompts, agents, and extensions.

[![All Contributors](https://img.shields.io/github/all-contributors/awesome-copilot/awesome-copilot?color=ee8449&style=flat-square)](CONTRIBUTORS.md)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a community-driven fork of [github/awesome-copilot](https://github.com/github/awesome-copilot), extending the collection with additional resources, agent workflows, and marketplace plugins.

> **Personal fork note:** I'm using this repo to experiment with custom Copilot instructions for TypeScript and Python projects. Feel free to browse but note some sections may be works-in-progress. Currently focusing on React/Next.js and FastAPI workflows. Also exploring custom instructions for Go and Terraform.

## Contents

- [Copilot Instructions](#copilot-instructions)
- [Agent Workflows](#agent-workflows)
- [Marketplace Plugins](#marketplace-plugins)
- [Contributing](#contributing)

## Copilot Instructions

Custom `.github/copilot-instructions.md` files that tailor Copilot's behavior for specific languages, frameworks, or workflows.

- See [`.github/copilot-instructions.md`](.github/copilot-instructions.md) for the project's own instructions.
- See [`.github/copilot-instructions-go.md`](.github/copilot-instructions-go.md) for Go-specific instructions (chi router + sqlc patterns).
- See [`.github/copilot-instructions-terraform.md`](.github/copilot-instructions-terraform.md) for Terraform instructions (AWS, module structure).

## Agent Workflows

Reusable agentic workflow definitions for GitHub Copilot agents.

- [Agentic Workflows Agent](.github/agents/agentic-workflows.agent.md) — A meta-agent for orchestrating multi-step agentic tasks.

## Marketplace Plugins

A curated index of GitHub Copilot Extensions available in the marketplace.

- See [`.github/plugin/marketplace.json`](.github/plugin/marketplace.json) for the full machine-readable index.

## Contributing

Contributions are welcome! Please read our [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

### Adding a new resource

1. Fork this repository.
2. Add your resource to the appropriate section.
3. Run `npm run lint` to validate formatting.
4. Open a pull request with a clear description.

### Code of Conduct

This project follows the [Contributor Covenant](https://www.contributor-covenant.org/) Code of Conduct.

## Contributors

Thanks to all our contributors! See [CONTRIBUTORS.md](CONTRIBUTORS.md) for the full list.

## License

[CC0 1.0 Universal](LICENSE) — Public Domain Dedication.

## Personal Notes

<!-- Personal bookmarks and reminders for my own use -->
- [x] Add custom instructions for Go (chi router + sqlc patterns) — done, see `.github/copilot-instructions-go.md`
- [x] Add custom instructions for Terraform (AWS, module structure) — done, see `.github/copilot-instructions-terraform.md`
- [x] Try out the agentic workflow for automation — done, see `.github/agents/agentic-workflows.agent.md`
- [ ] Add custom instructions for React/Next.js (app router, server components)
- [ ] Add custom instructions for FastAPI (async patterns, Pydantic v2)
