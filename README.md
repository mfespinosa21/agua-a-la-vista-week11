# Agua a la Vista · Week 11
Fernanda Espinosa

Live demo: https://agua-a-la-vista-fernanda.mafer212005.chatgpt.site

This Site and repository are private. Evaluator access must be configured before submission.

## What works
Manual-first tank-level simulation; optional digital alerts; actual linear regression on synthetic hourly data; illustrative full-cost calculation. All values are invented. No sensor, real household history, personal data, water safety claims or remote shutoff.

Serve dist/ with any static server. No build, backend, keys, external libraries or accounts needed by the application.

## Development evidence
The six original development commits are preserved exactly in DEVELOPMENT_HISTORY.bundle. GitHub commits here upload the final files; they are not the original development timeline. Clone the bundle to inspect packet-before-code, the actual code changes and DECISIONS.md:

    git clone DEVELOPMENT_HISTORY.bundle agua-original
    cd agua-original
    git log --reverse --oneline
    node tests/mechanical.cjs

SOURCE_WITH_DOCS.zip includes the source, tests, generated mockup and all Markdown documents. docs/PACKET.md renders the Mermaid diagrams on GitHub.

Original source history:
- bd9f410: Packet before code
- 6309bb2: ML and cost model
- f4a949f: initial UI; first deploy
- bd4d5a7: tests and uncertainty bug correction
- f2dd340: clarity and second deploy
- 69a23e2: persona evidence and current uncertainty range; third deploy

19 domain checks passed. Browser checks verified low, uncertain, stale and missing readings. Synthetic persona reviewed ordered screenshots; no field validation or six-household pilot claimed.

Full chat export and user-recorded3:30 demo remain separate deliverables. BUILD_RECORD.md is a supplement, not a full transcript.
