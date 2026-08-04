# Lifesize

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
