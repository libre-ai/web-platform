# `@libre-ai/web-platform`

Framework-free Bun/React web boundary. It provides deterministic React document rendering,
hydration, strict local-asset validation, security headers, static assets and a small request
router for direct `Bun.serve` adapters.

Bun request objects remain in the server adapter. The package has no product domain, storage,
authentication or infrastructure responsibility.

## Publication

**Publish-ready** (`publishConfig.access=public`) as a wave-1 support satellite:
`@libre-ai/auth-web` consumes `secureResponse` (response-hardening surface —
duplicating it would drift), so this package joins the publish set by
dependency closure even though EXECUTION-SEQUENCING names only ui/auth/sdk-ts;
owner-vetoable. `react`/`react-dom` are peer dependencies. **Bun-first
package:** it ships TypeScript source (no dist build) — consumers need a
TS-aware toolchain (bun natively; vite/esbuild-based bundlers otherwise).
Publication is the owner-run `Release satellites` workflow (see
`docs/transformation/WAVE1-PUBLICATION-RUNBOOK.md`). No reserved mirror
repository yet: npm-only until the owner reserves one.

## État du projet

<!-- libre-ai:project-status:begin -->
<!-- Section générée depuis project.v1.yaml — ne pas éditer à la main. -->

- Situation actuelle : Née verte en γ 3.4 (ex packages/web-platform) ; les huit applications produit la consomment épinglée.
- Maturité : usable
- Exposition : usable-verifiable
- Confiance : medium
- Preuves vérifiées le : 2026-07-30
- Avancement : 50 % du périmètre actuellement déclaré

<!-- libre-ai:project-status:end -->

La fiche [`project.v1.yaml`](./project.v1.yaml) est l'autorité de l'état du projet ; cette section en est générée et le gate de flotte échoue si elles divergent.
