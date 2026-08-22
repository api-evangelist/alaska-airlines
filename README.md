# Alaska Airlines (alaska-airlines)

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

A major American airline headquartered in SeaTac, Washington, operating an extensive domestic network with service across the U.S., Mexico, Canada, and Central America. Known for its customer service and West Coast focus.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/alaska-airlines/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=alaska-airlines-api-evangelist&utm_content=repo)

## Tags:

 - Airlines, Travel, Transportation

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-16

## APIs

Alaska Airlines does not publish a public developer portal or self-service developer API. Distribution to travel agencies and aggregators is via Sabre / Amadeus GDS feeds and NDC partnerships; direct technical integration requires a bilateral commercial agreement.

## Common Properties

- [Website](https://www.alaskaair.com/)
- [Login](https://www.alaskaair.com/account/login)
- [SignUp](https://www.alaskaair.com/account/enrollment)
- [MileagePlan](https://www.alaskaair.com/content/mileage-plan)

## Features

| Name | Description |
|------|-------------|
| Mileage Plan Loyalty | Alaska Airlines' Mileage Plan loyalty program supporting earn-and-burn across Alaska, Hawaiian, and Oneworld partners. |
| Flight Booking | Direct distribution of Alaska Airlines fares through alaskaair.com, the mobile app, and indirectly through GDS / NDC distribution. |
| Flight Status | Real-time flight-status surface on alaskaair.com, the mobile app, and via airport / partner integrations. |
| Check-In and Boarding | Mobile check-in, mobile boarding pass, and Apple Wallet / Google Wallet support. |
| Lounge Access | Access to Alaska Lounges across the West Coast and select hubs for premium-cabin and Mileage Plan elite members. |

## Use Cases

| Name | Description |
|------|-------------|
| Domestic and Near-International Air Travel | Scheduled commercial air travel across the U.S., Mexico, Canada, Central America, and to Hawaii. |
| Loyalty Earn / Burn | Earning and redeeming Mileage Plan miles on Alaska, Hawaiian, and Oneworld partner flights. |
| Corporate Travel | Corporate travel program with negotiated fares via Alaska Airlines Business and TMC integration. |
| Cargo | Alaska Air Cargo services for the U.S., Mexico, and Latin America operating on Alaska's mainline and freighter network. |

## Authentication

| Name | Description |
|------|-------------|
| No Public Developer API | Alaska Airlines does not publish a public developer portal or self-service developer API. |

## Compliance

| Name | Description |
|------|-------------|
| PCI DSS | Payment Card Industry Data Security Standard compliance for ticket sales and loyalty redemptions. |
| TSA Secure Flight | Mandatory passenger pre-screening data exchange with the U.S. Transportation Security Administration. |
| DOT Tarmac Delay | U.S. Department of Transportation tarmac-delay and consumer-protection rules apply to Alaska's domestic operations. |
| FAA Part 121 | FAA Part 121 air-carrier certification governs Alaska's flight operations. |
| GDPR / CCPA | Privacy compliance for European and California passengers respectively. |

## Integrations

| Name | Description |
|------|-------------|
| Oneworld Alliance | Alaska Airlines is a member of the Oneworld global airline alliance. |
| Hawaiian Airlines | Alaska Air Group has acquired Hawaiian Airlines; the two carriers' loyalty programs and operations are progressively integrated. |
| Sabre / Amadeus | GDS distribution to travel agencies and corporate booking tools. |
| NDC | IATA NDC channel for richer offer-and-order content distribution. |
| Bank of America (co-brand) | Alaska Airlines Visa credit card portfolio is issued by Bank of America and earns Mileage Plan miles. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
