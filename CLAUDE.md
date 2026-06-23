# CLAUDE.md — neo-candy-tela

## Project overview

Standalone repo for the **neo-candy-tela** folder-icon theme — the same folder set as
`erikdubois/surfn-tela` re-based onto the neo-candy-icons fallback.

## Current state

Ships one theme: `usr/share/icons/neo-candy-tela/` — folders only. Packaged as `neo-candy-tela-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/neo-candy-tela/`), `depends=('neo-candy-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits neo-candy-icons. `icon-theme.cache` gitignored.
  Payload reused verbatim from the Surfn counterpart; only Name/Inherits/dir name differ.
