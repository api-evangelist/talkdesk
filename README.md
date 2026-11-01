# Talkdesk

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

Talkdesk is a cloud contact center platform with Customer Experience Automation (CXA) capabilities including omnichannel engagement, workforce engagement management, quality management, analytics, and a marketplace of partner integrations. The Talkdesk developer surface exposes REST APIs and webhook delivery across three documented webhook services: the Events API (partner-app lifecycle events signed with ECDSA), the Webhook Trigger API (Talkdesk Connections triggers for call, agent, contact, and note events), and the Automated Notifications bridge for Digital Connect (DCE). This index currently models the webhook surface as an AsyncAPI 2.6 document.

**Areas:** Contact Center · CCaaS · Voice · Webhook · Event · Telephony · Customer Experience · Digital Connect · AppConnect · Customer Service

## Talkdesk on APIs.io

Everything profiled for Talkdesk is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/talkdesk/](https://apis.io/providers/talkdesk/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Talkdesk Webhook Surface](https://apis.io/apis/talkdesk/webhooks/) — AsyncAPI 2.6 description of Talkdesk's publicly documented outbound webhook surface, covering the Events API (partner-app lifecycle), the Webhook Trigger…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Talkdesk Webhook Surface](https://apis.io/asyncapis/talkdesk/talkdesk-webhooks-asyncapi/)

#### Event channels (18)

Individual events and webhooks the provider emits.

- [automated-notifications/bridge/digital-connect](https://apis.io/channels/talkdesk/automated-notifications-bridge-digital-connect/)
- [partner-events/app.credentials_rotated](https://apis.io/channels/talkdesk/partner-events-app-credentials-rotated/)
- [partner-events/app.installed](https://apis.io/channels/talkdesk/partner-events-app-installed/)
- [partner-events/app.trial_ended](https://apis.io/channels/talkdesk/partner-events-app-trial-ended/)
- [partner-events/app.trial_extended](https://apis.io/channels/talkdesk/partner-events-app-trial-extended/)
- [partner-events/app.trial_started](https://apis.io/channels/talkdesk/partner-events-app-trial-started/)
- [partner-events/app.uninstalled](https://apis.io/channels/talkdesk/partner-events-app-uninstalled/)
- [partner-events/app.updated](https://apis.io/channels/talkdesk/partner-events-app-updated/)
- [partner-events/user.logout](https://apis.io/channels/talkdesk/partner-events-user-logout/)
- [webhook-trigger/agent-logged-in](https://apis.io/channels/talkdesk/webhook-trigger-agent-logged-in/)
- [webhook-trigger/agent-logged-out](https://apis.io/channels/talkdesk/webhook-trigger-agent-logged-out/)
- [webhook-trigger/contact-created](https://apis.io/channels/talkdesk/webhook-trigger-contact-created/)
- [webhook-trigger/contact-updated](https://apis.io/channels/talkdesk/webhook-trigger-contact-updated/)
- [webhook-trigger/inbound-call-ends](https://apis.io/channels/talkdesk/webhook-trigger-inbound-call-ends/)
- [webhook-trigger/inbound-call-reaches-contact-center](https://apis.io/channels/talkdesk/webhook-trigger-inbound-call-reaches-contact-center/)
- [webhook-trigger/inbound-call-starts](https://apis.io/channels/talkdesk/webhook-trigger-inbound-call-starts/)
- [webhook-trigger/note-created](https://apis.io/channels/talkdesk/webhook-trigger-note-created/)
- [webhook-trigger/outbound-call-ends](https://apis.io/channels/talkdesk/webhook-trigger-outbound-call-ends/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Talkdesk — asyncapi rules](https://apis.io/rules/talkdesk/talkdesk-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Talkdesk Domain Security](https://apis.io/security/talkdesk/talkdesk-domain-security/)
- [Talkdesk Vulnerability Disclosure](https://apis.io/security/talkdesk/talkdesk-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.talkdesk.com)
- [Documentation](https://docs.talkdesk.com)
- [Support](https://support.talkdesk.com/hc/en-us)
- [Blog](https://www.talkdesk.com/blog/)
- [Terms of service](https://www.talkdesk.com/legal/)
- [Privacy policy](https://www.talkdesk.com/terms-of-service/privacy-notice/)

## API Evangelist rating

**Kin Score 27.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 43.8 |
| Contract governance | 13.6 |
| Operational transparency | 0.0 |
| Developer ergonomics | 20.2 |
| Access clarity | 21.1 |

**Agent readiness 14.0** — agent-aware

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
| Rate Limit Signal | — |
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

**Regulatory alignment 19.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/talkdesk/](https://apis.io/providers/talkdesk/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Talkdesk: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/talkdesk/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
