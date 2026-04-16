---
title: "Client Management Platform"
type: entity
updated: 2026-04-16
sources:
  - raw/gdrive/2026-04-13-daily-learning-1250.md
  - raw/gdrive/2026-04-14-daily-learning-0754.md
  - raw/gdrive/2026-04-15-daily-learning-0758.md
---

# Client Management Platform

An internal platform being built by Mohamed Anis to centralize client management, system deployment, and document generation. As of April 2026, it runs on a local machine and is not yet published.

## Capabilities (Demonstrated Apr 13-14, 2026)

- **Client creation** -- add a new client (e.g., "Digna") with a simple form
- **System spin-up** -- create a system for a client (e.g., "Digna Client Outbound") with one click
- **Team assignment** -- assign team members and team leaders to a client (e.g., Farhaan Abdi hassan as team member, Adam as team leader for Digna)
- **Document generation** -- generate KYC documents (Know Your Client as Person, Business, Context, Target Audience) through the platform
- **Multi-system support** -- a client can have both outbound and inbound systems; creating a second system (e.g., "DNA Client Inbound") is a separate action

## Current Status

- Built in "3-4 hours" on Apr 13, 2026 -- did not exist before that day
- Running on Mohamed Anis's local machine
- Not yet published or deployed to the team
- Document generation via "one click" is the intended workflow but not fully built yet
- "Really expensive" to run, which has delayed wider deployment

## Vision

The platform should allow team leaders to:
1. Log in and see their assigned clients
2. See which KYC steps have been completed and which remain
3. Generate missing documents with one click
4. Manage raw inputs about each client
5. See whether a client has signed up for outbound only, inbound only, or both
6. Showcase the system's power to prospective clients during sales calls

Farhaan Abdi hassan recognized the vision: "This is like preparing the seven documents in just one click button -- generate."

## Architecture Notes

The platform wraps around the [Research Engine](../../strategy-vision/research-engine.md), turning the sequential KYC document chain into a guided workflow. Each generated document feeds into the next, matching the dependency chain defined in the [Outbound Strategy](../../clients-partnerships/win-new/outbound/outbound-strategy.md).

StepUp.One itself is treated as a client in the system -- "StepUp is a client," making the system self-referential and dogfooded.

## Related Pages

- [Research Engine](../../strategy-vision/research-engine.md) -- the intelligence layer the platform wraps
- [Outbound Strategy](../../clients-partnerships/win-new/outbound/outbound-strategy.md) -- the process the platform automates
- [Mohamed Anis](../people/mohamed-anis.md) -- builder and primary developer
