# Contributing

Thanks for your interest in contributing to Awesome Agent Skills Israel!

## What belongs on this list

Skills that are **relevant to people living in or visiting Israel**. This includes:

- Skills that interact with Israeli platforms and services
- Skills that handle Hebrew language input/output
- Skills that solve problems specific to life in Israel (bureaucracy, local commerce, security)
- Skills built around services widely used in Israel, even if the platform is global

This is **not** a list of developer tools, coding utilities, or general-purpose skills. If your skill works equally well anywhere in the world and has no Israeli context, it probably belongs on a different list.

## Entry format

Each entry must follow this format:

```
- [Name](https://github.com/owner/repo) - Short, one-sentence description ending with a period.
```

Rules:

- Description must be a single sentence, starting with a capital letter and ending with a period.
- Description should explain what the skill does, not how it works.
- No trailing whitespace.
- English only, even if the skill supports Hebrew.
- Alphabetical order within each category.

## Quality bar

Before submitting, make sure the skill:

- **Has a `SKILL.md` file** in the standard Agent Skills format (YAML frontmatter with name and description, followed by instructions).
- **Actually works** - it should be installable and functional, not a placeholder or stub.
- **Is Israel-relevant** - see "What belongs on this list" above.
- **Has a public repository** with a README explaining what it does and how to install it.
- **Is not a duplicate** - search the list first.

## Suggesting a skill

If you know of a skill that should be on this list but you're not the author, [open an issue](../../issues/new?template=suggest-skill.md) using the suggestion template.

If you want to suggest a tool or resource that isn't an Agent Skill but is useful for building Israeli skills, [open an issue](../../issues/new?template=suggest-tool.md) using the tool suggestion template.

## Pull request process

1. **One entry per PR.** Don't batch multiple additions.
2. **Search first.** Make sure the skill isn't already listed.
3. **Use the correct format.** See entry format above.
4. **Place it alphabetically** within the correct category.
5. **Write a clear PR title** like "Add Rav-Kav Balance Checker to Transport & Navigation".

## Proposing a new category

If your skill doesn't fit any existing category, mention it in the PR description. Categories are added when there are at least two skills that fit them.
