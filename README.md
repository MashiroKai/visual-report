# visual-report

Nebflow / Stand plugin package — standalone repository for version history.

- **Version:** 1.5.0 (tag `v1.5.0`)
- **Import commit:** `ec6ec0d` (84 files)
- **Import date:** 2026-10-29
- **Content source:** engine seed, `src/main/resources/seed/plugins/visual-report`
  in the Stand monorepo (seed last touched by commit `bd0283a32 (2026-10-29 12:41:09 +0800)`)

> **Known drift at import (2026-10-29).** The runtime instance of this package
> differs from the seed in `Plugin.md` and `plugin.json` — the instance still carries the
> pre-2026-10-21 loader wording. This repository is authoritative on **seed**
> content; the instance-side text is archived in the Stand monorepo as
> `docs/attachments/20261029_plugin-instance-drift-visual-report.patch`.

## Editing

This repository is the place to change the package: commit here, tag releases as
`v<plugin.json version>`, and mirror the result back into the engine seed
(`src/main/resources/seed/plugins/visual-report`) so freshly installed instances receive it.

## Layout

```
plugin.json    manifest (name / version / description)
Plugin.md      package guide, injected as the agent prompt on plugin assignment
skills/        one directory per skill, each with SKILL.md
mcp.json       (optional) MCP server declarations
scripts/       (optional) helper scripts
```
