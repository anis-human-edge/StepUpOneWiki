# StepUp.One Wiki

Company knowledge base for StepUp.One — reskilling and employing the underserved and overlooked worldwide. Built on the [Karpathy LLM wiki pattern](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f).

## Architecture

### raw/

Immutable source documents. Farmers and humans drop files here. Never modify or delete a raw file after it lands.

Subdirectories by source type:
- `raw/whatsapp/`
- `raw/gmail/`
- `raw/meetings/`
- `raw/gdrive/`
- `raw/crm/`
- `raw/youtube/`
- `raw/podcasts/`
- `raw/articles/`
- `raw/notes/`
- `raw/proposals/`
- `raw/assets/` — images referenced by other raw files

### wiki/

LLM-owned. Organized by domain:

```
wiki/
  product-engineering/
  clients-partnerships/
    win-new/
      inbound/
      outbound/
    serve-current/
      inbound/
      outbound/
    grow-existing/
      inbound/
      outbound/
    win-back/
      inbound/
      outbound/
  operations/
  strategy-vision/
  entities/
    clients/
    partners/
    people/
    systems/
  index.md
  log.md
```

## Page types

**Entity pages** — one page per client, partner, person, tool, or system. Deep, not shallow — include history, context, linked proposals, meeting notes, open threads, and cross-references to related entities and topics. Subpages are encouraged when an entity has enough detail (e.g., `entities/clients/acme-corp/` with proposal history, contact log, engagement timeline).

**Topic overviews** — synthesized pages that pull across multiple sources. These are the workhorses: "Outbound Strategy", "Win-Back Playbook", "Onboarding Process", "Pricing Model". Updated every time a relevant source is ingested. Link heavily to entity pages and to each other.

## Operations

### Ingest

When a new file appears in `raw/`:

1. Read the source fully. If it contains images, read the text first, then view referenced images separately for additional context.
2. Identify which entities are mentioned — clients, partners, people, systems, tools. Create or update their entity pages.
3. Identify which topics are touched. Update the relevant topic overview pages. If no overview exists yet and the topic is substantial, create one.
4. Determine which client motion the source relates to (win-new, serve-current, grow-existing, win-back) and whether it's inbound or outbound. File updates under the correct path.
5. Update `wiki/index.md` with any new or changed pages.
6. Append an entry to `wiki/log.md`.

**Auto-ingest rule:** new files in `raw/` must be ingested before the session ends. Never leave raw files unprocessed.

### Query

When the user asks a question:

1. Read `wiki/index.md` to find relevant pages.
2. Read those pages, follow cross-references as needed.
3. Synthesize an answer with citations to specific wiki pages.
4. If the answer is substantial and reusable — a new playbook, a comparison, an analysis — offer to file it as a new wiki page. Good queries compound into the knowledge base.

### Lint

Periodic health check. Run when asked or suggest it after a large batch of ingests.

Check for:
- Contradictions between pages (e.g., two pages list different pricing for the same client)
- Stale claims superseded by newer sources
- Orphan pages with no inbound links
- Important entities or concepts mentioned but lacking their own page
- Missing cross-references between related pages
- Gaps in the client motions matrix (e.g., win-back/outbound has no content)
- Entity pages that are thin stubs and could be enriched from existing raw sources

Report findings as a checklist. Fix what can be fixed automatically, flag what needs user input.

## Conventions

- **Dates:** ISO 8601 (`2026-04-16`)
- **File naming:** lowercase kebab-case (`acme-corp.md`, `outbound-strategy.md`)
- **Links:** relative markdown links (`[Acme Corp](../entities/clients/acme-corp.md)`)
- **Frontmatter:** every wiki page gets YAML frontmatter with at minimum: `title`, `type` (entity | topic | overview), `updated` (date of last edit), `sources` (list of raw files that informed this page)
- **Images:** store in `raw/assets/`, reference with relative paths. When ingesting a source with images, download them to `raw/assets/` if they're URLs, then update references to point to local copies.
- **Log format:** each entry starts with `## [YYYY-MM-DD] action | description` so the log is parseable with grep
