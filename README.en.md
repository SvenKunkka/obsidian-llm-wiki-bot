# Obsidian Knowledge Governance Bot

A BotHarness bot inspired by the [LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) pattern for maintaining an Obsidian vault.

- **Ingest:** preserve source material, summarize it, and connect relevant topics, concepts, and entities.
- **Query:** consult the wiki and relevant sources, cite evidence, and identify uncertainty.
- **Lint:** find broken links, orphan notes, duplicates, missing sources, conflicts, and stale claims.
- **Protect:** follow the user's authorization, back up before editing, preserve manual content and Obsidian links, and surface conflicts.

Paste this repository URL into the DSH Bot Market to install. Select and authorize the vault separately; installation does not grant file access or start a governance run. The prompt describes intended behavior; actual capabilities depend on the model, tools, and permissions. Read [SOUL.md](SOUL.md) before use. The bot defaults to Chinese and can respond in the language requested by the user.

This is a community project and is not an official product of Obsidian, DeepSeek, or the LLM Wiki author.
