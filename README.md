# Awesome-Banking-Customer-Onboarding

# Top Customer Onboarding (Banking) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Identity Verification, KYC/AML Compliance & Digital Account Opening*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Onboarding in Banking**. These tools verify customer identity, perform Know Your Customer (KYC) and Anti-Money Laundering (AML) checks, and automate the digital account opening process for banks, fintechs, and financial institutions.

**Examples** include Fenergo, Signicat, Mitek Systems, OneSpan, Entrust Identity, Jumio, Onfido, Persona, Trulioo, and ID-Pal (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosting, custom identity verification pipelines, and transparent KYC workflows — ideal for fintechs, neobanks, and developers building vendor-independent onboarding solutions. The open-source ecosystem offers strong building blocks for document recognition, face matching, and eKYC orchestration, though full end-to-end onboarding platforms remain largely commercial.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Fenergo](https://www.fenergo.com/)**  
  Client lifecycle management platform specializing in KYC, AML, and regulatory compliance for financial institutions.

- **[Signicat](https://www.signicat.com/)**  
  Digital identity and onboarding platform with eID, e-signature, and KYC solutions for regulated markets.

- **[Mitek Systems](https://www.miteksystems.com/)**  
  Mobile deposit and identity verification platform with document capture and biometric authentication.

- **[OneSpan](https://www.onespan.com/)**  
  Digital agreement and identity verification platform with e-signature, authentication, and fraud prevention.

- **[Entrust Identity](https://www.entrust.com/)**  
  Identity and access management platform with identity verification and onboarding capabilities.

- **[Jumio](https://www.jumio.com/)**  
  AI-powered identity verification platform with document verification, biometrics, and AML screening.

- **[Onfido](https://onfido.com/)**  
  Identity verification platform using document and biometric checks with real-time verification.

- **[Persona](https://withpersona.com/)**  
  Configurable identity verification platform with document, database, and biometric checks.

- **[Trulioo](https://www.trulioo.com/)**  
  Global identity verification platform covering 195+ countries with document, database, and biometric verification.

- **[ID-Pal](https://id-pal.com/)**  
  Identity verification solution with document, biometric, and database checks for regulated industries.

## Open-Source GitHub Projects

- **[CrystalBank](https://github.com/Crystal-Bank/crystalbank)**  
  Open-source, event-sourced core banking system with first-class customer onboarding. Features customer onboarding for natural persons and organisations, multi-layer maker-checker approval workflows, double-entry ledger, and multi-tenant isolation through embedded roles and permissions. Built in Crystal with PostgreSQL, Svelte frontend dashboard, and full audit trail via immutable events .

- **[Mifos X](https://github.com/openmf/mifos-x)**  
  Recognized digital public good, full core banking platform providing common functionalities for creating customers, managing wallets, savings and loan accounts, and maintaining the financial ledger. Backend APIs via Apache Fineract, web UI for staff, reporting plugin, and mobile apps for field operations and customer banking .

- **[Lerian Midaz](https://github.com/LerianStudio/midaz)**  
  Source-available composable core banking platform built around a double-entry ledger. Includes onboarding of organizations, ledgers, assets, portfolios, and accounts; CRM with field-level encryption and searchable hashing for PII; and Tracer for real-time transaction validation with CEL rule engine and hash-chained immutable audit trail. Go monorepo under Elastic License 2.0 .

- **[eKYC Verification Service (fashkl)](https://github.com/fashkl/eKYC)**  
  Spring Boot eKYC orchestrator that coordinates document verification, biometric (face match), address verification, and sanctions screening across four external microservices. Produces APPROVED / REJECTED / MANUAL_REVIEW decisions based on configurable business rules. Hexagonal architecture with retry logic (exponential backoff), rate limiting, and Swagger UI. Java 21, Spring Boot 3.5 .

- **[woovi-kyc](https://www.npmjs.com/package/woovi-kyc)**  
  Open-source React KYC wizard for opening accounts. Handles full onboarding UI: company data, address, document uploads, and representative information. Features CNPJ and CEP auto-fill via BrasilAPI, storage-agnostic file upload callbacks, and 5-step wizard. MIT licensed .

- **[FintechPlayer (Neobank)](https://github.com/madeindigio/FintechPlayer)**  
  Open-source neobank with separate individual and company onboarding flows. Web banking client for transactions, cards, payments, and memberships. Onboarding process follows specific steps to meet legal requirements, with identity verification and compliance review simulated in sandbox. Built on Swan's banking-as-a-service APIs .

- **[onboarding-customers-api](https://github.com/MuindiStephen/onboarding-customers-api)**  
  Java Spring Boot backend application for onboarding new customers with REST APIs. Monolithic application performing sign-up, email verification, sign-in, and JWT token generation. Deployed via Docker Compose with PostgreSQL .

- **[digital-onboarding-platform](https://github.com/Ayushkush1/digital-onboarding-platform)**  
  Modern web-based MVP for financial institutions enabling secure digital onboarding, KYC verification, and credit risk assessment. Built with Next.js, Supabase, and Tailwind CSS. Includes user and admin panels, rule-based scoring, and basic fraud detection .

### Additional Strong Open-Source Options

- **MiniAiLive Face Recognition & Liveness Detection** — NIST FRVT top-ranked face recognition and iBeta Level 2 certified liveness detection SDKs for Android, Windows, and Linux. Includes ID document recognition and face matching .
- **kby-ai ID Card Recognition SDK** — ID document recognition for ID cards, passports, and driver licenses across Android, iOS, and React. Supports auto-capture and eKYC automation .
- **Aadhaar Paperless Offline eKYC APIs** — Go-based APIs for Aadhaar offline eKYC using web scraping .
- **Porichita AI eKYC System** — Python-based eKYC application for face verification and enrollment with real-time detection and liveness testing, PyQt5 GUI .
- **Serverless eKYC Backend** — AWS Lambda-based eKYC backend for document verification with OCR analysis, database matching, and health checks. Python and MongoDB .
- **OpenIAM Platform** — Apache-licensed identity and access management implementing OAuth 2.0 and SCIMv2 .
- **go-iam** — Lightweight multi-tenant IAM server in Go with Google/Microsoft/GitHub OAuth, RBAC, and admin UI. Apache 2.0 .

**Frameworks for building custom onboarding solutions**: Combine **CrystalBank** or **Lerian Midaz** for core banking with built-in customer onboarding and maker-checker workflows . Use **eKYC Verification Service** as an orchestration layer coordinating document, biometric, address, and sanctions checks . Leverage **woovi-kyc** for a React-based onboarding wizard UI . For identity verification components, integrate **MiniAiLive** or **kby-ai** SDKs for document recognition and face liveness . Note that full enterprise onboarding platforms with global compliance coverage, real-time sanctions screening, and regulatory reporting remain primarily commercial offerings; open-source stacks provide strong building blocks for identity verification, orchestration, and core banking foundations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Customer onboarding tools must comply with KYC/AML regulations (FATF recommendations, local banking laws), data privacy regulations (GDPR, CCPA), and identity verification standards.
- Self-hosted open-source solutions require proper infrastructure, security hardening, and ongoing maintenance. Biometric data handling requires strict compliance with privacy regulations and secure storage practices.

---

**Made for fintech developers, banking engineers, compliance officers, and identity professionals.**  
Let's make customer onboarding more open, transparent, and accessible.
