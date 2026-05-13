# Maindex Expert for OpenClaw

Full-fidelity memory for AI agents who demand precision.

[Website](https://maindex.io) | [Help & FAQ](https://maindex.io/help) | [Dashboard](https://maindex.io/dashboard)

This plugin connects OpenClaw to **Maindex Expert** — the complete knowledge graph API with 14 tools and 5 MCP resources (all prefixed with `maindex_`):

### Memory Management
- `maindex_memory_keep` — create a memory
- `maindex_memory_update` — revise with full history
- `maindex_memory_forget` — soft-delete
- `maindex_memory_supersede` — atomic replace with history chain
- `maindex_memory_bulk_keep` — batch create (up to 100)
- `maindex_memory_bulk_update` — batch tag/status/collection ops

### Retrieval
- `maindex_memory_search` — full-text, semantic, and hybrid search
- `maindex_memory_list` — structured filter and browse
- `maindex_memory_recall` — get by ID

### Graph & Organization
- `maindex_memory_associate` — create typed links between memories
- `maindex_memory_get_related` — discover connections
- `maindex_collection_manage` — create, update, and manage collections
- `maindex_collection_unlock` — unlock passphrase-protected collections

### System
- `maindex_system_report_bug` — report issues to the Maindex team

### Resources
- `memory://tags`, `memory://collections`, `memory://recent`, `memory://relation-types`, `memory://sessions`

## Installation

```bash
npm install @maindex/openclaw-expert-plugin
```

## Configuration

The plugin supports two authentication modes:

- **OAuth** (default) — browser-based sign-in via [maindex.io](https://maindex.io)
- **API Key** — manual key configuration

## Looking for Simplicity?

If you prefer a streamlined 4-tool surface that handles retrieval strategy and synthesis automatically:

- [openclaw-smart-plugin](https://github.com/maindexapp/openclaw-smart-plugin) — available in the OpenClaw Plugin Registry

## Learn More

- [maindex.io](https://maindex.io)
- [Help & FAQ](https://maindex.io/help)
