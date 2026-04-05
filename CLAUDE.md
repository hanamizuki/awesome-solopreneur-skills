# Awesome Solopreneur Skills

## About

This is a curated collection of AI agent skills for solopreneurs.
All comments, docs, and code should be in English (repo has LICENSE file).

## Adding Skills

When the user shares a skill (URL or name), follow this process:

1. **Research** — Fetch the repo/link to understand what it does
2. **Classify** — Determine:
   - **Platform:** `Claude Code` or `OpenClaw` (determines which section in README)
   - **Type:** `Skill` (installable skill), `Plugin` (extension/integration), or `CLI` (command-line tool)
   - **Provider:** GitHub org or username (e.g. anthropics, gstack, stripe)
3. **Categorize** — Pick the best function category:
   - `Build` — Planning, building, shipping, maintaining products
   - `Marketing` — SEO, ads, analytics, sales, pricing, landing pages
   - `Content` — Writing, social media, replies, scheduling, visuals
   - `Design` — UI/UX, branding, visual design
   - `Operations` — Automation, scheduling, customer support, finance, project management
4. **Add to README.md** — Insert a row in the correct platform section + category table:
   ```
   | [name](url) | `Type` Description | provider |
   ```
5. **Commit and push**

## Rules

- One skill per table row, keep descriptions under one line
- Type badge goes at the start of the Description column
- If a skill fits multiple categories, pick the primary one
- Empty categories use a placeholder row: `| — | — | — |`
- Remove placeholder row when adding the first real skill to a category
- Links should point to GitHub when possible
