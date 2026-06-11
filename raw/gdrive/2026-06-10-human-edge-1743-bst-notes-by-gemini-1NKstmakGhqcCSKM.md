---
source: farmer/gdrive
farmed: 2026-06-11T00:00:00Z
drive_id: 1NKstmakGhqcCSKMZ4FXAa7xpLkBIV6BkRrK3DWtGhAo
title: Human Edge – 2026/06/10 17:43 BST – Notes by Gemini
mime_type: application/vnd.google-apps.document
folder: SUO Meeting Recordings
modified: 2026-06-10T20:44:38Z
owner: anis@human-edge.io
---

# Notes

Jun 10, 2026

## Human Edge

Invited: omarvaruna@gmail.com, Aaliya Mohamed (aaliyazahramohamed@gmail.com), wasimf@gmail.com, Mohamed Anis (anis@human-edge.io), jezimazahir@gmail.com

### Summary

Technical team discussions covered taxonomy frameworks and CRM integration setups for streamlined client data management.

**Taxonomy and System Setup**
Discussions emphasized linking feedback to specific ideal customer profiles and versioned strategies. Technical teams verified Supabase project configurations and established foundational data flows for client onboarding.

**CRM Integration Procedures**
Integration protocols for GoHighLevel were finalized, requiring webhook implementation and unique location identifiers. The team decided to standardize nine website forms for consistent synchronization into the central database.

**Deployment and Verification**
Testing protocols were established to ensure accurate tracking across production environments and notification portals. NiFi deployment pathways were verified to maintain environment consistency.

### Decisions

**Aligned**

- **CRM integration via webhooks** The CRM integration architecture is set to use webhooks to ensure that client forms automatically update the GoHighLevel CRM, replacing the need for manual updates.
- **Form-to-CRM integration requirement established** Every website form is required to automatically update contact information in the CRM and trigger an email notification upon submission.

### Next steps

- [Mohamed Rafique] Update Supabase Project: Reconfigure the current Supabase project settings. Ensure the appropriate project environment is active.
- [Mohamed Rafique] Execute Bash Command: Run the specified bash command to facilitate the integration setup. Follow the deployment instructions for the supervisor login.
- [The group] Enable Onboarding Multiplicity: Update the client onboarding process to support multiple documents, ICPs, and strategies. Link these inputs to the "who are we selling" and "what are we selling" pages in the AI studio.
- [Mohamed Rafique] Connect Go High Level CRM: Implement a webhook to sync database updates with the Go High Level CRM. Ensure that forms and documents update the CRM database automatically.
- [Mohamed Anis] Send API Key: Provide the necessary API key for the integration setup.
- [Mohamed Rafique] Run Test Contacts: Submit 3 test contacts to verify that Go High Level CRM receives the data correctly.
- [Mohamed Rafique] Confirm Form Updates: Verify that all 9 website forms successfully trigger updates in the CRM system.
- [Mohamed Rafique] Provide Form URL: Share the website URL containing all 9 forms for verification purposes.
- [Mohamed Rafique] Rename Website Forms: Label all 9 forms with unique names to facilitate tracking in the CRM.
- [Mohamed Rafique] Run Final Test: Execute a final verification test using unique identifiers to ensure the system is functioning as expected.
- [Mohamed Rafique] Deploy updates: Execute a commit and deployment via NiFi to website.p.com.
- [Mohamed Rafique] Reset email configuration: Delete the internal notification portal and redo the setup.
- [Mohamed Rafique] Test production: Initiate a new round of validation using the live production environment.

### Details

