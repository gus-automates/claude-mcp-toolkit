# Claude MCP Toolkit

A collection of real-world **Model Context Protocol (MCP)** server configurations and Claude agent tooling setups — built to connect Claude to live business workflows.

## What is MCP?

The [Model Context Protocol](https://modelcontextprotocol.io) is an open standard by Anthropic that lets Claude connect to external tools and services — think of it as a plugin system for AI agents. Instead of copy-pasting data into a chat, Claude can directly read, write, and act on real systems.

## What's in this repo

| Folder | Description |
|---|---|
| `servers/n8n` | MCP integration with n8n for workflow automation |
| `servers/gmail` | Connecting Claude to Gmail via MCP |
| `servers/google-calendar` | Claude + Google Calendar for scheduling workflows |
| `configs/` | Sanitized example config files for Claude Code setup |

## Tools & Stack

- **Claude Code** — Anthropic's CLI for agentic coding
- **MCP servers** — n8n, Gmail, Google Calendar
- **Node.js / npm** — runtime and package management
- **Windows 11 + PowerShell** — primary dev environment

## Why I built this

I'm using Claude as a core part of internal business automation at a real company — connecting it to tools like QuickBooks Online, Google Workspace, and workflow engines. This repo documents the agent tooling layer that makes those integrations possible.

---

*More integrations being added as they're built.*
