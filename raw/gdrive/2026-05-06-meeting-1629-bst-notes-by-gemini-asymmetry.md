---
source: farmer/gdrive
farmed: 2026-05-10T00:00:00Z
drive_id: 1UzOkjV-CaxB2VEJW5Ke-qseDgpOModZDwbJqKBud6JM
title: Meeting started 2026/05/06 16:29 BST – Notes by Gemini
mime_type: application/vnd.google-apps.document
folder: SUO Meeting Recordings
modified: 2026-05-06
owner: anis@human-edge.io
---

# Notes

May 6, 2026

## Meeting May 6, 2026 at 16:29 BST (Asymmetry / Chris Thomas)

### Summary

Website strategy alignment and CRM configuration requirements for advisory and acquisition business divisions.

**Advisory Website Strategy**
The main website will focus exclusively on advisory services including MVC, plan B, exit, and raise. Acquisition operations must remain on a completely separate, standalone domain.

**CRM Data Management**
The primary decision is to categorize business data under companies rather than leads to resolve import errors. Mapping the name field is required for successful data ingestion.

**System Infrastructure Setup**
Google and Gmail accounts will be limited to 1 user initially to control costs. All system integrations and automations will follow the initial account provisioning.

### Next steps

- [Chris Thomas] Setup Gmail: Configure Google Gmail account for 1 user.
- [Chris Thomas] Send Credentials: Provide Mohamed Anis with the new Gmail setup credentials and details.
- [Mohamed Anis] Configure Gmail: Point the new Gmail setup to the correct internal system location using provided credentials.
- [Mohamed Anis] Troubleshoot Import: Use the shared CSV file to upload data into the asymmetry CRM; investigate upload blocker issue.
- [Chris Thomas] Provide CRM Feedback: Deliver granular feedback to Mohamed Anis regarding CRM issues tomorrow; specifically detail import and company mapping structure.
- [Mohamed Rafique] Review Documents: Deeply understand shared project documents to properly own upcoming changes.
- [Mohamed Rafique] Clean Website: Clean up asymmetry.com advisory content; focus website structure on 4 service verticals: Raise, Operate, Exit, Plan B.
- [Mohamed Rafique] Build Acquire Site: Create completely separate standalone website acquire.asymmetry.com; focus site 100% on acquisition services.

### Details

- **Website Strategy for Advisory and Acquisition**: Chris Thomas and Mohamed Anis agreed that the advisory firm's core offerings — MVC, raise, exit, plan B, and the CXO side — should be handled through distinct landing pages on the main website. They determined that mixing acquisition with advisory services is dangerous and should be avoided. Therefore, asymmetry.com will focus solely on the advisory business and its four core functions: MVC, Plan B, exit, and raise.

- **Separation of Acquisition Business**: The decision was made to keep the acquisition side completely separate. Acquisition will be featured on a standalone website, potentially acquire.asymmetry.com, and will not be mentioned on the main advisory site. This separate site will contain themes related to "buy and build out and standardize and compromise and abita multiply."

- **CRM Import Issue and Lead Management**: Chris Thomas reported being unable to complete a mass import of lead data via CSV because the "next" button on the mapping page was grayed out. Mohamed Anis diagnosed the issue: the primary key "name" field was not mapped. He also clarified that the CSV data (business names) should be imported under "companies," not "leads."

- **Google/Gmail Setup Commitment**: Chris Thomas agreed to set up the Google/Gmail account that day and send login credentials to Mohamed Anis. Mohamed Anis advised setting up only one user initially to avoid unnecessary costs.

- **Internal Review of Service Offerings**: Mohamed Anis reviewed the advisory services with Mohamed Rafique, confirming that asymmetry.com would feature four services: raise, exit, operate, and plan B. The acquire website must be completely separate and focus 100% on acquisition.

### Transcript (excerpt)

**Chris Thomas:** We're not reinforcing that narrative. And to be clear, all that could be done through landing pages. We can just create five distinct landing pages for each of the verticals. Clean up the website a bit to make it a bit more consistent.

**Mohamed Anis:** The advisory is we are not an exit acquirer... advisory is all these four things... acquire is what he wants to add newly. And these two must be completely separate.

**Chris Thomas:** The acquire part is dangerous to put directly aligned with the exit. It's more it should be more of a "by the way." We're a founder advisory firm. We need to keep those two things separate.

**Mohamed Anis:** So basically asymmetry.com is our advisory business. And within the advisory we have these four functions: raise, operate, exit and plan B. Acquire we decided not to make it a part of asymmetry.com — it will be a completely standalone separate website.
