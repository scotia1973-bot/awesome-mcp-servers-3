# Contributing to Awesome MCP Servers

Thanks for helping curate the MCP ecosystem. Quick rules to keep this list useful and rank-worthy.

## Adding a new server

1. **It must work.** Install it and confirm at least one tool call succeeds.
2. **It must be public.** A public repo or registry entry — no private/closed-beta drops.
3. **Place it in the most specific category.** Don't dump everything in "Developer tools."
4. **One sentence, present tense.** Describe what the server *does*, not what it *is*. Good: "Postgres read access with schema introspection." Bad: "A Postgres MCP server."
5. **No marketing language.** No "blazing fast," "production-ready," "best-in-class." Just say what it does.

## Alphabetical within each category

Servers are listed alphabetically inside each section. Don't reorder by personal preference.

## Removing a server

Open a PR if a server has been unmaintained for 12+ months, the repo is archived, or it no longer works. Link the evidence.

## Style

- Use the format: `[server-name](repo-url) — Description ending in a period.`
- Repo URL points to the source, not a marketing page.
- Lowercase server names unless the project capitalizes them.

## Reliability data

This list intentionally does **not** track per-server reliability scores, last-checked timestamps, or version data — that lives at [MCPfinder.org](https://mcpfinder.org) where it can be updated automatically. PRs that try to inline that data here will be asked to move it upstream.

## What we don't accept

- Forks of existing servers with no meaningful changes.
- "Coming soon" or placeholder repos.
- Servers that wrap a single REST call with no added value.
- Submissions of your own server *without disclosure* — disclose in the PR description; we don't reject self-submissions, we just want it on the record.
