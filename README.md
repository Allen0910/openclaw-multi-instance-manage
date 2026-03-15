# OpenClaw Multi-Instance Management

Multi-instance management system for OpenClaw.

## What is OpenClaw?

OpenClaw 🦞 is an AI Agent Gateway for any operating system, supporting WhatsApp, Telegram, Discord, iMessage, and more. Send messages and get AI agent responses from anywhere. Additional channels like Mattermost can be added via plugins.

## Core Features

- **Multi-Channel Gateway**: Connect WhatsApp, Telegram, Discord, and iMessage through a single Gateway process
- **Plugin Channels**: Add more channels like Mattermost via extensions
- **Multi-Agent Routing**: Isolate conversations by agent, workspace, or sender
- **Media Support**: Send and receive images, audio, and documents
- **Web Control Interface**: Browser dashboard for chat, configuration, session, and node management
- **Mobile Nodes**: Pair iOS and Android nodes with Canvas support

## How It Works

The Gateway is the single source of truth for sessions, routing, and channel connections.

## Quick Start

```bash
# Install OpenClaw
npm install -g openclaw@latest

# Onboard and install daemon
openclaw onboard --install-daemon

# Login to WhatsApp and start Gateway
openclaw channels login
```

## Getting Started

TODO: Add instructions for setting up and using the project.

## Learn More

- [Official Documentation](https://docs.openclaw.ai/zh-CN)
- [GitHub Repository](https://github.com/openclaw/openclaw)
- [Releases](https://github.com/openclaw/openclaw/releases)
