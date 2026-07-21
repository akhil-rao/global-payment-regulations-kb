---
title: "Payment Services Regulations 2017"
country: "United Kingdom"
regulator: "Financial Conduct Authority (FCA)"
category: "Primary Legislation"
status: "Active"
effective_date: "2018-01-13"
last_updated: "2026-07-18"
topics: ["licensing", "open-banking", "consumer-protection"]
payment_systems: ["Faster Payments", "Bacs", "CHAPS"]
tags: ["payments", "regulation", "uk", "psr2017", "open-banking"]
---

# Payment Services Regulations 2017 (PSRs 2017)

## Executive Summary
The PSRs 2017 implement the EU's Second Payment Services Directive (PSD2) into UK law. They regulate payment service providers, establish the framework for Open Banking, and set strict rules on consumer rights, liability, and transaction transparency.

## Background
Introduced to replace the 2009 regulations, the PSRs 2017 were designed to increase competition in the UK payments market, enhance security (via Strong Customer Authentication), and mandate banks to share customer data with authorized third parties (Open Banking).

## Scope
Covers payment services provided in the UK, including account servicing, payment initiation, money remittance, and card-based payment instruments.

## Key Requirements
- **Authorization:** Firms must be authorized or registered by the FCA as an Account Information Service Provider (AISP), Payment Initiation Service Provider (PISP), or Electronic Money Institution (EMI).
- **Strong Customer Authentication (SCA):** Mandatory multi-factor authentication for most electronic payments.
- **Refund Rights:** Clear rules on unauthorized transactions and refund timelines.

## Compliance Obligations
- Maintain adequate safeguarding of client funds.
- Implement robust SCA and fraud detection mechanisms.
- Provide transparent pricing and execution time disclosures to consumers.

## Affected Institutions
- Banks, Building Societies, EMIs, AISPs, PISPs, and Card Issuers.

## Affected Payment Systems
- Faster Payments Service (FPS), Bacs, CHAPS.

## ISO 20022 Impact
The UK is actively migrating its domestic clearing systems (starting with Bacs and CHAPS, followed by FPS via the New Payments Architecture) to ISO 20022 to improve data richness and interoperability.

## API Impact
The PSRs 2017 are the legal foundation for **Open Banking** in the UK, mandating that the 9 largest banks provide standardized APIs for AISPs and PISPs to access account data and initiate payments.

## Operational Impact
Firms had to overhaul their authentication flows, upgrade API infrastructure for Open Banking, and update customer service protocols for fraud and dispute resolution.

## Reporting Requirements
- Regular regulatory reporting to the FCA (e.g., transaction volumes, fraud statistics, safeguarding audits).
- Incident reporting for major operational or security breaches.

## Compliance Timeline
- Initial compliance required by January 13, 2018.
- Ongoing adherence to FCA policy statements and SCA Regulatory Technical Standards (RTS).

## Exceptions
- Limited network exemptions (e.g., closed-loop payment systems like store cards) and minor payment exemptions may apply under specific FCA guidelines.

## Related Regulations
- [Electronic Money Regulations 2011](#)
- [FCA Guidance on Strong Customer Authentication](#)

## Official References
- [The Payment Services Regulations 2017 - UK Legislation](https://www.legislation.gov.uk/uksi/2017/752/contents)
- [FCA Payment Services and Electronic Money](https://www.fca.org.uk/firms/payment-services)

## Payment Labs Insight
**Pro-Tip:** When building Open Banking integrations in the UK, ensure your API flows strictly adhere to the OBIE (Open Banking Implementation Entity) standards. The FCA heavily scrutinizes AISP/PISP firms for "screen scraping" or non-compliant data handling.

## Revision History
| Date | Version | Description of Change | Author |
|------|---------|-----------------------|--------|
| 2026-07-18 | 1.0 | Initial draft created for Knowledge Base | Payment Labs |
