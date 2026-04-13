# Sanjay's Second Brain — Antigravity Context

This workspace is an Obsidian-based personal knowledge management system. It uses a set of Antigravity skills located in the `skills/` directory to manage knowledge ingestion, synthesis, and retrieval.

## Quick Orientation

1. **Vault Root**: The current directory (`d:\Github\SanjaySecondBrain`).
2. **Skills**: Local Antigravity skills are in `skills/*.skill`.
3. **Core Files**:
   - `index.md`: The central directory of all pages.
   - `log.md`: Chronological log of all wiki operations.
   - `.manifest.json`: Tracks ingested sources and their corresponding wiki pages.
   - `_meta/taxonomy.md`: Controlled vocabulary for tags.

## Available Skills

You can trigger these skills by using the following phrases or their variations:

- **"set up wiki" / "initialize"** → `skills/wiki-setup.skill`
- **"ingest" / "add to wiki"** → `skills/wiki-ingest.skill`
- **"wiki status" / "check health"** → `skills/wiki-status.skill`
- **"query wiki" / "ask about"** → `skills/wiki-query.skill`
- **"cross-link" / "connect pages"** → `skills/cross-linker.skill`
- **"fix tags" / "normalize"** → `skills/tag-taxonomy.skill`
- **"update from project"** → `skills/wiki-update.skill`

## Operating Principles

- **Deduplication**: Never create duplicate pages. Merge new info into existing ones.
- **Wikilinks**: Always use `[[wikilink]]` syntax to connect knowledge.
- **Metadata**: Every page must have frontmatter (title, category, tags, sources).
- **Provenance**: Distinguish between extracted facts, inferences, and ambiguous info.
