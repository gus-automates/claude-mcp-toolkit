# Google Calendar MCP Server

Connects Claude to **Google Calendar** via the Model Context Protocol — using Anthropic's hosted Google Calendar MCP endpoint.

## What this enables

With this integration, Claude can read, create, and manage calendar events directly. Useful for scheduling automation, summarizing upcoming meetings, or building workflows that react to calendar activity.

## Setup

### Prerequisites
- Claude Code installed (`npm install -g @anthropic-ai/claude-code`)
- A Google account connected to Claude.ai

### Configuration

Add the following to your `~/.claude.json` under `mcpServers`:
```json
"google-calendar": {
  "type": "url",
  "url": "https://gcal.mcp.claude.com/mcp"
}
```

> ℹ️ This uses Anthropic's hosted Google Calendar MCP server — no self-hosting required. Authentication is handled through your Claude.ai Google account connection.

## Notes

- See `configs/claude.example.json` for a full sanitized config example
