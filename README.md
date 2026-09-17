Parker Pizza: Salesforce B2B CRM Implementation

Enterprise Sales Cloud & RevOps Solution for Regional Grocery Distribution

Salesforce Pathfinder Capstone Project | ReDI School Germany

📌 Executive Overview

Parker Pizza, a gourmet frozen pizza manufacturer, initiated a strategic transition from direct-to-consumer (B2C) sales into regional wholesale grocery distribution. B2B grocery procurement demands structured deal pipelines, complex margin tracking, sampling presentation sign-offs, and automated post-signing merchandising logistics.

This project delivers an end-to-end Sales Cloud implementation built with strict enterprise data governance, validation controls, and low-code Flow automation.

🎯 Key Project Metrics

Metric

Details

Data Architecture

10+ Custom Objects, Fields, and Junction Relationships

RevOps Automation

3 Modular Record-Triggered Flows (Zero legacy Process Builders)

Analytics

15+ Custom Reports & a 4-Component Executive Lightning Dashboard

Security Governance

3 Custom Profiles, 4 Role Hierarchies, 6 Modular Permission Sets

Data Integrity

100% Validated Data Loader migration with strict referential integrity

🚀 Live Links & Artifacts

🖥️ Interactive Presentation Deck (Live on GitHub Pages)

📄 Full Implementation Case Study Report (HTML)

📥 Executive PDF Download

🛠️ Technical Implementation Highlights

1. Data Model & Schema Architecture

Account Hierarchies: Modeled supermarket parent chains (e.g., corporate retail headquarters) and child branches (delivery and store manager locations).

Relational Design: Enforced referential integrity between Accounts, Opportunities, Sampling Campaigns, and Delivery Deliverables using Master-Detail and Lookup relationships.

2. Opportunity Lifecycle & Sales Path

Implemented a 5-stage customized sales cycle: Store Discovery ➔ Initial Outreach ➔ Product Pitch / Tasting ➔ Terms Negotiation ➔ Closed Won (In-Store Launch).

Enforced validation rules requiring unit wholesale margin calculations and store delivery frequencies before deals can advance to negotiation stages.

Configured Kanban views with real-time aggregate values per retail territory.

3. RevOps Flow Automation (Low-Code)

Standardized Naming Convention Flow: Automatically titles deals dynamically as [Account Name] - [Product SKU] - [Close Quarter] to ensure global search cleanliness.

High-Value Deal Escalation Flow: Automatically notifies RevOps leadership and sends Chatter alerts for contracts exceeding wholesale threshold volumes ($50k+).

Closed-Won Logistics Flow: Generates automated onboarding and merchandising collateral preparation tasks for the field support team upon deal execution.

4. Enterprise Security & Access Governance

Role Hierarchy: Modeled access reflecting regional directorates down to localized store account executives.

Organization-Wide Defaults (OWD): Configured Private OWD with explicit sharing rules.

Field-Level Security (FLS): Restricted wholesale cost margins and unit COGS fields to RevOps and executive profiles.

Permission Sets: Deployed 6 modular permission sets for specialized responsibilities (e.g., Campaign Authoring, Discount Overrides) to eliminate profile sprawl.

📊 Analytics & Reporting

Created 15+ operational reports consolidated into an Executive Lightning Dashboard:

Pipeline Velocity by Stage: Identifies deal stagnation in tasting presentation and margin negotiation phases.

Win/Loss Analysis by Retail Chain: Provides visibility into retailer margin objections.

Regional Distribution Penetration: Visualizes wholesale distribution density across geographic territories.

👤 Architect Profile & Credentials

Maria Naz

Salesforce Certified Administrator & Agentforce Specialist

Location: Albertslund, Capital Region of Denmark

Background: 5+ Years Commercial Banking Operations & Compliance Leadership

🌐 LinkedIn: linkedin.com/in/maria-naz-gondal

☁️ Trailblazer Profile: salesforce.com/trailblazer/marianaz

💻 GitHub: github.com/MariaNazGondal

📄 License & Attribution

Capstone project developed under the Salesforce Pathfinder Program in collaboration with ReDI School.
