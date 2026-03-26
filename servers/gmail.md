# Gmail MCP Server

Connects Claude to **Gmail** via the Model Context Protocol — using Anthropic's hosted Gmail MCP endpoint.

## What this enables

With this integration, Claude can read, search, and interact with Gmail directly. Useful for automating email workflows, summarizing threads, or triggering actions based on email content.

## Setup

### Prerequisites
- Claude Code installed (`npm install -g @anthropic-ai/claude-code`)
- A Google account connected to Claude.ai

### Configuration

Add the following to your `~/.claude.json` under `mcpServers`:
```json
"gmail": {
  "type": "url",
  "url": "https://gmail.mcp.claude.com/mcp"
}
```

> ℹ️ This uses Anthropic's hosted Gmail MCP server — no self-hosting required. Authentication is handled through your Claude.ai Google account connection.

## Notes

- See `configs/claude.example.json` for a full sanitized config example
