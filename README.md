# escouade-mail-plugins

*Français : [README.fr.md](README.fr.md)*

The **Escouade Mail** (formerly Subagent) plugin for Claude Code. It gives your agent a real mailbox: it writes, reads its threads and replies with its own address, and you approve what it sends.

The plugin brings the Escouade Mail MCP server (`https://api.subagent.fr/mcp`), connected with your key, which Claude Code asks for once and keeps with its own credentials, and the recipes that tell the agent how to use it.

## Install

In Claude Code:

```text
/plugin marketplace add escouade-io/escouade-mail-plugins
/plugin install escouade-mail@escouade-mail
```

Claude Code asks for the key, then open a new session. No key yet? `sign_up` opens a workspace without one: see the French guide.

## Documentation

Guides and the reference of every tool: https://escouade.io/mail/docs (in French).

## Contributing

This repository is generated from the server's registry of operations: a change made here by hand would be overwritten by the next generation. Please open an issue rather than a pull request.

## License

MIT. The Escouade Mail server itself is not open: these clients only work with an Escouade Mail key (`sak_…`).
