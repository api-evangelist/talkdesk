# Talkdesk (talkdesk)

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

Talkdesk is a cloud contact center platform with Customer Experience Automation (CXA)
capabilities including omnichannel engagement, workforce engagement management, quality
management, analytics, and a marketplace of partner integrations. The Talkdesk developer
surface exposes REST APIs and webhook delivery across three documented webhook services:
the Events API (partner-app lifecycle events signed with ECDSA), the Webhook Trigger API
(Talkdesk Connections triggers for call, agent, contact, and note events), and the
Automated Notifications bridge for Digital Connect (DCE). This index currently models the
webhook surface as an AsyncAPI 2.6 document.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/talkdesk/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/talkdesk/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Contact Center
- CCaaS
- Voice
- Webhooks
- Events
- Telephony
- Customer Experience
- Digital Connect
- AppConnect

## Timestamps

- **Created:** 2026-05-30
- **Modified:** 2026-05-30

## APIs

### Talkdesk Webhook Surface

AsyncAPI 2.6 description of Talkdesk's publicly documented outbound webhook surface,
covering the Events API (partner-app lifecycle), the Webhook Trigger API (Talkdesk
Connections triggers for call/agent/contact/note events), and the Automated
Notifications bridge for Digital Connect (DCE). Only event types that appear in
docs.talkdesk.com are modeled. Frequently-asked-about events such as
recording_available and agent_status_change are not documented as standard event
types on the public docs site and are intentionally not included.

- **Human URL:** [https://docs.talkdesk.com/docs/events-api](https://docs.talkdesk.com/docs/events-api)

#### Tags

- Webhooks
- Events
- AsyncAPI
- Partner Apps
- Connections
- Digital Connect

#### Properties

- [Documentation](https://docs.talkdesk.com/docs/events-api)
- [Documentation](https://docs.talkdesk.com/docs/webhook-trigger-api)
- [Documentation](https://docs.talkdesk.com/reference/automated_notifications_webhook_for_dce)
- [API Reference](https://docs.talkdesk.com/reference/upsertsubscription)
- [AsyncAPI](asyncapi/talkdesk-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [Website](https://www.talkdesk.com)
- [Developer Portal](https://docs.talkdesk.com)
- [Documentation](https://docs.talkdesk.com)
- [Support](https://support.talkdesk.com/hc/en-us)
- [Terms of Service](https://www.talkdesk.com/legal/)
- [Privacy Policy](https://www.talkdesk.com/terms-of-service/privacy-notice/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
