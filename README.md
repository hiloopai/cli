> [!WARNING]
> **Deprecated — this repository is archived.** The `hiloop` CLI distributed here is no longer
> developed or released. v0.18.1 (2026-08-16) is the final release. Existing releases and binaries
> stay available for reference but are unsupported, and the commands and installer below may no
> longer work against the hiloop service.

# hiloop CLI

The `hiloop` command-line interface — snapshottable, forkable agent sandboxes with tree-native
observability.

This repository is the **public release home** for the CLI: every release publishes prebuilt
binaries and a `curl | sh` installer here. The CLI is built from the hiloop API contract; this repo
hosts the released artifacts.

## Install

```sh
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/hiloopai/cli/releases/latest/download/hiloop-cli-installer.sh | sh
```

Prebuilt binaries are published for macOS and Linux (x86_64 + aarch64) on each
[release](https://github.com/hiloopai/cli/releases).

## Docs

Full documentation, including the CLI reference, lives at **[docs.hiloop.ai](https://docs.hiloop.ai)**.