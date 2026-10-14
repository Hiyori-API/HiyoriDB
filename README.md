# HiyoriDB

Relational dataset produced by the Hiyori CLI pipeline.

- Profile: per-entry-json
- Anime records: 13719
- Manga records: 2161

Tables: `data/tables/{anime,manga,entity_titles,entity_references}.csv` (see `schema.sql`).
Per-entry JSON: `data/<kind>/<hiyori_id>-<slug>.json`; bulk mirror: `data/<kind>.jsonl`.
