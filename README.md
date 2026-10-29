# Cloud Custodian

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cloud Custodian is an open-source rules engine for cloud security, compliance, and cost-optimization governance now stewarded by Stacklet. Operators express policies as YAML files that select a cloud resource type, apply filters, and execute actions; the engine then runs those policies against AWS, Azure, and GCP via provider-specific plugins. Custodian does not expose a developer REST API of its own - integration is via the c7n CLI, the policy YAML schema, c7n-org for multi-account fan-out, and c7n-mailer for SQS-driven notifications.

**Areas:** Cloud Security · Compliance · Cost Optimization · Multi-Cloud · Policy as Code

## Cloud Custodian on APIs.io

Everything profiled for Cloud Custodian is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cloud-custodian/](https://apis.io/providers/cloud-custodian/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [Cloud Custodian](https://apis.io/apis/cloud-custodian/cloud-custodian/) — Cloud Custodian provides rules-engine capabilities for managing cloud resources with security, compliance, and cost optimization policies.
- [Cloud Custodian AWS Provider](https://apis.io/apis/cloud-custodian/cloud-custodian-aws/) — The Cloud Custodian AWS provider enables policy-as-code management of Amazon Web Services resources including EC2, S3, IAM, RDS, Lambda, and hundreds of…
- [Cloud Custodian Azure Provider](https://apis.io/apis/cloud-custodian/cloud-custodian-azure/) — The Cloud Custodian Azure provider enables policy-as-code management of Microsoft Azure resources including virtual machines, storage accounts, network…
- [Cloud Custodian GCP Provider](https://apis.io/apis/cloud-custodian/cloud-custodian-gcp/) — The Cloud Custodian GCP provider enables policy-as-code management of Google Cloud Platform resources including Compute Engine instances, GCS buckets, Cloud…
- [Cloud Custodian C7n-Org](https://apis.io/apis/cloud-custodian/cloud-custodian-c7n-org/) — c7n-org is a Cloud Custodian tool for running policies across multiple cloud accounts, projects, or subscriptions in parallel. It uses an accounts…
- [Cloud Custodian C7n-Mailer](https://apis.io/apis/cloud-custodian/cloud-custodian-c7n-mailer/) — c7n-mailer is a Cloud Custodian notification tool that subscribes to an SQS queue populated by policy actions and sends notifications via SES email, Slack…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Cloud Custodian c7n-mailer Notification Events](https://apis.io/asyncapis/cloud-custodian/cloud-custodian-mailer-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/policy-notification](https://apis.io/channels/cloud-custodian/policy-notification/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Cloud Custodian Policy File](https://apis.io/schemas/cloud-custodian/cloud-custodian-policy/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cloud Custodian Context](https://apis.io/jsonld/cloud-custodian/cloud-custodian-context/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Cloud Custodian — asyncapi rules](https://apis.io/rules/cloud-custodian/cloud-custodian-asyncapi-spectral-rules/)
- [Cloud Custodian — jsonschema rules](https://apis.io/rules/cloud-custodian/cloud-custodian-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Cloud Custodian Domain Security](https://apis.io/security/cloud-custodian/cloud-custodian-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cloud Custodian Plans Pricing](https://apis.io/plans/cloud-custodian/cloud-custodian-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cloud Custodian Rate Limits](https://apis.io/rate-limits/cloud-custodian/cloud-custodian-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cloud Custodian Finops](https://apis.io/finops/cloud-custodian/cloud-custodian-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cloudcustodian.io/)
- [Documentation](https://cloudcustodian.io/docs/)
- [Getting started](https://cloudcustodian.io/docs/quickstart/index.html)
- [Changelog](https://github.com/cloud-custodian/cloud-custodian/releases)
- [GitHub](https://github.com/cloud-custodian/cloud-custodian)

## API Evangelist rating

**Kin Score 35.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 51.5 |
| Contract governance | 13.6 |
| Operational transparency | 36.8 |
| Developer ergonomics | 31.0 |
| Access clarity | 7.9 |

**Agent readiness 14.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cloud-custodian/](https://apis.io/providers/cloud-custodian/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cloud Custodian: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cloud-custodian/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
