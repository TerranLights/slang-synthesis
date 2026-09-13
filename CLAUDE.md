## Standing operating-hours law

This project (the language-extraction repo) is permitted to run autonomous/background work
(Auto Mode pushes, `/loop`, scheduled wakeups, long unattended subagent batches, etc.) **only
between 3:00pm and 4:59am**, any day of the week. Outside that window (5:00am–2:59pm), do not
self-schedule new autonomous work in this repo — pause and wait for the user, even if a task
feels unfinished. Work already in flight when the window closes does not need to be forcibly
killed, but no new wave/batch should be dispatched past the boundary; resume once the window
reopens. This is a durable rule, not a one-off preference — it applies across all future sessions
on this project.

## graphify

This project has a knowledge graph at graphify-out/ with god nodes, community structure, and cross-file relationships.

Rules:
- For codebase questions, first run `graphify query "<question>"` when graphify-out/graph.json exists. Use `graphify path "<A>" "<B>"` for relationships and `graphify explain "<concept>"` for focused concepts. These return a scoped subgraph, usually much smaller than GRAPH_REPORT.md or raw grep output.
- If graphify-out/wiki/index.md exists, use it for broad navigation instead of raw source browsing.
- Read graphify-out/GRAPH_REPORT.md only for broad architecture review or when query/path/explain do not surface enough context.
- After modifying code, run `graphify update .` to keep the graph current (AST-only, no API cost).
