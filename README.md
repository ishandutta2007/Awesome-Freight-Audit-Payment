# Awesome-Freight-Audit-Payment

## Top Freight Audit & Payment Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Freight Invoice Auditing, Carrier Payment, Spend Visibility & Transportation Cost Control*
**Last updated: August 2026**
This repository tracks notable **SaaS platforms** and **open-source projects** for **Freight Audit & Payment**. These tools audit carrier invoices against contracted rates, detect overcharges and duplicates, automate payments, allocate costs, and deliver actionable spend intelligence across all modes (truckload, LTL, parcel, ocean, air, rail).
**Examples** include Cass Information Systems, Trax Technologies, CT Logistics, nVision Global, ControlPay, PayCargo, Audintel, RateLinx, Green Mountain Technology, Data2Logistics (the category leaders).
**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom rate engines, three-way matching, AI-assisted audit, e-invoicing, and open logistics data processing — ideal for shippers, 3PLs, freight brokers, researchers, and developers building transparent transportation finance solutions.
Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.
## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)
## SaaS/Hosted Platforms

| Platform | Focus | Company size (revenue / valuation) | Pricing (starting tier) | Free tier / trial limits |
| :--- | :--- | :--- | :--- | :--- |
| [**ControlPay**](https://www.controlpay.com) | European-focused managed freight audit: pre-audit, post-audit, self-billing, rate consultancy, logistics BI | **~$2.0B** — parent Transporeon acquired by Trimble for €1.88B (2023) | Custom enterprise quote (modular managed FAP, part of Transporeon) | No free tier or trial — live demo available on request |
| [**PayCargo**](https://paycargo.com) | Neutral online freight payment network accelerating cargo release; AP automation & multi-currency settlement | **~$1.9B** — valuation per Sixth Street (2022); raised $290M+ from Insight Partners & Blackstone | **$14.95/transaction** (US payer account), **$19.50 Quick Pay**; **$295/year per user profile**; ~**3.8%** credit-card surcharge | No payer free tier (per-transaction fees apply); **vendor accounts free at $0** |
| [**Cass Information Systems**](https://www.cassinfo.com/freight-audit-payment) | Bank-backed freight audit & payment processing tens of millions of invoices and tens of billions in spend annually; global multi-mode coverage | **$187.9M** — FY2025 revenue (SEC 10-K); disburses $94B+ annually | Custom enterprise quote; typically **~1–2% of payment value** or per-invoice/transaction fees (no public rate card) | No free tier or trial offered — enterprise contract only |
| [**Data2Logistics**](https://www.data2logistics.com) | Global freight audit & payment; data normalization, business analytics, secure carrier payments | **$160–195M raised** — merged with Loop (2025); $3B+ payment volume | Custom enterprise contract; managed-FAP industry benchmark **~$1–5 per invoice** | No free tier or trial offered — enterprise contract |
| [**nVision Global**](https://corporate.nvisionglobal.com) | Global freight audit & payment and parcel audit using AI/ML line-item validation across ~190 countries | **~$101.4M** — est. annual revenue (ZoomInfo) | Custom enterprise quote; **per-invoice / per-transaction fees** | No free tier or trial offered — enterprise sales process |
| [**Trax Technologies**](https://www.traxtech.com) | AI-native global freight audit & spend management auditing 100% of invoices across modes, currencies, and regions | **Est. $17M–$226M** — annual revenue range (Latka/Growjo) | Custom enterprise quote; **per-invoice + monthly platform fees** scaling with shipment volume | No free tier or trial offered — enterprise sales process |
| [**CT Logistics**](https://www.ctlogistics.com) | Freight bill audit & payment with proprietary FreitRater® rating engine, pre- and post-audit services | **~$25–30M** — est. annual revenue (ZoomInfo) | **Monthly SaaS subscription + one-time rate-entry/auditing purchase fee** (custom quote) | No free tier or trial offered — subscription only |
| [**Green Mountain Technology**](https://greenmt.wpengine.com) | Parcel- and LTL-focused freight bill audit & pay (FedEx-certified FBAP provider), net-bill reconciliation | **~$22–26M** — est. annual revenue (Owler/ZoomInfo) | Custom enterprise contracts — typically serves shippers with **$10M+ annual parcel spend** | No free tier or trial offered — enterprise contract |
| [**Audintel**](https://audintel.com) | AI-powered transportation spend management; 100% invoice audit, contract intelligence & recovery | **~$3.5–58M** — est. annual revenue (Prospeo/Growjo) | **Contingency model: ~25–50% of recovered savings** (no upfront software cost) | No free tier or trial offered — engagement-based |
| [**RateLinx**](https://www.ratelinx.com) | Automated freight audit & pay; real-time invoice-to-shipment matching, GL coding, multi-modal analytics | **n/d** — private; no public revenue or valuation (Scottsdale, AZ) | **Fixed monthly subscription + minimal one-time implementation fee** ($0 professional-service fees; custom quote) | No free tier or trial offered — quote-based |

> **Notes:** Rows are sorted by company size (descending). Enterprise FAP providers price per invoice/transaction and rarely publish rate cards; figures above are the most specific published estimates as of August 2026 (sources: SEC filings, press releases, PayCargo Help Center, RateLinx pricing page, CT Logistics SaaS page, ZoomInfo/Growjo/Latka/Owler, industry FAP benchmarks).
## Open-Source GitHub Projects
*Sorted by GitHub stars (descending) — click a star badge to open that repo's stargazers page.*

- [**Mustangproject**](https://github.com/ZUGFeRD/mustangproject) [![Stars](https://img.shields.io/github/stars/ZUGFeRD/mustangproject?style=social&label=Stars&color=white)](https://github.com/ZUGFeRD/mustangproject/stargazers)
  Mature open-source Java library and toolkit for reading, writing, validating, and converting structured electronic invoices (ZUGFeRD/Factur-X, XRechnung, CII, UBL) — essential for automated freight e-invoice processing.
- [**LoadPartner TMS**](https://github.com/loadpartner/tms) [![Stars](https://img.shields.io/github/stars/loadpartner/tms?style=social&label=Stars&color=white)](https://github.com/loadpartner/tms/stargazers)
  Open-source TMS built for freight brokers (Laravel + React) covering load management, dispatch, and operational workflows that integrate with audit and payment processes.
- [**Open TMS**](https://github.com/fossabot/open-tms) [![Stars](https://img.shields.io/github/stars/fossabot/open-tms?style=social&label=Stars&color=white)](https://github.com/fossabot/open-tms/stargazers)
  Full open-source Transportation Management System (opentms.co.uk) with three-way freight audit, carrier invoice matching, LTL rating, EDI 210/810/820 support, AR/AP lifecycle, and financial reporting.
- [**OpenHaul**](https://github.com/johnmonarch/OpenHaul) [![Stars](https://img.shields.io/github/stars/johnmonarch/OpenHaul?style=social&label=Stars&color=white)](https://github.com/johnmonarch/OpenHaul/stargazers)
  Local-first open-source carrier verification and risk-scoring tool for brokers and shippers using public FMCSA data and packet checks.
- [**SmartAudit-LLM**](https://github.com/Sourish-Kanna/SmartAudit-LLM) [![Stars](https://img.shields.io/github/stars/Sourish-Kanna/SmartAudit-LLM?style=social&label=Stars&color=white)](https://github.com/Sourish-Kanna/SmartAudit-LLM/stargazers)
  Autonomous LLM-based auditing platform for financial documents (invoices in CSV/PDF) performing rule-based and reasoning validation.
- [**Operational Cost Audit**](https://github.com/ajmarsillo/operational-cost-audit) [![Stars](https://img.shields.io/github/stars/ajmarsillo/operational-cost-audit?style=social&label=Stars&color=white)](https://github.com/ajmarsillo/operational-cost-audit/stargazers)
  SQL + Python analytics platform for detecting operational cost leakage, overbilling against contracts, and post-termination charges in vendor invoice data.
- [**Vendor Invoice Intelligence System**](https://github.com/manish930s/Vendor-Invoice-Intelligence-System) [![Stars](https://img.shields.io/github/stars/manish930s/Vendor-Invoice-Intelligence-System?style=social&label=Stars&color=white)](https://github.com/manish930s/Vendor-Invoice-Intelligence-System/stargazers)
  ML-driven system that predicts expected freight costs and flags high-risk anomalous invoices for manual review.
- [**S2P AI Audit**](https://github.com/aswinakofficial/s2p-ai-audit) [![Stars](https://img.shields.io/github/stars/aswinakofficial/s2p-ai-audit?style=social&label=Stars&color=white)](https://github.com/aswinakofficial/s2p-ai-audit/stargazers)
  Production-grade AI-powered three-way match engine (invoice vs PO vs goods receipt) using LLM document understanding combined with deterministic financial validation.
- [**Warp Tools**](https://github.com/wearewarp/warp-tools) [![Stars](https://img.shields.io/github/stars/wearewarp/warp-tools?style=social&label=Stars&color=white)](https://github.com/wearewarp/warp-tools/stargazers)
  Suite of free, self-hostable logistics systems including invoice & payment tracker, carrier management, rate management, and mini-TMS modules designed to replace spreadsheets.
- [**FreightAccrue**](https://github.com/alexxxram25/freightaccrue) [![Stars](https://img.shields.io/github/stars/alexxxram25/freightaccrue?style=social&label=Stars&color=white)](https://github.com/alexxxram25/freightaccrue/stargazers)
  Controls-first, agentic freight accrual engine with rate-card pricing, segregation-of-duties workflow, and reconciliation against later carrier invoices.
- [**FreightAudit (derekwden-droid)**](https://github.com/derekwden-droid/freight_audit) [![Stars](https://img.shields.io/github/stars/derekwden-droid/freight_audit?style=social&label=Stars&color=white)](https://github.com/derekwden-droid/freight_audit/stargazers)
  AI-powered accessorial charge detection for freight brokers; OCR + LLM analysis of delivery receipts to catch unauthorized lumper, detention, and other overcharges before payment.
### Additional Strong Open-Source Options
- **Odoo Community TMS / Freight modules** — extensible ERP-based transport management with invoicing, vendor bills, and cost tracking (multiple community and commercial modules available).
- **EDI libraries and parsers** for 210 (Freight Invoice), 810, and 820 transactions commonly used in automated audit pipelines.
- **Rate engine and LTL rating open projects** for building custom contract compliance checks.
- **Invoice OCR + LLM pipelines** (many community notebooks and small repos) for extracting line-item charges from carrier PDFs.
- **InfluxDB + Grafana + Node-RED** stacks frequently combined with TMS data for spend dashboards and anomaly detection.
**Frameworks for building custom systems**: Combine **Open TMS / LoadPartner TMS**, **Mustangproject** (e-invoicing), **FreightAudit-style AI detectors**, **three-way match engines**, and **InfluxDB + Grafana** (or similar) with local LLMs for intelligent, self-hosted freight audit and payment platforms.
## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.
Star the repo if you find it useful!
## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Freight audit and payment tools must comply with applicable financial, tax, and transportation regulations.
- Self-hosted open-source solutions require proper security, audit trails, data protection, and reliability controls suitable for financial processes.
---
**Made for shippers, freight brokers, 3PLs, finance teams, and logistics technologists.**
Let's make freight audit and payment more open, accurate, and cost-effective.

