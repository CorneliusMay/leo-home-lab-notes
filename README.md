# leo-home-lab-notes

Personal, hands-on notes, setups, and implementations from the HomeLab
(Coventry, UK). Covers the tools and services I run daily on Ubuntu 24.04 LTS:
the Hermes Agent, documentation, self-hosting, and hardware I prototype with.

> This repo is a personal working notes repo — not a library of Python
> modules. For the source of the Hermes Agent itself (and other software
> projects), see the dedicated project repositories under
> `~/GitHub/`.

## What's inside

| Path | Purpose |
|---|---|
| `[projects/](projects/)` | One folder per project: code, docs, configs, and a `README.md` per project explaining the goal, build/run steps, and design notes. |
| `[docs/](docs/)` | Technical write-ups and reference notes: homelab setups, toolchains, lessons learned. |
| `[assets/](assets/)` | Schematic diagrams, system architecture drawings, and reference images. |

## How I work

- **Every project** gets a `README.md` that states the goal, how to build/run
  it, and what each part of the code does.
- **Code is documented** line by line where it isn't self-explanatory.
- **Everything** goes through git for version control and GitHub for storage.
- **Backups** are redundant: local (`obsidian-stack`), off-site (Git), and
  encrypted (external drive) — details in
  `#[Areas]/Encrypted-backups.md` and the Homelab Setup note.

## Tools / Setup quick reference

| Tool | Purpose |
|---|---|
| `gh` | GitHub CLI (`~/.local/bin/gh`, version 2.67.0) |
| `hermes` | The Hermes Agent CLI itself |
| `ssh` (key: `~/.ssh/id_ed25519_github`) | GitHub push/pull over SSH |
| `astral-sh/uv` | Python package & environment management |

## Further reading

- [System-Index.md](System-Index.md) — quick map of the vault
- [Homelab-Setup.md](Areas/Homelab-Setup.md) — how the HomeLab is wired
- [Encrypted-backups.md](Areas/Encrypted-backups.md) — backup strategy
- [Obsidian-Weekly-Capture.md](Areas/Obsidian-Weekly-Capture.md) — capture workflow

## License

Personal notes. All rights reserved unless a file states otherwise.
