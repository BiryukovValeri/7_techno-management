# Introduction for ChatGPT

We have created a public source repository for the seven management technologies:

`https://github.com/BiryukovValeri/7_techno-management`

Working branch: `codex/site-factory`.

## What was done

The seven source folders from the Mac were inventoried with SHA-256 and copied without rewriting source documents or overwriting conflicting variants. The repository contains 848 content files with checksum parity against the Mac sources. System `.DS_Store` files were excluded.

Identical files used in several self-contained delivery packages were preserved at their required paths. Git stores identical content as one blob, so this does not require destructive package cleanup.

## Where to start

Start with:

`technologies/01_UM_DA/`

For Управленческая Математика / Управленческая Точность, the canonical product documents are present:

- `30 Документация/Управленческая_Математика_УМ_Документация_08_Продуктовая_архитектура.docx`
- `30 Документация/Управленческая_Математика_УМ_Документация_09_Методика_проведения_продуктов.docx`

Do not claim they are missing. Read them directly before making conclusions about the four products.

## Repository navigation

Each technology is isolated under `technologies/01...07` and has a `MANIFEST_SHA256.txt` file. The overall corpus and cleanup audit is in `docs/SOURCE_CORPUS_IMPORT_AUDIT.md`.

The separate repository `BiryukovValeri/claudecode` remains the site-production control repository. Before site work there, read in order:

1. `AGENTS.md`;
2. `PROJECT_STATE.md`;
3. `70 Site/SITE_ARCHITECTURE_AND_PRODUCTION_PROTOCOL_v1.0.md`;
4. the direct current task and current technology Source Lock;
5. current V2 instance files only when the task explicitly selects that route.

See `docs/CLAUDECODE_SITE_MATERIALS_AUDIT.md` for the complete authority and navigation map.

## Mandatory boundary

Do not start designing a website merely because site drafts or old packages are present. First establish the current object, governing execution route, authoritative product truth, and source lineage. Historical site packages may be evidence, but they are not automatically current authority.
