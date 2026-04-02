# Baton AI — Context Handoff for Repo-Native Agents

> *Generational context transfer. Agents hand off to agents seamlessly.*

## What It Is

Baton implements the Universal Handoff Protocol for repo-native agents. When one agent finishes (or hits a boundary), it passes full context to the next — conversation history, knowledge, decisions, and intention. No information loss. No starting over.

## Key Features

- 🔄 **Seamless handoff**: Agent A → Agent B with full context
- 🔒 **HMAC-signed**: Every handoff is cryptographically verified
- 🎚️ **Privacy levels**: Public, shared, private
- 📋 **Handoff object**: Standardized context format (conversation, knowledge, files, decisions)
- 🤝 **Trust model**: Agents verify each other before accepting handoffs

## Use Cases

- Claude Code → Cocapn: Code writing hands off to long-term maintenance
- PersonalLog → BusinessLog: Personal context flows to work context
- MakerLog → FishingLog: Coding agent hands to domain specialist
- Human → Agent: Half-finished task completed by agent
- Agent → Human: Agent escalates decision boundary to captain

## Status

📝 Handoff module implemented in makerlog-ai/src/a2a/handoff.ts. This repo is the standalone library.

Author: Superinstance

## License

MIT — Built with ❤️ by [Superinstance](https://github.com/superinstance) & [Lucineer](https://github.com/Lucineer) (DiGennaro et al.)
