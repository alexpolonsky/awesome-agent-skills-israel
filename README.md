# Awesome Agent Skills Israel

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> A curated list of Agent Skills for navigating life in Israel - from finding a pharmacy to tracking geopolitical risks.

[Agent Skills](https://github.com/anthropics/skills) are reusable instruction bundles for AI coding agents and AI assistants (Claude, OpenClaw, GitHub Copilot, Cursor, etc.). Each skill lives in a folder with a `SKILL.md` file that the agent loads on demand.

This list focuses on **skills relevant to people living in or visiting Israel** - local platforms, Israeli services, Hebrew-language tools, and anything that helps an AI assistant operate in an Israeli context.

Looking for developer-focused agent skills? See [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) and [heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills).

## Contents

- [Health & Pharmacy](#health--pharmacy)
- [Food & Restaurants](#food--restaurants)
- [Language & Localization](#language--localization)
- [Security & Alerts](#security--alerts)
- [Libraries & Reading](#libraries--reading)
- [Transport & Navigation](#transport--navigation)
- [Government & Bureaucracy](#government--bureaucracy)
- [Shopping & E-Commerce](#shopping--e-commerce)
- [Real Estate](#real-estate)
- [Finance & Banking](#finance--banking)
- [News & Media](#news--media)
- [Jewish Calendar & Holidays](#jewish-calendar--holidays)
- [Utilities & Home Services](#utilities--home-services)

### Legend

Skills that need extra setup beyond installation are tagged:

- `API key required` - Requires registering for an API key or account.
- `Browser tool required` - Requires browser automation in the agent.
- `MCP server required` - Requires connecting to an external MCP endpoint.

## Health & Pharmacy

- [Clalit Pharm Search](https://github.com/tomron/agent-skill-clalit-pharm-search) - Search medications and check real-time stock availability at Clalit (כללית) pharmacies across Israel.
- [Maccabi Pharm Search](https://github.com/alexpolonsky/agent-skill-maccabi-pharm-search) - Search medications and check real-time stock availability at Maccabi pharmacy branches across Israel.

## Food & Restaurants

- [Ontopo](https://github.com/alexpolonsky/agent-skill-ontopo) - Search Israeli restaurants, check table availability across date ranges, view menus, and get booking links via Ontopo.
- [Wolt Orders](https://github.com/openclaw/skills/tree/main/skills/dviros/wolt-orders) - Discover restaurants, place orders, track deliveries, and contact support on Wolt. `Browser tool required`

## Language & Localization

- [Hebrew Nikud](https://github.com/openclaw/skills/tree/main/skills/shaharsha/hebrew-nikud) - Hebrew vowel points reference for AI agents covering verb conjugations, dagesh rules, gender suffixes, and homographs.
- [Video Subtitles](https://github.com/openclaw/skills/tree/main/skills/ngutman/video-subtitles) - Generate SRT subtitles from video with Hebrew transcription via ivrit.ai, English via Whisper, and translation support.

## Security & Alerts

- [StrikeRadar](https://github.com/alexpolonsky/agent-skill-strikeradar) - Monitor US-Iran strike probability with real-time signals from news, flights, oil prices, connectivity, and prediction markets.

## Libraries & Reading

- [Libby Book Monitor](https://github.com/alexpolonsky/agent-skill-libby-book-monitor) - Track when books get added to your Libby/OverDrive library with watchlists, multi-library profiles, and notifications.

## Transport & Navigation

- [Railil](https://github.com/openclaw/skills/tree/main/skills/lirantal/skill-railil) - Search Israel Rail train schedules between stations with fuzzy search, date/time filtering, and multiple output formats.

## Government & Bureaucracy

*Contributions welcome! See [suggesting a skill](CONTRIBUTING.md#suggesting-a-skill).*

## Shopping & E-Commerce

- [Salai MCP](https://github.com/openclaw/skills/tree/main/skills/idoziv/salai-mcp) - Israeli grocery price comparison, cross-retailer search, cart management, and store discovery via Salai. `API key required`

## Real Estate

*Contributions welcome! See [suggesting a skill](CONTRIBUTING.md#suggesting-a-skill).*

## Finance & Banking

- [Morning (GreenInvoice)](https://github.com/openclaw/skills/tree/main/skills/k0renn/morning-green-invoice) - Create and manage clients, items, invoices, receipts, and quotes via Morning accounting platform. `API key required`

## News & Media

*Contributions welcome! See [suggesting a skill](CONTRIBUTING.md#suggesting-a-skill).*

## Jewish Calendar & Holidays

*Contributions welcome! See [suggesting a skill](CONTRIBUTING.md#suggesting-a-skill).*

## Utilities & Home Services

- [Arbox Auto-Booking](https://github.com/WolfikOz/arbox-auto-booking) - Automatically book fitness classes on Arbox-powered gyms the moment booking opens, with schedule configuration, monthly limit tracking, and dry-run support.

## What is an Agent Skill?

Agent Skills use **progressive disclosure**:

1. **Discovery** - The agent sees only the skill's name and description at startup.
2. **Activation** - When the user's request matches, the agent loads the full `SKILL.md` into context.
3. **Execution** - The agent follows the instructions, optionally running scripts or loading reference files.

A typical skill folder looks like this:

```
my-skill/
  SKILL.md          # Name, description, and step-by-step instructions
  scripts/          # Optional helper scripts
  references/       # Optional data files or documentation
```

To learn more, see the [Anthropic skills repo](https://github.com/anthropics/skills) and the [Vercel skills registry](https://github.com/vercel-labs/skills).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the entry format, quality bar, and PR process.

## Related Lists

- [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) - Developer-focused agent skills.
- [heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills) - General agent skills collection.
- [alexpolonsky/agent-skills](https://github.com/alexpolonsky/agent-skills) - Installable skills registry with `npx skills add`.
