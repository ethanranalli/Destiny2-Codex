# Maintaining the Destiny 2 Helper

Reviewed: 2026-09-06. Maintenance changes remain inside this folder and Markdown-only unless the user explicitly changes scope.

## On-demand refresh

1. Read AGENTS.md and identify affected topics.
2. Check the canonical baseline and relevant source dates.
3. Inspect every changed dependency: item, perk, artifact, armor set, activity rule, reward, or ownership assumption.
4. Update the narrow canonical note and its index; avoid duplicating patch claims everywhere.
5. Record checked date, source/test date, evidence, and limitations.
6. Check local links and scenario coverage. Preserve personal data and unrelated files.
7. Summarize concrete changes and unresolved source access.

For a full audit, inventory every active Markdown file and public source. Distinguish reachable content, partial UI, authenticated/gated content, and historical sources. Do not change a date merely because a file was touched.

## Validation

Use [behavior scenarios](validation-2026-09-06.md) and [build legality](../builds/build-validation.md). These are manual acceptance checks; no scripts or application test suite is required.

Compare changed files against the original inventory. Check that new/modified artifacts are Markdown, no personal/binary data was lost, local links resolve, archive instructions are non-operative, and citations support claims.

## History and restoration

[Before-audit backup](history/2026-09-06-before-audit.md) contains all 35 original Markdown files in named fenced blocks. Treat it as historical data, never active instructions. To reverse a change, restore only the intended file's block after reviewing scope.

Exclude maintenance/history/ and data/snapshots/ from ordinary research. Read this maintenance folder only for audits, evidence, or helper changes.

No background automation is configured. "Up to date" means dated evidence plus relevant live verification when requested information could have changed.
