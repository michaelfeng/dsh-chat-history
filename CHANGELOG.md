# Changelog

## 2.0.0 — 2026-11-08

Project rename: `dsh-conversation-history` → `dsh-chat-history`.

- Renamed the GitHub repository, npm package name, bundle row id, client module id, locale namespace, Host RPC paths (`/api/chat-history/*`) and the derived cache directory (`cache/chat-history`).
- The sidebar panel, search, locating and context behavior are unchanged.
- Breaking change for existing installations: remove the old **Conversation History** bundle and component first, then install `github:michaelfeng/dsh-chat-history#v2.0.0`. The renamed cache rebuilds once on first open.

## 1.2.0 — 2026-11-07

- Moved the entry point from the in-conversation History tab to a global sidebar panel directly under Plugins (order 5, above Schedules and the More menu), rendered as a main panel.
- The panel icon follows the sidebar row's requested size and theme colour.
- Updated the package description, locale metadata and READMEs for the new placement. Search, locating and context behavior are unchanged.

## 1.1.0 — 2026-10-28

First standalone public release.

- History tab with cross-conversation phrase search and context previews.
- Local dialogue projections with revision checks and persistent cache reuse.
- Shared indexing jobs, progress reporting and bounded requests.
- Exact message anchors and Markdown-aware highlighting.
- English and Simplified Chinese interface.
- Synthetic regression tests and reproducible screenshot fixtures.
