# Awesome-Digital-Workplace-Integration

# Awesome-Digital-Workplace-Integration
**Top Digital Workplace Integration (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Employee Experience Platforms, Intranet Integration, ChatOps & Digital Front Doors*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Workplace Integration**. These tools enable organizations to connect employees with the systems, information, and people they need—from fully managed employee experience platforms with deep HRIS and ITSM integrations to self-hosted intranets and chat platforms that give organizations complete control over their digital workplace infrastructure.

**Examples** include Microsoft Viva, ServiceNow Employee Center, Slack, Simpplr, Workvivo, LumApps, Staffbase, Firstup, Moveworks, and Workday Everywhere (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, intranet, team collaboration, and open employee experience infrastructure. **Critical note**: Dedicated open-source digital workplace integration platforms are virtually nonexistent. The projects below cover adjacent capabilities—social intranets, team chat, and collaboration hubs—but none replicate the deep HRIS/ITSM orchestration of Microsoft Viva or ServiceNow Employee Center.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Workday Everywhere](https://www.workday.com/)**
  **Workday self-service embedded in Microsoft Teams and Slack** . Employees can query leave balances, request time off, update personal information, and receive notifications without opening Workday in a browser. Workday plans to deprecate the older Workday Assistant in 2027R2 in favor of the Workday Everywhere self-service agent . **Pricing**: Quote-only; bundled with Workday suite. **Free tier**: None. **Best for**: Workday customers wanting to surface HR self-service directly in employees' collaboration tools.

- **[Microsoft Viva](https://www.microsoft.com/microsoft-viva)**
  **Employee experience platform** integrated with Microsoft 365 and Teams, covering communications, knowledge, learning, and insights. Viva integrates with HR systems including Workday, SAP SuccessFactors, and ServiceNow . ServiceNow offers native integrations for Viva Connections and Teams to surface HR tasks and services . **Pricing**: Per-user licensing; quote-based for enterprise. **Free tier**: Limited Viva Connections available with certain M365 plans. **Best for**: Microsoft 365 organizations wanting employee experience capabilities natively within Teams and SharePoint.

- **[ServiceNow Employee Center](https://www.servicenow.com/)**
  **Unified employee portal** that aggregates tasks, approvals, and services from Workday, SuccessFactors, and other enterprise systems into a single "Integrated Action Center" . Native spokes pull to-do items from Workday and SuccessFactors; employees can approve or complete items without leaving ServiceNow . Integrates with Microsoft Teams, Slack, and Viva Connections for in-flow service requests . **Pricing**: Quote-only; bundled with ServiceNow HR Service Delivery. **Free tier**: None. **Best for**: enterprises wanting a single digital front door that orchestrates tasks across multiple backend systems.

- **[Slack](https://slack.com/)**
  **Channel-based messaging platform** with extensive app integrations for HR, IT, and workplace tools. ServiceNow provides Slack integration for requesting services in the flow of work . Workday Everywhere runs natively in Slack . **Pricing**: **Free** tier with limited message history; **Pro** at $8.75/user/month; **Business+** at $15/user/month; **Enterprise Grid** quote-only. **Free tier**: Yes, with 90-day message history and 10 integrations. **Best for**: teams wanting a flexible collaboration hub with broad third-party app support.

- **[Simpplr](https://www.simpplr.com/)**
  **AI-powered employee experience platform** with intranet and communications capabilities. Integrates with Workday for user syncing (matching by email, requires employee number) alongside Azure, Okta, and Google . **Pricing**: Quote-only; per-user models. **Free tier**: None. **Best for**: organizations wanting a modern intranet with strong HRIS sync and AI-powered content personalization.

- **[Workvivo](https://www.workvivo.com/)** (Zoom)
  **Employee communication and engagement platform** with social intranet features. Integrates with Slack, Workday, Microsoft Teams, Salesforce, and Google Drive . **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations wanting a social, engagement-focused intranet with broad integration support.

- **[LumApps](https://www.lumapps.com/)**
  **Employee experience platform** with 100+ third-party integrations. Connects Workday, SAP SuccessFactors, ServiceNow, Microsoft Teams, Slack, and Google Chat into a unified hub . Supports HR and time-off requests directly from the dashboard, plus AI-powered search across connected systems . **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises wanting a centralized hub that surfaces actions from multiple business systems.

- **[Staffbase](https://staffbase.com/)**
  **Employee communications and intranet platform** with deep Microsoft 365, Workday, and ServiceNow integrations. Connects at the platform level to M365, enabling frontline workers on personal devices to access SharePoint content and Workday payslips without individual M365 licenses . Workday integration covers profile sync, org hierarchy, and direct service access (payslips, time-off requests) . ServiceNow integration enables ticket creation and status checks from within the intranet . **Pricing**: Quote-only. **Free tier**: None. **Best for**: large, distributed enterprises with mixed desk and frontline workforces needing governed access to multiple systems.

- **[Firstup](https://firstup.io/)**
  **Workforce communications platform** for targeted multi-channel messaging to distributed and frontline employees. Integrates with Microsoft, Workday, and ServiceNow . **Pricing**: Quote-only. **Free tier**: None. **Best for**: organizations prioritizing personalized communications delivery across mobile, email, and digital signage.

- **[Moveworks](https://www.moveworks.com/)** (ServiceNow)
  **AI-powered employee support platform** with native integrations for ServiceNow, Workday, and Slack . Following ServiceNow's acquisition, the **Moveworks for Employee Center** plugin replaces the standard Virtual Agent with Moveworks' conversational AI, creating a unified support experience across enterprise systems . **Pricing**: Quote-only; requires licensing for both Moveworks and ServiceNow Employee Center . **Free tier**: None. **Best for**: ServiceNow customers wanting AI-driven conversational support that spans IT, HR, and other enterprise systems.

## Open-Source GitHub Projects

- **[HumHub](https://github.com/humhub/humhub)**
  **Open-source social network and intranet platform** (AGPL-3.0 for Community Edition) — **the most mature open-source social intranet** with GDPR-compliant hosting options and 80+ modules . **Features**: User profiles, Spaces (rooms/groups), activity streams, posts, comments, file management, Wiki, Messenger, Calendar, Polls, and OnlyOffice integration. Supports LDAP, SAML SSO, RESTful API, and translation into 40+ languages . **Tech stack**: PHP (Yii2 framework), MySQL/MariaDB. **Deploy**: Self-hosted or HumHub Cloud (SaaS). **Trade-off**: **Not a digital workplace integration platform**—it is a social intranet with community features. No native Workday/ServiceNow connectors or task orchestration across enterprise systems. **Best for**: organizations wanting a self-hosted social intranet for communications, collaboration, and community building.

- **[Mattermost](https://github.com/mattermost/mattermost)**
  **Open-source, self-hosted Slack alternative** (MIT for Team Edition; AGPL for some components) — **the leading open-source team messaging platform** with strong enterprise controls. **Features**: Channels, direct messages, file sharing, search, webhooks, and Slack-compatible APIs. Supports import of Slack channels, users, and theme colors . **Tech stack**: Go, React. **Deploy**: Self-hosted (Docker, Kubernetes) or Mattermost Cloud. **Trade-off**: **Messaging platform, not a workplace integration hub**—no native HRIS task orchestration or employee portal features. Integrations require webhooks or custom apps. **Best for**: organizations wanting a self-hosted, Slack-compatible messaging backbone with data sovereignty.

- **[Nextcloud Hub](https://github.com/nextcloud/server)**
  **Open-source content collaboration platform** (AGPL-3.0) — **a comprehensive self-hosted alternative to Microsoft 365 and Google Workspace** . **Features**: File sync and share, collaborative document editing (Nextcloud Office/Collabora), Talk (chat and video), Calendar, Mail, Deck (Kanban), and Collectives (team workspaces). Supports LDAP/AD, SAML SSO, and external storage integration . **Tech stack**: PHP, PostgreSQL/MySQL/SQLite. **Deploy**: Self-hosted or Nextcloud Cloud. **Trade-off**: **Collaboration suite, not an employee experience platform**—no native Workday/ServiceNow integration or employee task orchestration. **Best for**: organizations wanting a sovereign, self-hosted collaboration platform that replaces Microsoft/Google productivity suites.

- **[Raven](https://github.com/The-Commit-Company/raven)**
  **Open-source team messaging platform built on Frappe** (AGPL-3.0) — **a messaging tool with deep ERP integration**, not a general workplace hub. **Features**: Channels, direct messages, rich text, file sharing, threads, reactions, and AI agents for workflow automation. **Deep integration with Frappe apps**: share ERPNext documents with previews, trigger notifications on document events, perform workflow actions, and print documents within chats . **Tech stack**: Frappe Framework (Python), React, React Native. **Deploy**: Self-hosted or Frappe Cloud. **Trade-off**: **Ecosystem-locked**—value depends entirely on running ERPNext/Frappe HR. Not a general-purpose integration layer for Workday or ServiceNow. **Best for**: organizations already on the Frappe/ERPNext ecosystem wanting integrated team chat.

- **[Farik](https://github.com/SamoTech/Farik)**
  **Open-source HR platform for small teams** (MIT) — **an HRMS with a helpdesk, not a digital workplace integration platform**. **Features**: People directory, recruitment pipeline, employee helpdesk ticketing, attendance and leave, and dashboard analytics. Pro features include payroll, AI analytics, and mood pulse . **Tech stack**: Supabase (PostgreSQL), modern JavaScript. **Deploy**: Vercel (recommended) or self-hosted. **Trade-off**: **Narrow HR scope**—no intranet, no communications, no integrations with Workday or ServiceNow. The helpdesk is internal, not an enterprise service orchestration layer. **Best for**: small teams wanting a free, modern HR system with basic internal ticketing.

- **[TeamTalk](https://github.com/virjar/team-talk)**
  **Open-source instant messaging and office collaboration system** (license per repo) — **an early-stage messaging platform for private deployment**. **Features**: Private and group chat with rich text, images, voice, video, and files; reply, forward, edit, recall, read receipts, and multi-device sync; contacts, friend requests, group management, and full-text search . **Tech stack**: Kotlin Multiplatform, Ktor, Netty, PostgreSQL, RocksDB, Lucene. **Deploy**: Self-hosted (Docker). **Trade-off**: **Pre-release software**—the project explicitly states it is not recommended for production without review. No HRIS/ITSM integrations or employee portal features . **Best for**: developers wanting a self-hosted messaging foundation to customize for small organizations.

### Additional Strong Open-Source Options

- **Collab Hub** — Self-hosted intranet (one-time $1,299 fee, not OSI open source). Staff directory, news, documents, and pages. **Note**: Proprietary licensing despite "open source" marketing; WordPress-based . **Best for**: small businesses wanting a low-cost intranet without subscriptions.
- **Documize** — Self-hosted knowledge base and documentation platform (AGPL-3.0). Spaces, labels, search, enterprise auth. **Note**: Documentation tool, not an employee experience platform or integration hub . **Best for**: teams wanting a Confluence-style wiki.
- **Outline** — Team wiki and knowledge base (AGPL-3.0). Real-time editing, spaces, permissions, search. **Note**: Knowledge management, not workplace integration . **Best for**: organizations needing a modern, self-hosted wiki.

**Frameworks for building custom systems**: Combine **Mattermost** as the messaging backbone with **HumHub** for social intranet and community features, **Nextcloud Hub** for document collaboration, and **Raven** for ERP-integrated chat if already on Frappe—creating a self-hosted digital workplace stack. **None of these provide the HRIS/ITSM task orchestration** that ServiceNow Employee Center or Microsoft Viva deliver.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Digital workplace platforms handling employee data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls and audit logging.
- **The "integration platform" vs. "intranet" vs. "messaging tool" distinction is critical.** **Microsoft Viva, ServiceNow Employee Center, Simpplr, LumApps, Staffbase, Firstup, and Moveworks** are **integration platforms**—they connect to Workday, ServiceNow, and other systems to surface tasks, content, and services. **HumHub** is a **social intranet**—communications and community, not system orchestration. **Mattermost and Raven** are **messaging tools**. **Nextcloud Hub** is a **collaboration suite**. **Farik** is an **HRMS with helpdesk**. **Do not confuse a chat tool or intranet with a digital workplace integration layer.**
- **Dedicated open-source digital workplace integration platforms are virtually nonexistent.** No mature open-source project matches ServiceNow Employee Center or Microsoft Viva in scope (cross-system task orchestration, HRIS/ITSM connectors, employee service portal). **The projects listed here are adjacent tools**—intranet, chat, collaboration—that address fragments of the digital workplace. **Organizations needing genuine integration across Workday, ServiceNow, and collaboration tools will require SaaS or significant custom development.**
- **Workday Everywhere is a narrow but important integration.** It embeds Workday self-service in Teams and Slack for leave requests, profile updates, and notifications . **It is not a full employee experience platform**—for broader integration across multiple systems, ServiceNow Employee Center or Microsoft Viva are the commercial choices.
- **ServiceNow's acquisition of Moveworks is reshaping the integration landscape.** The **Moveworks for Employee Center** plugin replaces the standard Virtual Agent with Moveworks' conversational AI, creating a unified support experience across enterprise systems . **This is a significant capability**—but it requires licensing both Moveworks and ServiceNow Employee Center.
- **Pricing opacity is universal across commercial vendors.** Workday Everywhere, Microsoft Viva, ServiceNow Employee Center, Slack (Enterprise), Simpplr, Workvivo, LumApps, Staffbase, Firstup, and Moveworks all require sales contact for enterprise quotes. **Validate with direct vendor conversations against your actual integration scope.**
- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Employee data and workplace communications are sensitive**—ensure your hosting meets your organization's security and privacy requirements before deploying.

---

**Made for developers, IT teams, and organizations building transparent digital workplace solutions.**
Let's make Digital Workplace Integration more open, data-driven, and employee-friendly.
