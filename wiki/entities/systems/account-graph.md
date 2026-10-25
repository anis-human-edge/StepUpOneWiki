---
title: "Account Graph"
type: entity
updated: 2026-10-25
sources:
  - raw/gmail/2026-10-21-notes-stepup-one-daily-learning-21-oct-2026.md
  - raw/gdrive/2026-10-21-stepup-one-daily-learning-2026-10-21-0759-bst-notes-by-gemini-1LayB5dNzD.md
  - raw/gdrive/2026-10-21-stepup-one-daily-learning-2026-10-21-1302-bst-notes-by-gemini-1vjINcNAUO.md
  - raw/gdrive/2026-10-22-stepup-one-daily-learning-2026-10-22-0800-bst-notes-by-gemini-12Yr5lor7y.md
  - raw/gdrive/2026-10-23-stepup-one-daily-learning-2026-10-23-0759-bst-notes-by-gemini-1H2Jz0jfAD.md
  - raw/gdrive/2026-10-24-stepup-one-daily-learning-2026-10-24-0800-bst-notes-by-gemini-1yQeUTTGRO.md
---

# Account Graph

StepUp.One's platform for managing and mapping target accounts and professional networks. Introduced to the team on **2026-10-21**.

## Purpose

Consolidates LinkedIn connections and professional relationship data across the entire StepUp.One team into a unified graph. Enables:

- Searching and leveraging team members' combined professional networks for warm introductions
- Mapping organizational structures at target accounts (buying centers, divisions, verticals)
- Calculating combined connection totals to highlight engagement overlaps across team members

## Data Input

Users upload LinkedIn connection files to the platform. The system integrates:
- Individual team member connection exports (uploaded as LinkedIn ZIP archive)
- Client network CSV exports (Farah Ibrahim downloading network files for clients Oct 21)
- Google, LinkedIn, and Apple contacts (synced for expanded network visibility)

**Format requirement:** LinkedIn ZIP archive (full data export) or raw CSV files. XLS format is not accepted. Ahmed Farhan was the first team member to demonstrate the process: downloaded his LinkedIn ZIP, uploaded it directly — no preprocessing required.

## Account Structure

The account graph categorizes connections by:
- Company divisions and verticals
- Buying centers (permanent department leadership + temporary deal-specific committees)
- Individual and collective decision-making units

## Multi-Tier Account Hunting

Reflects the 3-tier organizational hunting structure:
- **Tier 1:** Founding/leadership level
- **Tier 2:** Account leads
- **Tier 3:** Individual team members

For enterprise accounts like Cognizant and Standard Chartered, 3 selling centers target 3 specific buying centers (CXO, VP, and client partner levels).

## Network Value Estimation (Oct 23, 2026)

When a full LinkedIn ZIP archive is uploaded, the platform estimates the **market price of your entire LinkedIn profile** — what your professional network would be worth if sold at market rates. This value updates daily as connections grow.

- Ahmed Farhan's estimated profile value: ~$2M (2026-10-23 session)
- The number reflects the financial worth of existing relationships, not a sales price

This creates a striking opening for client demos: showing a CEO their network is worth $100M but is currently dormant is described by Anis as a moment that causes executives to "jump out of their chair."

### Relationship Value Per Contact

Each connection shows an individual estimated value plus a probability score (% likelihood to close). Example from Ahmed's demo:
- Lady with outstanding reply: $651 value, 50% close probability
- Another contact: ~$1,000 value, 80% close probability

**Warmth scores** ("bone" and "worm" metrics) reflect relationship strength and last interaction date.

### AI Follow-Up Message Generation

The research engine analyzes a prospect's profile, industry, company, and past conversations to generate **4 distinct follow-up angles**. Cost: **4–7 cents per search**.

Users can run research even without prior interaction — the engine reviews recent posts and news mentions to draft customized messages. Farah Ibrahim's Oct 23 demo: evaluated 4 AI-generated messages for Emily at IBM Ventures; options 1–3 were judged natural and human-sounding; option 4 was explicitly rejected as "begging" (requesting a quick call with no value offered).

**Key principle:** Users must evaluate AI outputs critically. The tool generates angles — the human selects and refines.

### Birthday Tracking

The platform identifies upcoming birthdays **2–3 days in advance**, allowing proactive outreach before LinkedIn publicly displays the date. This creates a "caring" impression — the contact assumes you remembered independently. Ahmed Farhan demonstrated successfully using this feature before LinkedIn notified him.

### Conversation Stage Tracking

Users can record private notes and update conversation stages for any contact (e.g., "in conversation," "proposal sent," "opportunity"). Notes can be set to private (visible only to the user).

## AI Tool Accuracy Issues (Oct 24, 2026)

The prospecting engine has known accuracy limitations as of Oct 2026:

- **Colleague recognition:** The tool does not distinguish internal team members from prospects. Patience Ciza appeared as a "strong fit" recommendation for Abdulkadir Mhina. Users must apply common sense and manually filter out colleagues.
- **Closed prospect re-surfacing:** The tool resurfaces prospects who have already said "not a fit," recommending them as priority contacts.
- **Revenue estimates:** Values like "$863" for a teammate are meaningless — treat AI estimates as directional, not literal.

**Resolution process:** Team members send error screenshots to the main group channel immediately on discovery; Anis reviews and fixes.

## Dashboard and Filtering (Oct 23–24, 2026)

### Seniority Filtering

Instead of deleting unwanted connections, users filter by level: CEO, VP + executive, manager, etc. This surfaces only the relevant relationship tier for the task at hand.

**Example — Abdulkadir Mhina (Oct 24):** 1,790 founders ($45.1K capital), VPs ($11.4K capital), 358 executives, 408 managers.

**Example — Farhan (Oct 24):** 912 total connections; 80 from StepUp.One team; ~10% self-employed (no revenue potential); seniority breakdown: 24 CEOs, 105 founders, 26 CXOs, 623 VPs/executives/directors.

### Exclusion Feature (Planned)

Anis agreed to build a feature where users (and clients) can flag specific people or companies to **never surface in recommendations**. Use cases:
- Clients' existing relationships (avoid embarrassing contact with their partners/friends)
- Internal team members
- Contacts who have explicitly said "not a fit"
- CDG incident: during a campaign, a team member accidentally contacted a client's personal friend on LinkedIn

## Multi-Channel Integration (Oct 24, 2026)

The platform is designed to centralize relationship data from all channels:

| Channel | Status |
|---------|--------|
| LinkedIn | Live (ZIP upload) |
| X (Twitter) | Planned |
| Email | Planned |
| WhatsApp | Planned (for senior leaders with client WhatsApp relationships) |

**The vision:** Anis has sent ~1M WhatsApp messages across 3,000 groups. For a 10-person team managing a client like GSK Pharma over 7 years, a centralized view of all touchpoints (LinkedIn + WhatsApp + email) across all team members is the core value proposition.

**Privacy note:** Some team members flagged concerns about uploading personal messaging data. Resolution: give users/clients the ability to hide personal conversations and reveal only professional ones.

**Data discrepancy known issue:** LinkedIn ZIP uploads sometimes show a lower connection count than actual (e.g., 5,029 → 4,000+). Under investigation.

## CRM Replacement Context

The platform competes directly with traditional CRM systems:
- **Salesforce** (world's largest CRM): ~$1–2M/year for an enterprise team; companies are actively cancelling Salesforce contracts to build AI-native CRMs in months at a fraction of the cost
- **HubSpot**: ~10× smaller than Salesforce by revenue
- **Key differentiator:** Traditional CRMs track only people who reply. Account Graph tracks the **entire network** including dormant and un-engaged connections.

The team discussed an Oct 2026 news article about a company cancelling a $600K Salesforce deal after building a replacement CRM in 2 months.

## Competitive Context

StepUp.One's account graph outperforms **Hapstar** (also called "Happensance") in network analysis capabilities per Ahmed Farhan's Oct 23 assessment. Also noted as a complementary tool earlier in the Oct sessions.

## Relationship Capital Statement (Oct 22, 2026)

The platform generates a **relationship capital statement** — a financial valuation of each team member's professional network. This was the key feature demonstrated in the Oct 22 session.

### Three Metrics

| Metric | Definition |
|--------|-----------|
| **Closeable-now** | Connections with enough warmth to potentially convert to business now |
| **Unutilized** | Connections that exist but haven't been actively engaged |
| **Active** | Relationships currently in two-way active engagement |

**Example — Ahmed Farhan:** 874 closeable-now, 894 unutilized, 24 active. Total relationship capital value: **$25K**. Target set by Mohamed Anis: $100K.

### Converting Engine, Not Building Engine

The platform does not create relationship capital — it surfaces and quantifies what already exists in the team's combined network. The statement is built on **current reality** (existing relationships), not speculative future value.

Mohamed Anis: the platform showed early clients their network expressed as a financial asset statement for the first time. Initial reactions described as "extraordinary."

### LTV Integration

Relationship values are calculated using Lifetime Value (LTV) logic. A 10-year relationship with a client worth $50K/year = $500K LTV. This makes individual connections legible as financial assets rather than abstract goodwill.

## Related Pages

- [ABSM Methodology](../../clients-partnerships/win-new/outbound/absm-methodology.md)
- [Client Relationship Framework](../../training-reskilling/client-relationship-framework.md)
- [Commenting Studio](commenting-studio.md)
- [LinkedIn Commenting](../../training-reskilling/linkedin-commenting.md)
