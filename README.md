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
- **[Cass Information Systems](https://www.cassinfo.com/freight-audit-payment)**
  Industry-leading freight audit and payment provider processing tens of millions of invoices and tens of billions in spend annually; bank-backed security, global multi-mode coverage, and deep transportation cost analytics.
- **[Trax Technologies](https://www.traxtech.com)**
  AI-native global freight audit and spend management platform that audits 100% of invoices across modes, currencies, and regions with normalized data and advanced analytics.
- **[CT Logistics](https://www.ctlogistics.com)**
  Long-standing freight bill audit and payment specialist with proprietary FreitRater rating engine, pre- and post-audit services, and web-based reporting tools.
- **[nVision Global](https://corporate.nvisionglobal.com)**
  Global freight audit & payment and parcel audit provider using AI/ML for line-item validation, multi-mode processing, and operational business intelligence.
- **[ControlPay](https://www.controlpay.com)**
  European-focused managed freight audit solutions offering pre-audit, post-audit, self-billing, rate consultancy, and logistics BI for multinational shippers.
- **[PayCargo](https://paycargo.com)**
  Neutral online freight payment network accelerating cargo release through secure digital payments, AP automation, and multi-currency settlement for ocean, air, and logistics providers.
- **[Audintel](https://audintel.com)**
  AI-powered transportation spend management platform focused on 100% invoice audit, contract intelligence, recovery, and actionable logistics cost insights.
- **[RateLinx](https://www.ratelinx.com)**
  Automated freight audit & pay solution with real-time invoice-to-shipment matching, zero rate tolerance, GL coding, and multi-modal analytics.
- **[Green Mountain Technology](https://greenmt.wpengine.com)**
  Parcel- and LTL-focused freight bill audit and pay specialist (FedEx Certified FBAP provider) delivering high-volume net-bill reconciliation and carrier savings recovery.
- **[Data2Logistics](https://www.data2logistics.com)**
  Global freight audit and payment services with data normalization, business analytics, secure carrier payments, and multi-currency/multi-language support.
## Open-Source GitHub Projects
- **[Open TMS](https://www.opentms.co.uk/)** / related implementations
  Full open-source Transportation Management System with three-way freight audit, carrier invoice matching, LTL rating, EDI 210/810/820 support, AR/AP lifecycle, and financial reporting.
- **[FreightAudit (derekwden-droid)](https://github.com/derekwden-droid/freight_audit)**
  AI-powered accessorial charge detection for freight brokers; OCR + LLM analysis of delivery receipts to catch unauthorized lumper, detention, and other overcharges before payment.
- **[LoadPartner TMS](https://github.com/loadpartner/tms)**
  Open-source TMS built for freight brokers (Laravel + React) covering load management, dispatch, and operational workflows that integrate with audit and payment processes.
- **[Warp Tools](https://github.com/wearewarp/warp-tools)**
  Suite of free, self-hostable logistics systems including invoice & payment tracker, carrier management, rate management, and mini-TMS modules designed to replace spreadsheets.
- **[Mustangproject](https://github.com/ZUGFeRD/mustangproject)**
  Mature open-source Java library and toolkit for reading, writing, validating, and converting structured electronic invoices (ZUGFeRD/Factur-X, XRechnung, CII, UBL) — essential for automated freight e-invoice processing.
- **[S2P AI Audit](https://github.com/aswinakofficial/s2p-ai-audit)**
  Production-grade AI-powered three-way match engine (invoice vs PO vs goods receipt) using LLM document understanding combined with deterministic financial validation.
- **[Operational Cost Audit](https://github.com/ajmarsillo/operational-cost-audit)**
  SQL + Python analytics platform for detecting operational cost leakage, overbilling against contracts, and post-termination charges in vendor invoice data.
- **[OpenHaul](https://github.com/johnmonarch/OpenHaul)**
  Local-first open-source carrier verification and risk-scoring tool for brokers and shippers using public FMCSA data and packet checks.
- **[Vendor Invoice Intelligence System](https://github.com/manish930s/Vendor-Invoice-Intelligence-System)**
  ML-driven system that predicts expected freight costs and flags high-risk anomalous invoices for manual review.
- **[SmartAudit-LLM](https://github.com/Sourish-Kanna/SmartAudit-LLM)**
  Autonomous LLM-based auditing platform for financial documents (invoices in CSV/PDF) performing rule-based and reasoning validation.
- **[FreightAccrue](https://github.com/alexxxram25/freightaccrue)**
  Controls-first, agentic freight accrual engine with rate-card pricing, segregation-of-duties workflow, and reconciliation against later carrier invoices.
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

