# web-platform Canonical Agent Rules

## Authority

Web application foundation (couche 4) of the Libre AI constellation:
Bun.serve SSR/hydration/static serving, React 19, session security and
hardened response headers, letting a constellation application start
securely without reassembling the foundation. A single foundation is
consumed pinned by every product application. Fleet doctrine and the
gate template live upstream:
https://raw.githubusercontent.com/libre-ai/governance/main/AGENTS.md

## Boundaries

- No second durable implementation of this domain exists elsewhere in
  the constellation; this repository is the one implementation.
- Current exposure and acceptance state live in this repository's own
  `project.v1.yaml`, aggregated by governance — never duplicated here.

## Quality gates

Run `bun run check` before pushing; never hide a red test.

## Agents

- Read actual state before editing.
- Stage files before running tree-walking gates.
- Security > quality > performance > completeness.
