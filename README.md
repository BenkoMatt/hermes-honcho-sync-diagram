# Hermes + Honcho Multi-Profile Memory Sync

An interactive, dark-themed SVG diagram showing how multiple [Hermes Agent](https://github.com/NousResearch/hermes-agent) profiles can share a single [Honcho](https://honcho.dev) user peer while keeping their own AI peer identities.

## View it

Open `index.html` in any modern browser, or serve it locally:

```bash
python3 -m http.server 8080
# http://localhost:8080
```

## What it illustrates

- All non-isolated Hermes profiles write facts about the **same user** into one Honcho workspace.
- Each profile keeps a **distinct AI peer** for its own self-representation.
- Isolated profiles (e.g. `work`) use built-in memory only and do not connect to the shared Honcho workspace.

## Make it yours

Replace the placeholders in `index.html` with your own values:

- `your-user-peer` → your Honcho user peer name
- `your-workspace` → your Honcho workspace name
- `profile-a` … `profile-f` → your Hermes profile names

## License

MIT
