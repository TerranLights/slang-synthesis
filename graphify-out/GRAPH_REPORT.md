# Graph Report - slang-synthesis  (2026-08-30)

## Corpus Check
- Corpus is ~5,161 words - fits in a single context window. You may not need a graph.

## Summary
- 49 nodes · 70 edges · 8 communities (7 shown, 1 thin omitted)
- Extraction: 97% EXTRACTED · 3% INFERRED · 0% AMBIGUOUS · INFERRED: 2 edges (avg confidence: 0.9)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Corpus/Analysis Index Structure
- Usage-Tier Taxonomy Fields
- Historical/Geographic Context Fields
- Pipeline READMEs & Templates
- Subtitle/Transcript Reliability
- Graphify Tooling Docs
- Per-Language Graphify Scope Rule
- Source Reference Folder

## God Nodes (most connected - your core abstractions)
1. `Source Reliability Guide — Subtitles & Transcripts` - 9 edges
2. `Slang Mechanics Analysis Index` - 8 edges
3. `Historical & Geographic Context Guide` - 8 edges
4. `Slang Corpus Collection Index` - 8 edges
5. `Datasets Language Template Extraction Checklist` - 7 edges
6. `Datasets README` - 6 edges
7. `Language Corpus Template Extraction Checklist` - 6 edges
8. `Usage-Tier & Slang-Type Taxonomy` - 5 edges
9. `Language Corpus README` - 5 edges
10. `Reference-Corpus-Analysis-Synthesis Pipeline` - 4 edges

## Surprising Connections (you probably didn't know these)
- `Corpus Per-Language Scoped graphify-out/ Rule` --semantically_similar_to--> `Per-Language Scoped graphify-out/ Rule`  [INFERRED] [semantically similar]
  language_corpus/_TEMPLATE/00_Extraction_Checklist.md → datasets/_TEMPLATE/00_Extraction_Checklist.md
- `Scope Notes (contemporary/historical, regional variation)` --references--> `Historical & Geographic Context Guide`  [EXTRACTED]
  language_corpus/_TEMPLATE/00_Extraction_Checklist.md → datasets/00_Historical_and_Geographic_Context_Guide.md
- `Slang Corpus Collection Index` --references--> `source_reference/ (reference material)`  [EXTRACTED]
  language_corpus/00_Corpus_Collection_Index.md → README.md
- `Corpus Index Maintenance Rule` --references--> `Slang Mechanics Analysis Index`  [EXTRACTED]
  language_corpus/00_Corpus_Collection_Index.md → datasets/00_Analysis_Index.md
- `Corpus-before-Analysis Prerequisite Rule` --references--> `Slang Corpus Collection Index`  [EXTRACTED]
  datasets/00_Analysis_Index.md → language_corpus/00_Corpus_Collection_Index.md

## Hyperedges (group relationships)
- **Reference-Corpus-Analysis-Synthesis Pipeline Flow** — readme_pipeline_stages, language_corpus_00_corpus_collection_index, datasets_00_analysis_index [EXTRACTED 1.00]
- **Cross-Language Taxonomy Consistency Pattern** — datasets_00_usage_tier_taxonomy, datasets_00_historical_and_geographic_context_guide, language_corpus_00_source_reliability_guide [INFERRED 0.85]
- **Copy-Template-Then-Index Scaffolding Pattern** — datasets__template_00_extraction_checklist, language_corpus__template_00_extraction_checklist, datasets_00_analysis_index [INFERRED 0.85]

## Communities (8 total, 1 thin omitted)

### Community 0 - "Corpus/Analysis Index Structure"
Cohesion: 0.22
Nodes (11): Slang Mechanics Analysis Index, Analysis Folder Convention (datasets/<Language>/), Analysis Index Maintenance Rule, Corpus-before-Analysis Prerequisite Rule, Analysis Status Legend (not started/in progress/complete), Status by Language Table, Slang Corpus Collection Index, Corpus Index Maintenance Rule (+3 more)

### Community 1 - "Usage-Tier Taxonomy Fields"
Cohesion: 0.28
Nodes (9): attested_era Field, Usage-Tier & Slang-Type Taxonomy, Slang-Derivation Types (technical_leak, taboo_inversion, euphemism_chain, phonological_reduction, semantic_shift, borrowing, metaphor_productivity, morphological_play, register_inversion), Dot-Notation Subcategory Extensibility Rule, Taxonomy Maintenance Rule (promote 2+ language subcategories), Usage Tiers (core, formal, colloquial, technical, regional, literary, archaic, taboo, slang), analysis/ Directory (mechanics findings shards), established/ Directory (baseline vocab/grammar shards) (+1 more)

### Community 2 - "Historical/Geographic Context Fields"
Cohesion: 0.32
Nodes (8): Historical & Geographic Context Guide, attested_region Field, geographic_scope Field, Correction/Revision Maintenance Rule, Null-Is-Legitimate Rule (no guess-filling), Datasets Language Template Extraction Checklist, revision_history Field (no silent overwrite), synthesized/ Directory (derived in-universe slang, provisional)

### Community 3 - "Pipeline READMEs & Templates"
Cohesion: 0.38
Nodes (7): Datasets README, Language Corpus Template Extraction Checklist, Scope Notes (contemporary/historical, regional variation), Language Corpus README, Reference-Corpus-Analysis-Synthesis Pipeline, slang-synthesis Project, source_reference/ (reference material)

### Community 4 - "Subtitle/Transcript Reliability"
Cohesion: 0.47
Nodes (6): Source Reliability Guide — Subtitles & Transcripts, AI-Transcription Confident-Wrongness Risk (for slang), Source Reliability Maintenance Rule, Platform Reliability Registry, source_type Field, transcription_confidence Field (verified/plausible_unverified/low_confidence)

### Community 5 - "Graphify Tooling Docs"
Cohesion: 0.50
Nodes (4): graphify-out/graph.json, graphify-out/GRAPH_REPORT.md, graphify (knowledge graph tool), graphify-out/wiki/index.md

### Community 6 - "Per-Language Graphify Scope Rule"
Cohesion: 0.67
Nodes (3): Sharded JSON Scaling Rule (established/analysis/synthesized dirs), Per-Language Scoped graphify-out/ Rule, Corpus Per-Language Scoped graphify-out/ Rule

## Knowledge Gaps
- **9 isolated node(s):** `graphify-out/graph.json`, `graphify-out/GRAPH_REPORT.md`, `graphify-out/wiki/index.md`, `Source Files (language reference books)`, `slang-synthesis Project` (+4 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Datasets README` connect `Pipeline READMEs & Templates` to `Corpus/Analysis Index Structure`, `Usage-Tier Taxonomy Fields`, `Historical/Geographic Context Fields`?**
  _High betweenness centrality (0.274) - this node is a cross-community bridge._
- **Why does `Source Reliability Guide — Subtitles & Transcripts` connect `Subtitle/Transcript Reliability` to `Usage-Tier Taxonomy Fields`, `Pipeline READMEs & Templates`?**
  _High betweenness centrality (0.201) - this node is a cross-community bridge._
- **Why does `Historical & Geographic Context Guide` connect `Historical/Geographic Context Fields` to `Usage-Tier Taxonomy Fields`, `Pipeline READMEs & Templates`?**
  _High betweenness centrality (0.184) - this node is a cross-community bridge._
- **What connects `graphify-out/graph.json`, `graphify-out/GRAPH_REPORT.md`, `graphify-out/wiki/index.md` to the rest of the system?**
  _9 weakly-connected nodes found - possible documentation gaps or missing edges._