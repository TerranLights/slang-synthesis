# Graph Report - slang-synthesis  (2026-08-30)

## Corpus Check
- Corpus is ~179 words - fits in a single context window. You may not need a graph.

## Summary
- 6 nodes · 5 edges · 2 communities (1 shown, 1 thin omitted)
- Extraction: 60% EXTRACTED · 40% INFERRED · 0% AMBIGUOUS · INFERRED: 2 edges (avg confidence: 0.7)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Graphify Tooling Docs
- Project Corpus Overview

## God Nodes (most connected - your core abstractions)
1. `graphify (knowledge graph tool)` - 4 edges
2. `slang-synthesis project` - 2 edges
3. `graphify-out/graph.json` - 1 edges
4. `graphify-out/GRAPH_REPORT.md` - 1 edges
5. `graphify-out/wiki/index.md` - 1 edges
6. `Source Files (language reference books)` - 1 edges

## Surprising Connections (you probably didn't know these)
- `graphify (knowledge graph tool)` --conceptually_related_to--> `slang-synthesis project`  [INFERRED]
  CLAUDE.md → README.md
- `slang-synthesis project` --conceptually_related_to--> `Source Files (language reference books)`  [INFERRED]
  README.md → source_reference/README.md

## Communities (2 total, 1 thin omitted)

### Community 0 - "Graphify Tooling Docs"
Cohesion: 0.50
Nodes (4): graphify-out/graph.json, graphify-out/GRAPH_REPORT.md, graphify (knowledge graph tool), graphify-out/wiki/index.md

## Knowledge Gaps
- **4 isolated node(s):** `graphify-out/graph.json`, `graphify-out/GRAPH_REPORT.md`, `graphify-out/wiki/index.md`, `Source Files (language reference books)`
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `graphify (knowledge graph tool)` connect `Graphify Tooling Docs` to `Project Corpus Overview`?**
  _High betweenness centrality (0.900) - this node is a cross-community bridge._
- **Why does `slang-synthesis project` connect `Project Corpus Overview` to `Graphify Tooling Docs`?**
  _High betweenness centrality (0.400) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `slang-synthesis project` (e.g. with `graphify (knowledge graph tool)` and `Source Files (language reference books)`) actually correct?**
  _`slang-synthesis project` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `graphify-out/graph.json`, `graphify-out/GRAPH_REPORT.md`, `graphify-out/wiki/index.md` to the rest of the system?**
  _4 weakly-connected nodes found - possible documentation gaps or missing edges._