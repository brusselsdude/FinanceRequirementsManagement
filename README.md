# 📋 FinTech / Banking Requirements Management Model -- Sparx Enterprise Architect

> End-to-end regulatory traceability model built in **Sparx Enterprise
> Architect (EA)**\
> Covering AML, KYC, PSD2, GDPR, Capital Requirements, Functional &
> Non-Functional Requirements.

------------------------------------------------------------------------

## 🚀 What This Repository Contains

This repository provides a complete **Requirements Management reference
model** for a regulated Financial Services / FinTech environment.

It demonstrates full traceability from:

-   📜 Laws & Regulations\
-   🏛 Business Requirements\
-   ⚙ Functional Requirements\
-   🔐 Non-Functional Requirements\
-   👤 User Stories\
-   🧩 System Features

All modeled using Sparx Enterprise Architect and delivered as an **XMI
file** for direct import.

------------------------------------------------------------------------

# 📦 How To Use This Model

## ▶ Step 1 -- Download the XMI File

Download:

    RequirementManagement.xml

## ▶ Step 2 -- Import into Sparx Enterprise Architect

1.  Open **Sparx Enterprise Architect**
2.  Create or open a project (.qea / .eapx)
3.  Right-click a root package
4.  Select:

```{=html}
<!-- -->
```
    Import/Export → Import Package from XMI

5.  Choose `RequirementManagement.xml`

All packages, diagrams, traceability links and tagged values will load
automatically.

------------------------------------------------------------------------

# 🏗 Model Structure

## 1️⃣ Laws & Regulations

Includes regulatory drivers such as:

-   Anti-Money Laundering (AML) Act\
-   GDPR & Data Protection Act\
-   PSD2 -- Payment Services Directive 2\
-   Basel III & CRR Capital Requirements\
-   FCA Consumer Duty

These regulations derive Business Requirements via traceability
connectors.

------------------------------------------------------------------------

## 2️⃣ Business Requirements

Examples:

-   BR001 -- Know Your Customer (KYC) Programme\
-   BR002 -- Transaction Monitoring\
-   BR003 -- Data Privacy & Consent Management\
-   BR004 -- Strong Customer Authentication\
-   BR005 -- Open Banking API Platform\
-   BR006 -- Capital Adequacy Reporting\
-   BR007 -- Consumer Outcome Monitoring

Each Business Requirement links back to regulatory obligations.

------------------------------------------------------------------------

## 3️⃣ Functional Requirements

### KYC & Onboarding

-   Identity Verification\
-   Beneficial Ownership Check\
-   Customer Risk Scoring\
-   PEP & Sanctions Screening\
-   Enhanced Due Diligence\
-   KYC Audit Trail

### Payments & Transaction Monitoring

-   Real-Time Transaction Screening\
-   Alert Generation & Case Management\
-   SAR Filing\
-   SCA Enforcement on Payments\
-   Open Banking Payment Initiation API

Parent-child decomposition is modeled using aggregation relationships.

------------------------------------------------------------------------

## 4️⃣ Non-Functional Requirements

Grouped into four quality domains:

### 🔐 Security

-   Data Encryption (At Rest & In Transit)\
-   Annual Penetration Testing\
-   Role-Based Access Control

### ⚡ Performance

-   Payment Processing Latency\
-   KYC Onboarding Throughput

### 🟢 Availability & Resilience

-   Core Banking Availability\
-   Disaster Recovery

### 📊 Regulatory Compliance

-   Audit Log Immutability\
-   Regulatory Reporting SLA

NFRs are linked to Business Requirements via dependency relationships.

------------------------------------------------------------------------

## 5️⃣ User Stories

Agile-format stories:

> "As a \[role\], I want to \[action\] so that \[benefit\]."

Examples:

-   KYC Review User Story\
-   SAR Filing User Story\
-   Consent Management User Story\
-   Biometric Payment Authentication Story

Each User Story is associated with Stakeholder roles and linked to
Functional Requirements.

------------------------------------------------------------------------

# 🔎 Traceability

The model demonstrates full traceability chains such as:

AML Act\
→ KYC Programme\
→ Identity Verification\
→ PEP & Sanctions Screening\
→ Customer Risk Scoring\
→ KYC Review User Story

This provides audit evidence aligned with:

-   ISO/IEC 29148 Requirements Engineering\
-   FCA SYSC guidelines\
-   Regulatory compliance best practices

------------------------------------------------------------------------

# 🎯 Intended Audience

-   Enterprise Architects\
-   Solution Architects\
-   Compliance Teams\
-   Regulatory Reporting Teams\
-   Product Owners\
-   FinTech Platforms\
-   Core Banking Transformation Programs

------------------------------------------------------------------------

# 🛠 Modeling Approach

-   Built in Sparx Enterprise Architect\
-   Uses requirement decomposition via aggregation\
-   Uses «derives» and «trace» connectors for traceability\
-   Includes requirement attributes (Priority, Status, Author)\
-   Designed for regulated financial institutions

------------------------------------------------------------------------

# 🔐 Credits

Architecture & modeling by:

👉 https://nilus.be

Enterprise Architecture \| Regulatory Compliance \| FinTech Architecture
\| Sparx EA \| Requirements Traceability

------------------------------------------------------------------------

© 2026 FinTech Requirements Management Model
