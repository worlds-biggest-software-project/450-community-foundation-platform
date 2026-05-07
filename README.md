# Community Foundation Platform

> Part of the [worlds-biggest-software-project](https://github.com/worlds-biggest-software-project) initiative.
>
> An open-source, API-first platform for community foundations to manage funds, grantmaking, donor advised funds, and compliance reporting -- with AI-native capabilities that legacy vendors do not offer.

Community Foundation Platform is purpose-built software for the ~800 community foundations in the United States that collectively manage over USD 100 billion in assets. It replaces fragmented combinations of accounting software, spreadsheet-based fund accounting, and legacy CRM tools with a single integrated system covering fund management, grantmaking, donor advised fund (DAF) administration, and IRS compliance. The primary audience is foundation staff, fund advisors, grant applicants, and board members.

---

## Why Community Foundation Platform?

- **Incumbent lock-in at high cost.** The dominant platform (Foundant CommunitySuite) serves mid-to-large foundations well but is expensive relative to the capacity of smaller foundations (under USD 50M in assets), while the largest foundations outgrow its customisation limits.
- **No true all-in-one open-source option.** The only open-source grant management tool identified (Gandhi) lacks fund accounting, donor portals, DAF features, investment management, compliance reporting, and active maintenance.
- **Fragmented best-of-breed stacks.** Platforms like Foundation Cloud (NPact) and Give Interactive require external accounting (Sage Intacct, Financial Edge) and external CRM (Salesforce), creating data silos, manual reconciliation, and delayed fund statements.
- **Batch-updated portals erode donor trust.** Most systems provide fund advisors with batch-updated statements rather than real-time account data, falling short of the brokerage-quality access that high-net-worth donors expect.
- **No AI capabilities in incumbent products.** Only Fluxx offers basic AI document summarization; no platform uses historical grant outcomes to predict application success, models donor churn risk, or automates compliance checking.

---

## Key Features

### Fund Management

- Multi-fund accounting across all common fund types: DAFs, endowed, designated, field-of-interest, agency, scholarship, and operating funds
- Per-fund investment allocation, fee calculation, and distribution tracking
- Fund agreement storage and fund-level trial balance
- Unit value calculations for pooled investment portfolios with daily valuation and retroactive correction
- Configurable fee and cash management structures

### Grantmaking

- Competitive grantmaking: application portal, eligibility screening, review committee assignment, scoring rubrics, grant agreement generation
- DAF grant recommendation intake, IRS charity eligibility verification (TEOS API), approval workflow, and payment instruction generation
- Multi-tranche payment scheduling for multi-year grants
- Scholarship application and review process
- Grantee outcome reporting and impact synthesis

### Donor and Fund Advisor Portal

- Real-time self-service access to fund balances, transaction history, and account statements
- Grant recommendation submission through the portal
- White-label option with foundation branding and sub-branding for partner ecosystems
- Automated fund statement generation and distribution

### Compliance and Reporting

- IRS Form 990-PF schedule generation
- Expenditure responsibility tracking and UBIT analysis
- State charity registration status tracking
- Configurable compliance workflows that adapt to regulatory changes without redevelopment
- Audit trail and transaction logging across all operations

### Analytics and Community Impact

- Geospatial impact reporting: grants by geography, issue area, and population served
- Community needs assessment data integration
- Dashboard with fund and grant metrics
- Exportable charts and maps for annual reports and board presentations
- DEI analytics and grant distribution analysis

---

## AI-Native Advantage

Community Foundation Platform applies AI where incumbent products have no capability. Grant applications are text-heavy documents that AI can automatically summarize and extract key data from, reducing reviewer burden. Historical grant outcome data enables predictive models that suggest promising applications based on organisational strategy and applicant track record. Donor lifecycle analytics can predict fund advisor churn risk and recommend engagement strategies. Automated compliance checking flags potential issues in applications before staff review, and outcome reports from grantees can be synthesized into narrative impact stories without manual effort.

---

## Tech Stack & Deployment

The platform targets self-hosted and cloud deployment modes. The architecture is API-first, enabling integration with existing accounting systems (Financial Edge NXT, Sage Intacct, QuickBooks) and CRM platforms (Salesforce, Blackbaud CRM) via bidirectional sync. Key external integrations include the IRS Tax Exempt Organisation Search (TEOS) API for charity eligibility verification, investment custodian data feeds for portfolio tracking, and community data APIs (Census, CDC) for needs assessment. Role-based access control supports distinct interfaces for foundation staff, fund advisors, grant applicants, reviewers, and board members.

---

## Market Context

Approximately 800 community foundations in the United States manage over USD 100 billion in assets, with DAF assets specifically growing at double-digit rates for over a decade. The market is segmented: smaller foundations (under USD 50M) find incumbent platforms expensive, while the largest foundations outgrow customisation limits. Primary buyers are foundation executive directors and operations staff seeking to replace manual reconciliation workflows and provide real-time donor portal experiences. ([cof.org](https://cof.org/topic/donor-advised-funds), [peakgrantmaking.org](https://www.peakgrantmaking.org/insights/how-to-select-the-right-software-for-your-community-foundation/))

---

## Project Status

> This project is in the **research and specification phase**.  
> Contributions, feedback, and domain expertise are welcome.

---

## Contributing

We welcome contributions from developers, domain experts, and potential users.
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Important:** All contributions must be your own original work or clearly attributed
open-source material with a compatible licence. Copyright infringement and licence
violations will not be tolerated and will result in immediate removal of the offending
contribution. If you are unsure whether a piece of code, text, or other material is
safe to contribute, open an issue and ask before submitting.

---

## Licence

Licence to be determined. See [discussion](#) for context.
