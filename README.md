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

| Platform | Focus | Pricing (starting tier) | Free tier / trial limits |
| :--- | :--- | :--- | :--- |
| [**Cass Information Systems**](https://www.cassinfo.com/freight-audit-payment) | Bank-backed freight audit & payment processing tens of millions of invoices and tens of billions in spend annually; global multi-mode coverage | Custom enterprise quote; typically **~1–2% of payment value** or per-invoice/transaction fees (no public rate card) | No free tier or trial offered — enterprise contract only |
| [**Trax Technologies**](https://www.traxtech.com) | AI-native global freight audit & spend management auditing 100% of invoices across modes, currencies, and regions | Custom enterprise quote; **per-invoice + monthly platform fees** scaling with shipment volume | No free tier or trial offered — enterprise sales process |
| [**CT Logistics**](https://www.ctlogistics.com) | Freight bill audit & payment with proprietary FreitRater® rating engine, pre- and post-audit services | **Monthly SaaS subscription + one-time rate-entry/auditing purchase fee** (custom quote) | No free tier or trial offered — subscription only |
| [**nVision Global**](https://corporate.nvisionglobal.com) | Global freight audit & payment and parcel audit using AI/ML line-item validation across ~190 countries | Custom enterprise quote; **per-invoice / per-transaction fees** | No free tier or trial offered — enterprise sales process |
| [**ControlPay**](https://www.controlpay.com) | European-focused managed freight audit: pre-audit, post-audit, self-billing, rate consultancy, logistics BI | Custom enterprise quote (modular managed FAP, part of Transporeon) | No free tier or trial — live demo available on request |
| [**PayCargo**](https://paycargo.com) | Neutral online freight payment network accelerating cargo release; AP automation & multi-currency settlement | **$14.95/transaction** (US payer account), **$19.50 Quick Pay**; **$295/year per user profile**; ~**3.8%** credit-card surcharge | No payer free tier (per-transaction fees apply); **vendor accounts free at $0** |
| [**Audintel**](https://audintel.com) | AI-powered transportation spend management; 100% invoice audit, contract intelligence & recovery | **Contingency model: ~25–50% of recovered savings** (no upfront software cost) | No free tier or trial offered — engagement-based |
| [**RateLinx**](https://www.ratelinx.com) | Automated freight audit & pay; real-time invoice-to-shipment matching, GL coding, multi-modal analytics | **Fixed monthly subscription + minimal one-time implementation fee** ($0 professional-service fees; custom quote) | No free tier or trial offered — quote-based |
| [**Green Mountain Technology**](https://greenmt.wpengine.com) | Parcel- and LTL-focused freight bill audit & pay (FedEx-certified FBAP provider), net-bill reconciliation | Custom enterprise contracts — typically serves shippers with **$10M+ annual parcel spend** | No free tier or trial offered — enterprise contract |
| [**Data2Logistics**](https://www.data2logistics.com) | Global freight audit & payment; data normalization, business analytics, secure carrier payments | Custom enterprise contract; managed-FAP industry benchmark **~$1–5 per invoice** | No free tier or trial offered — enterprise contract |

> **Pricing note:** Enterprise freight-audit-and-payment providers price per invoice/transaction and rarely publish rate cards. Figures above are the most specific published estimates as of August 2026 (sources: PayCargo Help Center, RateLinx pricing page, CT Logistics SaaS page, Gartner Peer Insights, industry FAP benchmarks).
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