- **Login and Authentication Procedures**: Mohamed Anis and Mohamed Rafique troubleshoot an account login process by signing out of Gmail and performing verification via phone tapping.
- **Taxonomy Pilot Framework**: Mohamed Anis discusses the taxonomy pilot, emphasizing that feedback — including objections, rejections, and positive outcomes — must be explicitly linked to the specific Ideal Customer Profile (ICP) and the strategy being executed. Mohamed Anis notes that as strategies evolve (from initial iterations to V2 and V3 versions), feedback must be categorized against these specific variables to ensure it remains meaningful for the implementation.
- **Supabase Project Configuration**: Mohamed Rafique assists Mohamed Anis with accessing the Supabase product dashboard and verification protocols. Mohamed Anis provides instructions on utilizing bash commands, specifically `npx supabase login`, to manage the project and handle access tokens for deployment. They discuss the use of project API keys for managing non-public access.
- **Client Onboarding and Data Flow**: Mohamed Anis describes the "client binning and onboarding journey," which uses client-provided websites and documents to define products, services, and target audiences. This data serves as the foundation for the AI Studio, where approved documents should automatically transfer to sales and strategy pages. Mohamed Anis stresses the need for multiplicity at every stage of the onboarding process, ensuring the system can accommodate multiple ICPs, sub-ICPs, products, and strategies.
- **CRM Integration via GoHighLevel**: Mohamed Anis discusses the requirement to sync data from onboarding forms directly to the CRM to ensure the database remains updated. The CRM used is GoHighLevel; the technical implementation uses webhooks to automate this data transfer between the database and the CRM.
- **Symmetry Database Integration Setup**: Mohamed Anis guides the creation of a new integration within the Symmetry database. The process involves navigating to the "private integrations" section, creating an entry named "symmetry integration," and selecting all scopes. Mohamed Anis notes that they will provide the necessary API key later to finalize the connection.
- **Go High Level CRM Integration Setup**: Mohamed Anis instructs Mohamed Rafique on establishing a private integration with the Go High Level CRM system. They navigate to settings, access "other settings," and utilize the "learn more" button regarding the private integration token. Mohamed Anis emphasizes that the technical implementation requires using an API to ensure that whenever a user submits a form, the data is saved directly to the CRM.
- **CRM Location ID Configuration**: The participants discuss the technical requirements for the Go High Level integration, specifically the necessity of a Location ID. Mohamed Anis directs Mohamed Rafique to check the business profile location settings and mail settings to obtain this specific ID. Once a form is submitted, the update is visible at the contact level within the CRM.
- **Form Update Consistency and Testing**: Mohamed Anis requests that Mohamed Rafique run a test using three test contacts to confirm the synchronization between the website and the CRM. Every form on the website must consistently update the contacts using the same integration logic. Additionally, whenever a form is updated, an automatic email notification should be triggered to the CRM.
- **Website Form Audit**: Mohamed Anis seeks to confirm the total number of forms existing on the Symmetry website to ensure comprehensive integration coverage. Mohamed Rafique identifies that there are nine forms total. The consensus is to verify that all nine forms are properly connected to the CRM system.
- **Testing and Troubleshooting Protocols**: Mohamed Anis requests that Mohamed Rafique assign a unique name to each of the nine forms to facilitate accurate tracking during testing. They briefly address the footer news forms, with Mohamed Anis suggesting a selection of 17 items to manage them effectively. To finalize the verification, Mohamed Anis asks for another test using unique IDs and unique emails.
- **Email and Notification Portal Troubleshooting**: Mohamed Rafique and Mohamed Anis discuss technical issues regarding the internal notification email portal. Mohamed Anis suggests that the existing email conversation data is not correct and advises that they delete the current entries and redo the process to ensure data accuracy.
- **Deployment Process via NiFi**: Mohamed Anis instructs Mohamed Rafique to perform the commit and deployment through the NiFi system located at `nifi.local` and `website.p.com`. They confirm the requirement to commit these changes to the Symmetry environment.
- **Production Environment Testing**: Mohamed Anis requests that Mohamed Rafique initiate another round of testing specifically using the production website to verify system functionality.
- **Data Management and Forms**: Mohamed Rafique and Mohamed Anis address specific form details, including the processing of data regarding the acquisition of GCF and partner information.

### Transcript

Session ran 2:05:58. Key participants: Mohamed Anis, Mohamed Rafique.

Technical context:
- Database: Supabase (Symmetry project)
- CRM: GoHighLevel (via webhook integration)
- Deployment: NiFi at nifi.local, website.p.com
- Forms: 9 total on the Symmetry website, all requiring CRM sync
- Integration: Private integration token in GoHighLevel settings required Location ID from business profile
