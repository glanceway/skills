# Glanceway Skills

AI agent skills for [Glanceway](https://glanceway.app).

## Available Skills

| Skill                                                  | Description                                                                                                                                    |
| ------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| [glanceway-source](./skills/glanceway-source/SKILL.md) | Use when creating a Glanceway source plugin. Covers development guide, API reference, manifest schema, source lifecycle, and code conventions. |

## Installation

```bash
npx skills add glanceway/skills
```

Install a specific skill:

```bash
npx skills add glanceway/skills --skill glanceway-source
```

## What is Glanceway?

Glanceway is a macOS menu bar app that aggregates information from multiple sources — Hacker News, GitHub, Reddit, RSS feeds, stock prices, crypto, and more — all in one glance. Sources are JavaScript plugins that periodically fetch data and emit items for display.

## License

MIT
