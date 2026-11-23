# FLARE

**Creator intelligence, from discovery to outreach.**

[Explore the platform](https://useflare.ai)

---

FLARE is a research and workflow platform for teams working across the creator economy. It connects creator discovery, brand activity, agency relationships and outreach in one place.

## The platform

| Discover | Understand | Act |
| :--- | :--- | :--- |
| Find creators and explore their content and performance. | Research brands, commercial activity and agency relationships. | Build shortlists, prepare outreach and manage conversations. |

## Architecture

FLARE combines a web application with separate data processing systems.

| Component | Responsibility |
| :--- | :--- |
| Application | Next.js and TypeScript interface, APIs and operational workflows |
| Serving layer | PostgreSQL-backed discovery, account and workflow data |
| Intelligence layer | Creator, brand and agency relationships, entity resolution and commercial evidence |
| Data pipelines | Collection, enrichment and scheduled refresh of source information |
| Integrations | Connected email, outreach and supporting platform services |

## Capabilities

- **Creator discovery:** Explore creators, their content and performance signals.
- **Brand intelligence:** Research brand activity and creator relationships.
- **Agency intelligence:** Explore agency records, representation evidence and rosters.
- **Outreach workflows:** Build shortlists, prepare personalised communication and manage conversations.
- **Commercial evidence:** Distinguish sponsorship disclosures, affiliate activity and weaker brand associations where evidence permits.

## Technology

| Area | Technologies used in the application |
| :--- | :--- |
| Web | Next.js, React, TypeScript |
| Data | PostgreSQL, Neon, BigQuery |
| UI | Tailwind CSS, Recharts |
| Services | Vercel, Google integrations and email providers |

These are selected technologies verified in the application repository, not an exhaustive inventory of the wider infrastructure.

## Repository structure

| Repository | Purpose |
| :--- | :--- |
| `flare` *(private)* | Main FLARE application |
| `flare-core-pipeline` *(private)* | Core data processing |
| `flare-yt-cron` *(private)* | Scheduled YouTube processing |
| `flare-backup` and `flare-dev-backup` *(private)* | Backup repositories retained for recovery |

Application and pipeline repositories remain private. Public documentation does not expose internal deployment configuration, credentials or customer data.

## Engineering principles

**Evidence over assumptions.** A mention is not automatically a sponsorship. An estimated metric is not a verified financial result.

**History matters.** New data should improve a record without silently erasing context or provenance.

**Useful beats impressive-looking.** The product should help teams make decisions, not just display dashboards.

**Systems should be operable.** Clear ownership, reviewable changes, practical testing and recovery paths are part of shipping.

---

**FLARE** · [useflare.ai](https://useflare.ai)
