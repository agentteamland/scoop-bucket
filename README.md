# 🪣 AgentTeamLand Scoop Bucket

> Auto-managed Scoop manifest for the [`atl` CLI](https://github.com/agentteamland/cli) (Windows).

This bucket holds a single JSON manifest at `bucket/atl.json`. Goreleaser overwrites it on every git tag in [`agentteamland/cli`](https://github.com/agentteamland/cli) — no manual edits land here. Branch protection is intentionally NOT applied (would block goreleaser's force-push).

## 📚 Documentation

Full docs live at **[agentteamland.github.io/docs](https://agentteamland.github.io/docs/)**.

Most relevant sections:

- [Install `atl` (Scoop section)](https://agentteamland.github.io/docs/guide/install#windows-scoop) — the user-facing install commands
- [Release pipeline](https://agentteamland.github.io/docs/contributing/release-pipeline) — how this bucket gets auto-bumped on every cli tag (the maintainer-facing detail)

## License

MIT.
