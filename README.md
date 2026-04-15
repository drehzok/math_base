# Math LLM Wiki

A persistent, locally-stored personal math knowledge base managed by Gemini CLI.

## Directory Structure

- `01-raw-sources/`: Immutable storage for raw math notes, textbooks, and snippets.
- `02-wiki/`: Structured, interlinked mathematical concepts (Definitions, Theorems, Proofs, Examples).
- `03-agents/`: Specialized subagents for wiki management.

## Core Protocols

Defined in `GEMINI.md`:
- **Mathematical Rigor:** Clear separation of concepts.
- **LaTeX Formatting:** Standard math notation using `$` and `$$`.
- **Interlinking:** Obsidian-style `[[Wikilinks]]`.
- **Prerequisite Tracking:** Every concept links to its foundational requirements.

## Agents

- **Ingest Math Agent (`03-agents/ingest-math.md`):** Synthesizes raw sources into wiki pages.
- **Lint Math Agent (`03-agents/lint-math.md`):** Maintains graph integrity by finding broken links and missing proofs.
