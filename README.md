# Awesome-Email-Automation-Autoresponder

## Top Email Automation & Autoresponder Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Drip Campaigns, Behavioral Triggers & Self-Hosted Newsletter Automation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Email Automation & Autoresponders**. These tools help organizations send targeted email sequences triggered by subscriber actions—covering everything from simple welcome series to complex behavioral branching and multi-channel marketing automation.

**Examples** include Mailchimp, ActiveCampaign, Klaviyo, ConvertKit, GetResponse, Brevo, Mautic, Listmonk, Keila, and Dittofeed (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted email automation, open-source autoresponders, and community-driven marketing platforms—ideal for organizations seeking data sovereignty and avoiding per-subscriber pricing that punishes growth. The open-source landscape splits into **full automation platforms** (Mautic, Dittofeed) for behavior-based journeys, and **newsletter senders** (Listmonk, Keila) that prioritize deliverability and throughput over complex branching [citation:2][citation:13].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global email marketing software market is estimated at **$1.7B – $1.8B** (expanding to **$8B – $11B+** when including the broader marketing automation ecosystem), compounding at an annual growth rate of ~9%–14%. The sector exhibits a **barbell market dynamic**: it is consolidated at the top among a handful of heavyweight platforms (e.g., Mailchimp, Klaviyo, HubSpot) capturing massive market share, yet simultaneously fragmented across mid-market and edge niches driven by vertical specialization (creator economy, e-commerce) and the emergence of AI-native orchestration tools.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Description | Starting Pricing (Specific Tier) | Free Tier / Trial Limits |
|---------|------------------------------------|-------------|----------------------------------|--------------------------|
| **[Mailchimp](https://mailchimp.com/)** | **$12B Valuation** (Acquired by Intuit) / ~$1.3B ARR | Industry-standard email marketing platform with visual journey builder, segmentation, and extensive third-party app ecosystem. | **$13/month** (*Essentials*, 500 contacts, up to 5,000 monthly sends; Standard from $20/month) | **Free tier**: up to 250 contacts, 500 email sends/month (max 250 sends/day) |
| **[Klaviyo](https://www.klaviyo.com/)** | **~$6B Market Cap** (NYSE: KVYO) / ~$1.4B ARR | E-commerce-focused lifecycle automation platform with deep Shopify/e-commerce integrations and predictive analytics. | **$20/month** (500 active profiles, up to 5,000 monthly sends) | **Free tier**: up to 250 active profiles, 500 email sends/month |
| **[ActiveCampaign](https://www.activecampaign.com/)** | **$3B Valuation** (Series C) / ~$250M ARR | Automation-first platform specializing in complex multi-branch conditional triggers, CRM, and dynamic lifecycle messaging. | **$19/month** (*Starter* plan, 1,000 contacts; or $15/month billed annually) | **14-day free trial**: capped at 100 contacts, 100 total sends, 1 user seat |
| **[Brevo](https://www.brevo.com/)** | **$1B+ Valuation** (Unicorn) / ~$215M ARR | European multi-channel suite for transactional and marketing email, SMS, and WhatsApp with volume-based pricing. | **$9/month** (*Starter* plan, 5,000 emails/month; Standard automation from $18/month) | **Free tier**: 300 emails/day (~9,000/month), storage for up to 100,000 contacts |
| **[Kit](https://kit.com/)** *(formerly ConvertKit)* | **~$200M Valuation** / ~$50M ARR | Creator-centric email platform built for newsletters, digital commerce, audience tagging, and broadcast monetization. | **$39/month** (*Creator* plan, 1,000 subscribers; or $33/month billed annually) | **Free tier**: up to 10,000 subscribers with unlimited broadcasts (automations locked) |
| **[GetResponse](https://www.getresponse.com/)** | **~$120M Valuation** / ~$100M ARR | Comprehensive marketing platform with autoresponders, visual automation flows, landing pages, and webinars. | **$19/month** (*Starter* plan, 1,000 contacts; or $15.58/month billed annually) | **14-day full free trial** (auto-converts to Free plan: up to 500 contacts, 2,500 sends/month) |
| **[Moosend](https://moosend.com/)** | **Acquired by Constant Contact** / ~$4M+ ARR | Lightweight email automation and autoresponder platform offering visual workflows and predictive product recommendations. | **$9/month** (*Pro* plan, 500 subscribers, unlimited email sends) | **30-day free trial**: up to 1,000 contacts with unlimited email sends |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Mautic](https://github.com/mautic/mautic)** | [![Stars](https://img.shields.io/github/stars/mautic/mautic?style=social&color=white)](https://github.com/mautic/mautic/stargazers) | **The most powerful open-source marketing automation platform.** GPL-3.0, PHP. **~11k GitHub stars**, actively maintained [citation:6][citation:12]. **Visual campaign builder with conditional branching**, lead scoring, dynamic content, and multi-channel touchpoints beyond email. Native integrations with WordPress, Salesforce, and major CRMs. **Self-hosted edition is unrestricted and free**. Heavier to run than simple newsletter tools—requires proper server resources and has a steeper learning curve [citation:2]. **Best for teams wanting HubSpot-style automation depth without per-contact fees.** |
| **[Listmonk](https://github.com/knadh/listmonk)** | [![Stars](https://img.shields.io/github/stars/knadh/listmonk?style=social&color=white)](https://github.com/knadh/listmonk/stargazers) | **The most popular open-source newsletter and mailing list manager.** AGPL-3.0, Go. **~24k GitHub stars**, highest health score in 2026 comparisons [citation:6][citation:12]. **Single binary deployment** with PostgreSQL as the only dependency. High-performance architecture sends millions of emails from your own SMTP relay. Supports both transactional and bulk campaigns, public API for integrations, and dynamic templates. **Trade-off: no built-in drip sequences or behavioral triggers**—you write automation against the API and run it from cron [citation:10]. **Best for developers wanting a fast, lightweight newsletter sender with full relay flexibility.** |
| **[Keila](https://github.com/pentacent/keila)** | [![Stars](https://img.shields.io/github/stars/pentacent/keila?style=social&color=white)](https://github.com/pentacent/keila/stargazers) | **Modern EU-based newsletter tool with GDPR-first design.** AGPL-3.0, Elixir/Phoenix. **~2.2k GitHub stars**, actively maintained [citation:6][citation:7]. **Polished interface**—the most modern UX among open-source email tools. Sends through SES, SendGrid, Mailgun, Postmark, or any SMTP. **One welcome email per signup form**; multi-step automations are on the roadmap but not shipped as of late 2026 [citation:7]. Segments can filter on opens and clicks. Docker image available. **Best for EU teams prioritizing data sovereignty and a clean interface over complex automation.** |
| **[Dittofeed](https://github.com/dittofeed/dittofeed)** | [![Stars](https://img.shields.io/github/stars/dittofeed/dittofeed?style=social&color=white)](https://github.com/dittofeed/dittofeed/stargazers) | **Open-source customer engagement platform for automated journeys.** MIT licensed (permissive), Node.js/TypeScript. **~3k GitHub stars** [citation:11][citation:12]. **Low-code tools for message automation across multiple channels** including email, SMS, push, and WhatsApp. Powerful segmentation and personalization driven by user events and segments. Positioned as a self-hosted alternative to Customer.io, Braze, and Iterable. **Caveat: still pre-1.0 (alpha release tags)** [citation:9]. **Best for product-led teams wanting lifecycle messaging with MIT licensing and multi-channel support.** |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[phpList](https://github.com/phpList/phplist3)** | [![Stars](https://img.shields.io/github/stars/phpList/phplist3?style=social&color=white)](https://github.com/phpList/phplist3/stargazers) | **Veteran open-source newsletter tool, actively maintained since 2000.** AGPL-3.0, PHP. **~877 GitHub stars** [citation:12]. Handles lists, campaigns, bounce processing, and **basic scheduled autoresponders** (welcome sequences, date-based reminders). Extremely mature and stable with low resource footprint. **UI is dated** and advanced features require plugins [citation:2][citation:14]. **Best for non-profits and community organizations wanting proven reliability with basic automation.** |
| **[SendPortal](https://github.com/mettle/sendportal)** | [![Stars](https://img.shields.io/github/stars/mettle/sendportal?style=social&color=white)](https://github.com/mettle/sendportal/stargazers) | **Laravel-based newsletter platform with a modern UI.** Free and open-source. Integrates with AWS SES, Postmark, SendGrid, Mailgun, SMTP, and Mailjet. Multiple workspaces for agencies managing client campaigns. **Unlimited users, subscribers, and messages** [citation:2]. Smaller ecosystem than more established tools. **Best for PHP/Laravel teams wanting a modern-looking self-hosted sender.** |
| **[Mailtrain](https://github.com/Mailtrain-org/mailtrain)** | [![Stars](https://img.shields.io/github/stars/Mailtrain-org/mailtrain?style=social&color=white)](https://github.com/Mailtrain-org/mailtrain/stargazers) | **Node.js newsletter tool with triggered campaigns.** GPL licensed (no AGPL disclosure for SaaS). Subscription management, segmentation, and **medium-depth autoresponders** triggered by subscription events, RSS feeds, or schedules. **More capable than Listmonk for sequences**, less than Mautic [citation:14]. Community less active than 2020–2022 peak. **Best for JavaScript-centric teams comfortable extending the codebase.** |

**Frameworks for building custom systems**: Choose **Mautic** for the deepest open-source automation with visual branching and lead scoring , **Listmonk** for the fastest, most reliable newsletter sender with full relay flexibility , **Keila** for EU data sovereignty and a polished modern UI , and **Dittofeed** for MIT-licensed multi-channel lifecycle messaging —all without per-subscriber pricing that scales against you.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Email automation platforms handle subscriber PII and sending reputation; enforce double opt-in, clear unsubscribe mechanisms, and compliance with CAN-SPAM, GDPR, and applicable anti-spam regulations. **Self-hosted sending requires proper domain authentication (SPF, DKIM, DMARC) and IP warm-up**—misconfiguration leads to deliverability failures.
- **Open-source email automation requires matching the tool to your actual needs.** **Mautic** is the only open-source option with genuine visual branching and behavioral triggers, but it is heavy to run and has a steep learning curve [citation:2][citation:13]. **Listmonk and Keila have no built-in drip sequences**—Listmonk requires writing automation against its API and running from cron , while Keila offers only a single welcome email per form [citation:7][citation:10]. **Dittofeed fills the multi-channel gap with MIT licensing but is pre-1.0 (alpha)** [citation:9]. **AGPL licensing matters for SaaS resellers**: Listmonk, Mautic, Keila, and phpList all carry AGPL's network-use disclosure obligation—if you host them as a service for others, you must make modifications available [citation:13]. **Validate deliverability setup and automation requirements** before committing to any self-hosted tool.

---

**Made for growth marketers, lifecycle teams, and developers building email automation infrastructure.**  
Let's make email automation and autoresponders more open, deliverable, and subscriber-friendly.
