# Identity and Consciousness (public Org-mode tree)

Public Org-mode mirror of Daniel Bryan Boice's Identity and Consciousness research map, from the Adaptive Philosophy Foundation. This repository contains only public Notion content.

**Sites**

- Public research: https://research.dan.credit
- System: https://system.dan.engineer
- Private Director site: https://private.dan.engineer (Director-only)

Daniel's public identity for this work is [dan.credit](https://dan.credit).

## Layout

- `index.org` — tree index (eight sections, taxonomy, version history)
- `sections/<section-slug>/` — one `.org` file per public Notion page, nested to match branches
- `taxonomy/topics/`, `taxonomy/categories/`, `taxonomy/tags/` — 8 topics, 11 categories, 32 tags
- `versions/version-history.org` — public change log
- `sync-log.org` — dated sync counts (Pacific Time)
- `README.org` — Org-mode copy of this orientation

Each page is org-roam compatible. The `:ID:` property is the dashed Notion page id. Internal links use `[[id:...]]` when the target is in this tree. A `:PRIVATE_TWIN:` / `:PRIVATE_NOTION_ID:` property may name the Director's private working page as plain text; this repository does not include private content.

## Sync

Notion is the source for this pull. An assistant refreshes snapshots and runs `python3 /workspace/orgsync/notion_to_org.py`. The script overwrites generated files and never deletes files, so extra local notes stay in place. This tree and the private tree are separate git repositories.

## Community

The public map is open for anyone who is kind. The Director maintains a banned-list mechanism on the Notion side.
