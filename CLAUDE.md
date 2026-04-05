# Awesome Solopreneur Skills

## About

This is an open-source curated + original skill collection for solopreneurs.
All comments, docs, and code should be in English (repo has LICENSE file).

## Adding Skills

When the user shares a skill (URL or name), follow this process:

1. **Research** — Fetch the repo/link to understand what it does
2. **Classify** — Determine:
   - **Platform:** `Claude Code` or `OpenClaw` (determines which section in README)
   - **Type:** `Skill` (installable skill), `Plugin` (extension/integration), or `CLI` (command-line tool)
3. **Categorize** — Pick the best function category:
   - `Build` — Planning, building, shipping, maintaining products
   - `Marketing` — SEO, ads, analytics, sales, pricing, landing pages
   - `Content` — Writing, social media, replies, scheduling, visuals
   - `Design` — UI/UX, branding, visual design
   - `Operations` — Automation, scheduling, customer support, finance, project management
4. **Add to README.md** — Insert a row in the correct platform section + category table:
   ```
   | [Name](url) | One-line description | `Type` |
   ```
5. **If Original** — Also add the skill source code under `skills/claude-code/` or `skills/openclaw/`. Strip private config (env vars, API keys, agent-specific logic) from the open-source version.
6. **Commit and push**

## Repo Structure

```
README.md              — Main page, skills listed by function category
CONTRIBUTING.md        — Contribution guidelines
LICENSE                — MIT
skills/
  claude-code/         — Original Claude Code skills (source code)
  openclaw/            — Original OpenClaw skills (source code)
```

## Rules

- One skill per table row, keep descriptions under one line
- If a skill fits multiple categories, pick the primary one
- Empty categories use a placeholder row: `| — | — | — |`
- Remove placeholder row when adding the first real skill to a category
