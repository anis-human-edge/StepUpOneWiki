---
title: "Commenting Studio"
type: entity
updated: 2026-10-25
sources:
  - raw/gmail/2026-10-19-notes-stepup-one-daily-learning-19-oct-2026.md
  - raw/gmail/2026-10-20-notes-stepup-one-daily-learning-20-oct-2026.md
  - raw/gmail/2026-10-21-notes-stepup-one-daily-learning-21-oct-2026.md
  - raw/gdrive/2026-10-24-stepup-one-daily-learning-2026-10-24-0800-bst-notes-by-gemini-1yQeUTTGRO.md
---

# Commenting Studio

StepUp.One's AI-powered LinkedIn commenting training and execution platform. Officially launched for team use on **2026-10-19**, following final speed optimization work still in progress.

## Purpose

Dual function: (1) train team members to evaluate and write professional LinkedIn comments, and (2) generate approved comments at scale for ABSM client accounts.

## Training Architecture

Three proficiency tiers:

| Tier | Mode | What users do |
|------|------|---------------|
| **Beginner** | Evaluation | Choose from 5 comment options; identify the correct one and explain why others fail |
| **Intermediate** | Selection + critique | Identify errors using specific terminology (apology opener, off point, question dump, etc.) |
| **Expert** | Generation + voice | Write and post comments using client voice profiles |

Beginner mode teaches **error identification over posting** — understanding why wrong options fail is the core learning objective, not selecting the best comment.

## Comment Evaluation Framework

**Failure types (disqualifiers):**
- **Parroting** — comment merely repeats the author's own statements
- **Excessive praise** — generic agreement with no substantive value
- **Self pitch** — promotional content inserted into a comment
- **Indecisive phrasing** — speculative language ("might", "could be") creating uncertainty
- **Wrong voice** — unnatural tone misaligned with client persona
- **Off point** — remark irrelevant to the post's actual topic
- **Question dump** — multiple questions in a single comment (questions go unanswered; only ask one)
- **Invented facts / unnamed metrics** — fabricated data or vague statistics
- **Generic agreement phrases** — "Great post!", "So true!" with no added value
- **Excessive jargon** — terminology misaligned with natural speech

**Passing criteria:**
- Adds a unique perspective, reinforces author's point, or offers a relevant counter-example
- Uses natural tone consistent with the commenter's voice profile
- Asks at most one targeted question (increases author engagement)
- Frames intelligence around measurable customer outcomes (for ABSM posts)

## Gamification

The system automatically tracks user **streaks**, **scores**, and **earned badges** to drive consistent practice.

## ABSM Client Execution

The studio generates comments for client accounts at scale:

- **Dodo client**: 10–20 comments/day targeting CXO, VP, and director-level posts; all draft responses reviewed and approved by Richard for the first 2 months
- **Torio client**: email-first outreach due to low LinkedIn activity (commenting studio less relevant)
- Target roles: sales and business development leaders at accounts in the client's target list

## Voice Profiles

Each client gets a dedicated **voice profile** within the studio enabling automated responses in their distinct communication style. Team task (Oct 21): create Richard's voice profile.

## Technical Notes

- Login via StepUp.One credentials required
- High operational cost: ~12 AI calls per generated comment
- Initial post analysis notes disappear immediately after comment generation
- Platform tracks learning progress across tiers
- Client categorization field planned (not yet live as of Oct 20)
- Profile banners/photos require manual updates for correct display

## Access

Abdulkadir Mhina demonstrated the studio to the team (Oct 20). Farah Ibrahim and the team are the primary execution agents for Dodo.

## Related Pages

- [LinkedIn Commenting](../../training-reskilling/linkedin-commenting.md)
- [ABSM Methodology](../../clients-partnerships/win-new/outbound/absm-methodology.md)
- [Dodo](../clients/dodo.md)
- [Account Graph](account-graph.md)
