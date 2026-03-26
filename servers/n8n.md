
# n8n MCP Server

Connects Claude to **n8n** — an open-source workflow automation tool — via the Model Context Protocol.

## What this enables

With this integration, Claude can trigger and interact with n8n workflows directly from a conversation or agent task. This is useful for automating business processes without leaving the Claude interface.

## Setup

### Prerequisites
- Claude Code installed (`npm install -g @anthropic-ai/claude-code`)
- n8n instance running (local or cloud)
- n8n MCP server configured

### Configuration

Add the following to your `~/.claude.json` under `mcpServers`:
```json
"n8n": {
  "type": "url",
  "url": "YOUR_N8N_MCP_SERVER_URL"
}
```

> ⚠️ Never commit real URLs or tokens — use environment variables or a local config file excluded by `.gitignore`.

## Notes

- See `configs/claude.example.json` for a full sanitized config example
