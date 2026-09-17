https://github.com/user-attachments/assets/79099e6f-80b4-48eb-a119-78aa8d71c444


# Parker Pizza — Salesforce B2B CRM & RevOps Implementation
Salesforce Pathfinder Capstone Project | ReDI School Germany

---

## Executive Summary
Parker Pizza transitioned from direct-to-consumer (D2C) retail to regional grocery store distribution (B2B). This implementation delivers an enterprise Sales Cloud architecture to manage complex, multi-stakeholder retail procurement, negotiate pricing tiers, and automate post-sale retail merchandising.

---

## Project Deliverables & Media
* **Interactive Presentation Deck:** [Launch Live Slide Portal](https://marianazgondal.github.io/parker-pizza-salesforce-b2b-crm/)
* **Executive Case Study:** [Download Implementation Report (PDF)](./Parker_Pizza_Salesforce_Implementation_Report.pdf)
* **Architecture Walkthrough:** [Watch Video Walkthrough](./walkthrough.mp4)

---

## Core Metrics & Technical Specifications
* **Data Architecture:** 10+ Custom Objects, Master-Detail & Lookup Relational Hierarchy
* **Sales Automation:** 3 Production Record-Triggered Flows (Naming Conventions, Exec Thresholds, Task Generation)
* **Security & Access:** 3 Profiles, 4-Tier Role Hierarchy, 6 Custom Permission Sets, strict Field-Level Security
* **Data Quality:** Validation Rules enforcing Wholesale Margin minimums and Tax Registration validation
* **Reporting & Analytics:** 15+ Custom Reports driving an Executive 4-Component RevOps Dashboard

---

## Business Process to Salesforce Architecture Mapping

| B2B Business Stage | Salesforce Object | Implementation Details |
| :--- | :--- | :--- |
| **Store Account Discovery** | Account | Parent-child account hierarchies modeling regional retail chains vs. local branch stores |
| **Buyer Outreach & Sourcing** | Lead & Contact | Standardized qualification stages with automated lead conversion criteria |
| **Tasting & Pitch Negotiation** | Opportunity (Stages 1-3) | Guided sales paths tracking margin expectations and shelf-space commitments |
| **Contract Finalization** | Opportunity (Closed Won) | Record-triggered automation updating billing status and securing commercial terms |
| **Merchandising & POS Support** | Campaign & Custom Asset | Automated task generation dispatching POS collateral and sample freezer displays |

---

## Automation Workflows (Flow Builder)
* **Standardized Opportunity Naming:** Triggered on creation/update to enforce `[Account Name] - [Deal Category] - [Fiscal Quarter]` naming standards.
* **Executive Margin Alerts:** Alerts executive leadership whenever opportunity revenue exceeds $50,000 or profit margin falls below the 18% threshold.
* **Post-Sale Onboarding Tasks:** Automatically assigns marketing and logistics setup tasks to field reps when an opportunity moves to Closed Won.

---

## Author & Salesforce Administrator
**Maria Naz**  
*Salesforce Certified Administrator & Agentforce Specialist*  
Location: Albertslund, Denmark  
Profiles: [LinkedIn Profile](https://www.linkedin.com/in/maria-naz-gondal/) | [Salesforce Trailblazer](https://www.salesforce.com/trailblazer/marianaz)
