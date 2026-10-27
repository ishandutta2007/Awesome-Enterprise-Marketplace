# Awesome-Enterprise-Marketplace

# Top Enterprise Marketplace Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on App Store Platforms, Multi-Vendor Commerce & Self-Hosted Marketplace Infrastructure*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Marketplaces**. These tools enable organizations to operate digital storefronts where third-party vendors, developers, or partners can list and sell applications, services, or products—whether as internal app exchanges, B2B procurement hubs, or consumer-facing multi-vendor platforms.

**Examples** include ServiceNow Market Place, Salesforce AppExchange, AWS Marketplace, Azure Marketplace, Google Cloud Marketplace, Atlassian Marketplace, HubSpot App Marketplace, Shopify App Store, Zapier App Directory, and Workato Community Hub (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted multi-vendor commerce, app registry systems, and marketplace foundations—ideal for organizations building sovereign marketplace infrastructure without per-transaction fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Market Place](https://www.servicenow.com/)**  
  Enterprise app and agent marketplace on the Now Platform; the AI Agent Marketplace lists industry and function-specific agents (agentic contact centers for banking/insurance, data-quality analysis) built by ServiceNow and partners, inheriting native workflow, approval, and governance machinery; strongest catalog for ITSM, operations, and employee-service use cases .

- **[Salesforce AppExchange](https://appexchange.salesforce.com/)**  
  The oldest and most consolidated cloud marketplace (20+ years, 5,000+ apps); AppExchange now unifies Slack Marketplace and Agentforce ecosystem into AgentExchange, listing 1,000+ agents and skills including third-party sub-agents and MCP servers; partner agents are vetted for security with granular admin control over data boundaries .

- **[AWS Marketplace](https://aws.amazon.com/marketplace)**  
  B2B cloud marketplace with the widest selection across categories; hundreds of partner-built agents, tools, and solutions purchasable against existing AWS commitment agreements; procurement leverage allows agent spend to draw down committed cloud spend, though curation is broader and evaluation burden shifts to the buyer .

- **[Azure Marketplace](https://azuremarketplace.microsoft.com/)**  
  Microsoft's commercial marketplace for Azure-based solutions, apps, and services; integrates with Azure consumption commitments and provides co-sell capabilities for partners.

- **[Google Cloud Marketplace](https://cloud.google.com/marketplace)**  
  Google Cloud's marketplace for enterprise solutions, with validated partner listings and integration with Google Cloud committed spend.

- **[Atlassian Marketplace](https://marketplace.atlassian.com/)**  
  App marketplace for Jira, Confluence, and Atlassian ecosystem products; thousands of apps and integrations from third-party developers with cloud and data center deployment options.

- **[HubSpot App Marketplace](https://www.hubspot.com/apps)**  
  Integration marketplace for HubSpot CRM platform; apps are listed without requiring transactable status, though legal and security reviews are required before listing goes live .

- **[Shopify App Store](https://apps.shopify.com/)**  
  App marketplace for Shopify merchants; developers build apps that extend store functionality, with revenue sharing and review processes for listing.

- **[Zapier App Directory](https://zapier.com/apps)**  
  Integration directory for Zapier's automation platform; lists thousands of app connectors that enable workflow automation between SaaS tools.

- **[Workato Community Hub](https://www.workato.com/)**  
  Community-driven connector and recipe hub for Workato's enterprise automation platform; enables sharing of integration recipes and custom connectors.

## Open-Source GitHub Projects

- **[Medusa](https://github.com/medusajs/medusa)**  
  Open-source headless commerce platform (MIT) providing building blocks for digital commerce; modules can be customized to build advanced ecommerce stores, marketplaces, or any product needing foundational commerce primitives; all modules are open-source and freely available on npm; flexible architecture suitable for custom marketplace development .

- **[Mercur](https://github.com/avinaszh/mercur)**  
  Open-source multi-vendor marketplace platform built on MedusaJS (production-ready for B2C marketplaces as of v1.0); features vendor system, admin panel with commission/category/vendor management, vendor panel for seller product/order control, and B2C storefront; full ownership with no transaction fees or vendor lock-in; Node.js 20+, PostgreSQL, and Stripe/Resend integrations; installable via `mercur-cli` .

- **[Saleor](https://github.com/saleor/saleor)**  
  Open-source MACH ecommerce platform (BSD-3-Clause, 21.8k+ GitHub stars) with GraphQL-first API, 45+ dashboard mount points for UI extensions, and a full open stack including storefront, dashboard, and configurator; app ecosystem with webhook-driven, versioned apps for payments, CMS, search, and taxes; Agent Skills for AI-assisted commerce development; Docker-based local setup .

- **[Spree Commerce](https://github.com/spree/spree)**  
  Open-source API-first ecommerce platform (Ruby, 15k+ GitHub stars) supporting DTC, B2B commerce, multi-vendor marketplaces, and omnichannel; REST APIs, TypeScript SDKs, and production-ready Next.js storefront; self-hostable with no vendor lock-in or platform fees; official extensions for Stripe, Adyen, PayPal, Klaviyo, and Google Analytics .

- **[Bagisto](https://github.com/bagisto/bagisto)**  
  Free and open-source Laravel eCommerce framework for building and scaling online businesses; extensive module ecosystem including payment gateways (Stripe, PayPal, Mollie, Razorpay), shipping integrations (DHL, UPS, USPS, Canada Post), and marketplace-specific extensions; suitable for custom marketplace development on the Laravel stack .

- **[Mobazha](https://github.com/mobazha/mobazha)**  
  Open-source peer-to-peer commerce platform (v0.3.0-rc.1) separating storefront, discovery, checkout, and data ownership; sellers own their store and commercial history while connecting to shared markets; supports BTC, BCH, LTC, Zcash, and EVM networks including BNB Smart Chain with BEP-20 stablecoins; Go-based Node with embedded Web UI and API .

### Additional Strong Open-Source Options

- **Sharetribe Go** — The original open-source marketplace software (source-available) from Sharetribe; no longer actively maintained, but the codebase remains available for reference; Sharetribe now offers a Web Template as a starting point for client apps connecting to their Flex marketplace API .
- **Gerege Nexus App Store** — Modular app store distribution built on the Gerege Nexus platform (Go); includes registry for catalog publishing and signing, publisher studio for third-party app submission, review workflow, and SSO client management; demonstrates a modular approach to building enterprise app marketplaces .

**Frameworks for building custom systems**: Combine **Mercur** for a ready-to-deploy multi-vendor marketplace on MedusaJS with vendor and admin panels, **Saleor** for a MACH-architecture commerce engine with GraphQL and extensible dashboard, **Spree** for a proven Ruby-based marketplace foundation with B2B/B2C flexibility, and **Medusa** as the underlying commerce primitives layer for fully custom marketplace builds.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise marketplace platforms handling transactions and vendor data must comply with applicable regulations (PCI DSS for payments, GDPR for user data, marketplace-specific tax laws); vendor onboarding and payout workflows require careful financial controls.
- Self-hosted open-source solutions vary significantly in scope—Mercur provides a production-ready B2C marketplace, while Saleor and Spree offer commerce engines requiring more assembly; Sharetribe Go is no longer maintained and should not be used for new production deployments.
- Verify license terms for commercial use; Medusa uses MIT, Saleor uses BSD-3-Clause, Spree is open-source (check repository), and Mercur is open-source .

---

**Made for marketplace operators, ecommerce architects, platform engineers, and digital commerce leaders.**  
Let's make enterprise marketplaces more open, vendor-friendly, and transaction-efficient.
