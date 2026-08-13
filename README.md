# Awesome-Supply-Chain-Sustainability

## Top Supply Chain Sustainability Platforms



A curated list of leading platforms for supply chain sustainability, ESG risk and performance management, supplier due diligence, carbon/Scope 3 accounting, responsible sourcing, and regulatory compliance (CSDDD, LkSG, EUDR, etc.).  

**Primary focus: open-source software.**



Commercial / hosted platforms are listed separately for completeness. Open-source alternatives and community tools are emphasized throughout.



---



## SaaS / Hosted Platforms



| Platform | Company Size (Revenue / Valuation) | Description | Key Focus | Pricing | Free Tier / Trial Limits |
|----------|-----------------------------------|-------------|-----------|---------|--------------------------|
| **[Intertek Inform](https://www.intertek.com/)** | **≈$4.3B revenue** (FY2024; public, LSE: ITRK) | Assurance, testing, and supply chain sustainability solutions including audit programs, risk tools, and compliance support. | Assurance & audit-driven sustainability | Custom quote based on scope, location & facility count; Standards document packages separate | No free trial for assurance platform (select free downloadable PDF standards available) |
| **[osapiens HUB](https://osapiens.com/)** | **>$1B valuation** (unicorn, Series C 2026) | Supplier intelligence and compliance platform supporting due diligence (LkSG, EUDR, etc.), onboarding, risk monitoring, and multi-tier transparency. | Supplier intelligence & due diligence | CMMS Essential from €29/user/month; Premium from €49/user/month; ESG/LkSG custom quote | CMMS Starter plan free up to 5 users & 10 work orders/month; 14-day free trial on CMMS Premium |
| **[Assent](https://www.assent.com/)** | **>$1B valuation** (unicorn, Series D 2022) | Supply chain sustainability and compliance platform helping manufacturers manage regulatory obligations, product compliance, and ESG data across complex supplier networks. | Product & supply chain compliance | Enterprise quote-based (custom per network complexity); Free ASP supplier portal | No free trial (guided demo available); Free ESG risk assessment tool |
| **[EcoVadis](https://ecovadis.com/)** | **≈$1B valuation** (2022) | Leading provider of business sustainability ratings. Assesses suppliers on Environment, Labor & Human Rights, Ethics, and Sustainable Procurement with industry benchmarking and scorecards. | Supplier ESG ratings & benchmarking | Basic plan from €490/year; Premium plan from €990/year | No free plan/trial; 6-week free questionnaire period for invited suppliers |
| **[IntegrityNext](https://www.integritynext.com/)** | **Valuation n/d** — €100M raised (EQT Growth, 2023) | Supply chain due diligence and ESG risk platform with automated risk detection, supplier engagement, regulatory coverage (CSDDD and more), and AI-driven supplier intelligence. | Due diligence & regulatory compliance | Customer plan from €9,800/year; Free for invited suppliers | 14-day free trial (evaluations auto-expire after 14 days) |
| **[Sedex](https://www.sedex.com/)** | **≈$181M est. valuation** / $60M est. ARR (2025) | Collaborative platform for sharing responsible sourcing data, audits, and sustainability performance among buyers and suppliers. | Responsible sourcing data sharing | Supplier Standard from £224/year (Plus at £374/year); Buyer tier quote-based by turnover | No free trial or free tier (SMETA audits billed separately by third parties) |
| **[Prewave](https://www.prewave.com/)** | **≈$132M est. valuation** / $44M est. ARR (2025) | AI-powered supply chain risk and sustainability monitoring platform that detects risks from news, social, and other signals across multi-tier supply chains. | Real-time risk intelligence | Tiered custom quote (est. from ~€249/month for entry risk monitoring modules); Supplier basic access free | No standard public free trial (PoC / site-contribution trials under formal setup) |
| **[Worldly](https://worldly.io/)** (formerly Higg) | **≈$60M raised** (Series B, 2022) | Sustainability measurement platform widely used in apparel and consumer goods for environmental and social impact assessment across the value chain. | Industry impact measurement (apparel focus) | Facility Light plan from $299/year; Standard plan from $899/year; Complete plan from $1,499/year | No free trial; 5-unit exploration cap on Higg MSI tool |
| **[Achilles](https://www.achilles.com/)** | **≈$60M est. revenue** (private) | Supplier management and sustainability platform providing qualification, risk assessment, and ESG performance insights for procurement teams. | Supplier qualification & risk | Free Member tier; Silver upgrade from €510/year; Silver Plus from €750/year (Audits billed separately) | Free forever basic Member tier (up to €50k contract threshold) |
| **[Source Intelligence](https://www.sourceintelligence.com/)** | **≈$15M est. revenue** (2024) | Supply chain compliance and ESG data management platform focused on regulations (PFAS, REACH, RoHS, EUDR, conflict minerals, etc.) with automation and supplier engagement. | Regulatory compliance & materials data | Enterprise custom quote based on scope & supplier network size | No free trial (product demo upon request) |

> **Company size figures:** Public companies are shown by annual revenue (e.g. Intertek FY2024 results). Private companies are shown by disclosed valuation where available, otherwise by estimates from public sources (marked *est.*) or total funding raised as a proxy. Figures are approximate, rounded, and indicative.



---



## Open-Source Softwares



Fully featured commercial-grade supplier ESG rating networks and multi-tier due diligence platforms are scarce in pure open source. Stronger open-source building blocks exist for carbon accounting (especially Scope 3), emissions reporting, sustainable finance tools, and ERP-integrated sustainability modules.



### Core Frameworks & Sustainability Platforms



| Project | Description | License | Notes |
|---------|-------------|---------|-------|
| **[blockchain-carbon-accounting](https://github.com/hyperledger-labs/blockchain-carbon-accounting)** (Hyperledger) | Open-source blockchain applications for climate action and accounting: emissions calculations, carbon trading, validation of climate claims, and supply-chain decarbonization components. | Open source | Climate & carbon accounting on ledger |
| **Carbon accounting toolkits** | Open-source AI agents and MCP toolkits for auditable Scope 1/2/3 carbon accounting, emission factor matching, data quality scoring, and decarbonization workflows. | Apache-2.0 / various | Scope 3 & audit-ready carbon tools |
| **[Sustainability Odoo modules](https://github.com/sustainability-suite/sustainability-odoo)** | Open-source Odoo modules for CO₂e tracking, GHG Protocol-aligned accounting, CSRD-related features, emission factors, and sustainability reporting integrated with ERP. | AGPL-3.0 | ERP-native sustainability |
| **Supply chain sustainability reporting projects** | Python-based open projects for calculating and reporting distribution-network or logistics CO₂ emissions, often with Power BI or dashboard examples. | Various | Practical emissions reporting |
| **OS-Climate & sustainable finance tools** | Open-source initiatives for climate-smart investing, risk management, and ESG data handling (part of broader sustainable finance ecosystems). | Open source | Climate risk & finance |
| **Open supply chain visualization** | Open codebases for visualizing and analyzing supply chains (e.g., Sourcemap-related open components). | Various | Transparency & mapping |



### Specialized Libraries & Related Tools



| Project | Description | Focus Area |
|---------|-------------|---------|
| **Emission factor databases & calculators** | Open libraries and datasets for GHG emission factors, activity-based calculations, and Scope 3 category support. | Carbon calculation |
| **Input-output & LCA tools** | Open economic input-output and life-cycle assessment packages for estimating supply-chain impacts. | Impact estimation |
| **ESG data & reporting frameworks** | Open resources and code for aligning with CSRD/ESRS, GHG Protocol, and related disclosure standards. | Regulatory reporting |
| **Risk & news monitoring prototypes** | Open NLP and scraping approaches for basic supplier risk signal detection (far less mature than commercial AI platforms). | Risk signals |
| **ERP & procurement integrations** | Modules and connectors for Odoo, ERPNext, and similar systems to track sustainability attributes of purchases and suppliers. | Operational integration |
| **Dashboarding** | Metabase, Apache Superset, or Grafana on top of emissions and supplier data for internal sustainability scorecards. | Visualization & KPIs |



### Additional Notable Open-Source Tools



- **Self-hosted carbon accounting** — Combine open Scope 1/2/3 engines with internal activity data for auditable inventories.

- **ERP sustainability extensions** — Use Odoo sustainability modules or similar ERPNext customizations for operational CO₂ tracking.

- **Blockchain pilots** — Experiment with Hyperledger-based carbon accounting and tokenized claims for transparency projects.

- **Reporting pipelines** — Python + open BI stacks for logistics, procurement, and product-level emissions reports.

- **Data standards & taxonomies** — Open alignment with GHG Protocol, product category rules, and emerging digital product passport concepts.

- **Hybrid approaches** — Many organizations use commercial platforms (EcoVadis, IntegrityNext, etc.) for supplier ratings and due diligence while running open-source tools for internal carbon accounting and custom reporting.



**Note:** Commercial platforms dominate supplier ESG ratings, multi-tier due diligence, regulatory content libraries, audit networks, and real-time risk intelligence because these require large supplier networks, proprietary data, and continuous regulatory updates. Open-source strength lies in carbon accounting, emissions calculation engines, ERP-integrated sustainability modules, and transparent reporting pipelines that organizations fully control.



---



## Quick Start Recommendations



| Goal | Recommended Starting Point |
|------|---------------------------|
| Open-source carbon / climate accounting | **blockchain-carbon-accounting** or dedicated Scope 1/2/3 toolkits |
| ERP-integrated CO₂ & sustainability | **Sustainability Odoo modules** |
| Practical logistics emissions reporting | Community Python supply-chain sustainability projects |
| Supplier ESG ratings & benchmarking | **EcoVadis** |
| Supply chain due diligence & CSDDD | **IntegrityNext** or **osapiens HUB** |
| Product & regulatory compliance | **Assent** or **Source Intelligence** |
| Real-time multi-tier risk signals | **Prewave** |
| Responsible sourcing data sharing | **Sedex** |
| Apparel / consumer goods impact | **Worldly** |
| Supplier qualification & risk | **Achilles** |



---



## Contributing



Contributions, corrections, and new open-source projects are welcome.  

Please open an issue or pull request.



---



**Last updated:** August 2026  

Emphasizing open-source tools while documenting the major commercial platforms for context. Fully featured open-source supplier ESG rating and due-diligence networks remain limited; the strongest open options focus on carbon accounting, Scope 3 calculation, ERP sustainability modules, and transparent reporting pipelines. Commercial platforms lead in network-scale supplier ratings, regulatory coverage, and risk intelligence.

