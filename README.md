# Lifesize

Lifesize is a video conferencing and meeting-room platform — Lifesize Cloud meeting service, Icon conference-room systems, the Lifesize Share wireless presentation appliance, Phone HD, and the web/desktop/mobile apps. Lifesize merged with contact-center provider Serenova (CxEngage) in 2020 and was acquired by Enghouse Systems in 2023; the video business now operates as Enghouse Video (Vidyo Inc.) and the Lifesize brand and product line continue under [enghousevideo.com/lifesize](https://www.enghousevideo.com/lifesize). `lifesize.com` now redirects there.

## API surface

- **[Lifesize Icon Automation API](https://support.lifesize.com/product/lifesize-icon-400-450-600-800/advanced-topics/api-overview/)** — an on-device REST interface plus the **Lifesize Automation Command Line Interface (CLI)**, built into Lifesize Icon systems (models 300–800). Reached over HTTPS or SSH with administrator credentials, self-documenting on the device at `/docs/json` (REST) and `/docs/clish` (CLI). Covers configuration retrieval, preference changes, call status and statistics, and call control.
- **Lifesize Cloud API** — the hosted service API behind Lifesize Cloud, the Admin Console, and the client apps at `https://api.lifesizecloud.com`. Live but not publicly documented; returns HTTP 403 to unauthenticated callers.

Lifesize publishes **no OpenAPI/Swagger/GraphQL/AsyncAPI definition**, no SDKs on any public package registry, no public GitHub organization, no MCP server, no webhook or event surface, and no sandbox or Postman collection. It does publish a support/documentation site, per-product dated release notes, and an Atlassian-hosted [status page](https://status.lifesizecloud.com/).

## Artifacts

| Artifact | File |
|---|---|
| Authentication | `authentication/lifesize-authentication.yml` |
| API conventions | `conventions/lifesize-conventions.yml` |
| CLI | `cli/lifesize-cli.yml` |
| Lifecycle | `lifecycle/lifesize-lifecycle.yml` |
| Changelog | `changelog/lifesize-changelog.yml` |
| Conformance | `conformance/lifesize-conformance.yml` |
| Domain security | `security/lifesize-domain-security.yml` |
| Well-known probe | `well-known/lifesize-well-known.yml` (no documents found) |
| llms.txt | `llms/lifesize-llms.txt` |

Backed by: norwest-venture-partners, redpoint-ventures — https://lifesize.com
