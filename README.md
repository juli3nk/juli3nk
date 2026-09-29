
> Infrastructure I can reason about.

---

## Products

| Project | Description | Stack |
|---------|-------------|-------|
| **[memoria](https://github.com/juli3nk/memoria)** | Sovereign knowledge base for human and AI agent collaboration. Markdown as source of truth, Git for audit, SQLite for search, MCP server for agents. | Go, React, OIDC, FTS5 |
| **[podcd](https://github.com/juli3nk/podcd)** | GitOps controller for single Linux nodes via native systemd units. No Kubernetes required. | Go, systemd |
| **[dotfiles](https://github.com/juli3nk/dotfiles)** | Profile-based dotfiles manager with templating and symlinks. | Go |
| **[daggerverse](https://github.com/juli3nk/daggerverse)** | Reusable Dagger modules and toolchains for CI automation. | Go, Dagger |

---

## Stack

| Layer | Technology |
|-------|------------|
| **Language** | Go |
| **Desktop** | NixOS + Sway ([nixos-modules](https://github.com/juli3nk/nixos-modules)) |
| **Servers** | Debian + Ansible ([system](https://github.com/juli3nk/ansible-collection-system), [container](https://github.com/juli3nk/ansible-collection-container), [ai](https://github.com/juli3nk/ansible-collection-ai)) |
| **CI** | Dagger toolchains, GoReleaser |

---

## Principles

- **Provider-agnostic**: No cloud or vendor lock-in
- **Self-hosted**: Own the data, own the system
- **Composable**: Tools over frameworks
- **Declarative**: Git-tracked, reproducible infrastructure
