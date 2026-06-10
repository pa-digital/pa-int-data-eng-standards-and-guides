# Data Engineering Standards & Guides

A practical, organisation-ready repository for defining, governing, and scaling data engineering best practices. This repo provides a consistent foundation for onboarding, development standards, architecture principles, and reusable templates across data platforms.

Use this repository as a **single source of truth** for how data products, pipelines, and teams should operate.

---

## What’s included

- **Getting Started Guides**: Onboarding, developer setup, and first pipeline walkthroughs  
- **Reference Materials**: Architecture principles, naming conventions, data contracts, and glossary  
- **Standards**: Data modelling, quality, governance, security, and testing best practices  
- **Ways of Working**: Team ceremonies and onboarding processes  
- **Templates**: Ready-to-use templates for data products, pipelines, incidents, and documentation  

---

## Repository Structure
├── Docs/ 
│           │ 
│      ├── Getting-started/ 
│           │     ├── Developer-setup # Local environment setup, tools, and access
│           │     ├── First-pipeline # Guide to building your first pipeline
│           │     └── Onboarding # New joiner onboarding guidance
│           │     
│      ├── Reference/ 
│          │         ├── Architecture-principles # Core design principles (scalability, resilience, etc.)
│           │       ├── Data-contracts # Definition and usage of data contracts
│        │       ├── Glossary # Standard terminology across the platform
│           │        └── Naming-conventions # Naming standards for datasets, pipelines, etc.
│           │     
│      ├── Standards/  
│           │        ├── Data-modelling # Modelling patterns (e.g. dimensional, data vault)
│           │      ├── Governance # Ownership, stewardship, and compliance
│           │      ├── Quality # Data quality rules and validation approaches
│          │     ├── Security # Data security and access control standards
│           │      └── Testing # Unit, integration, and pipeline testing practices
│           │     
│      └── Ways-of-working/  
│           ├── Ceremonies # Agile ceremonies, rituals, and expectations
│           └── Onboarding # Team-specific onboarding processes
│
└── Templates/ 
      ├── Data-product # Data product definition template
      ├── Data-quality # Data quality rules and monitoring template
      ├── Design-doc # Technical design document template
      ├── Incident # Incident management and post-mortem template
      ├── Pipeline-spec # Pipeline specification template
      ├── PRD # Product requirements document template
      ├── Runbook # Operational runbook template
      └── Schema # Data schema definition template

— 

## How to use this repository 

### 1. Getting started 
- Begin with the **Getting-started** section for environment setup and onboarding 
- Follow the **First-pipeline** guide to understand standard pipeline patterns 

### 2. Building data products 
- Use **Templates** to ensure consistency in documentation and delivery 
- Follow **Standards** to align with engineering best practices 
- Reference **Data contracts** and **Naming conventions** to ensure interoperability 

### 3. Designing solutions 
- Apply **Architecture principles** when designing systems 
- Use **Design-doc templates** to document decisions clearly 
- Align with **Governance and Security standards** 

### 4. Operating and improving 
- Use **Runbooks** and **Incident templates** for operational excellence 
- Follow **Ways of Working** to ensure effective collaboration 
- Continuously improve using feedback loops and retrospectives 

— 

## Guiding Principles 
- **Consistency over customisation** – standard patterns reduce cognitive load 
- **Shift left on quality** – build validation and testing into pipelines early 
- **Data as a product** – treat datasets as owned, versioned, and documented assets 
- **Automation first** – minimise manual processes wherever possible 
- **Security by design** – embed access control and governance from the start 

— 

## Contributing 
We encourage contributions from all team members. 

When contributing: 
- Follow the **existing structure and naming conventions** 
- Use the appropriate **template** for new content 
- Ensure alignment with **standards and principles** 
- Submit changes via pull request with clear descriptions 

— 

## Who is this for? 
- Data Engineers building pipelines and platforms 
- Architects defining scalable data solutions 
- Analysts and Scientists consuming governed data 
- Product and Delivery teams working with data products 

— 

## Quick Start Checklist 

- Set up your development environment 
- Read architecture principles 
- Review standards relevant to your work 
- Use templates for all new artefacts 
- Align with naming conventions and data contracts 
