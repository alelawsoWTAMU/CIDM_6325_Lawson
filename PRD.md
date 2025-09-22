# Product Requirements Document (PRD)

## 1. Document Information
- Product/Feature Name: Home Maintenance Compass
- Author(s): Alexander J Lawson
- Date Created: 2025-09-21
- Last Updated: 2025-09-21
- Version: 0.1
---
## 2. Overview
- **Summary:**
  This tool is called the Home Maintenance Compass. It's purpose is to assist new homeowners in creating a personalized preventative maintenance, in addition to provided verified knowledge from nearby experts. The philosophy behind this tool is to prevent homeowners from having to make stressful and costly repairs by providing them an organized plan and access to local resources. The primary target audience are first-time buyers, specifically Millenials and Gen Z, who may never have received guidance or been mentored on what it takes to take care of a property.
  
- **Problem Statement:**
The problem we are trying to solve can be split into two parts: 1) new homeowners are often overwhelmed when it comes to taking care of their new property, which results in a reactive and stressful approach akin to whack-a-mole and 2) the advice they may get is very generic from strangers on the internet and said advice is not tailored to their specific situations or local climate.
- **Goals & Objectives:** 
  - Empower first-time homeowners to adopt a proactive approach to home maintenance.
  - Provide a methodical maintenance schedule based on a home's specific circumstances.
  - Create a community-driven knowledge base for localized tips and advice.
  - Reduce the likelihood of costly and stressful home repairs caused by neglect.

- **Non-Goals:**
The initial version of this product will not include features related to the automated ordering ordering of products or parts, e-commerce integration, professional contractor bidding, smart home device integration, or AI-driven diagnostics.

## 3. Context & Background
- **Business Context:** The product is tethered to the goal of fostering preventative home maintenance with the additional benefit of reducing insurance claims dealing with neglect. This initative would lower the volume of potential claims for both the customers and insurance providers.
- **Market/Customer Insights:** 
The persona of our target audience is first-time homeowners, particularly those in the Millennial and Gen Z generations. These individuals are digitally savvy and used to having any answer to any question at their fingertips. However, many report feelings of being blindsided by the practical realities posed by maintaining a home. They don't typically have a community of knowledgeable people they can ask questions and suffer from a consistent anxiety that their one hard asset, their home, could fall apart. According to a 2022 survey from Thumbtack, 80% of millennial homeowners and 81% of first-time buyers felt overwhelmed or stressed about upkeeping their homes amongst these generations.  Additionally, these individuals are concerned about their ability to stay financially solvent if something breaks. A May 2025 report from Kin Insurance articulated that 72% of Gen-Z and millennial first-time homebuyers encountered unexpected issues after moving in, at an average cost of over $5,000. When you factor in that most of the homes these people buy are fixer-uppers, you can understand their concern. Lastly, they feel anxious about being seen as incompetent when pursuing home repairs and some might report feeling uneasy about asking questions, if they even have someone to ask questions to. To summarize, they often feel daunted by home maintenance tasks. These individuals may not have had a mentor in "Homeownership 101" and find that reliable, specific information is scattered and unverified. There is also a market for budget-conscious users who want to extend the life of their systems and are interested in DIY solutions.

---
## 4. Scope
- **In Scope:**
  - A personalized maintenance schedule based on user inputs like home age, construction type, and climate zone.
  - Maintenance task profiles with step-by-step guides, required tools, and estimated time.
  - A localized tips module with user submission and upvoting functionality.
  - A digital log for key home information, trusted service providers, and links to articles/videos.
- **Out of Scope:** Bullet list of excluded items to prevent ambiguity.
  - Automated parts ordering or e-commerce integration.
  - Recommendations for replacement appliances or service providers based on environmental factors.
  - Professional contractor bidding or scheduling services.
  - Integration with smart home devices.
  - AI-driven diagnostics for maintenance issues.
---
## 5. User Stories & Use Cases
- **Primary User Persona(s):** First-time homeowners, budget-conscious homeowners, local community contributors and property managers.
- **User Stories:**
- As a new homeowner, I want a personalized maintenance schedule, so that I know what tasks I need to do and when to do them.
- As a DIY enthusiast, I want step-by-step guides for common tasks, and access to approachable and knowledgeable individuals, so that I can confidently and competently complete them myself.
- As a local community member, I want to provide and have access to useful tips, so that I can share my knowledge to help others and be helped if I require it.
- **Use Case Scenarios:** 
  - **Happy Path:** The ideal scenario is that a new, young homeowner creates a profile, inputs their home's details, and receives a schedule. For example, a user named John Doe would enter the home's age (1985), construction type (wood frame), her climate zone (Midwestern U.S.) and the ages of appliances.  The app would then create a customized schedule with weekly, seasonal or annual tasks such as “Clean the Gutters” or “Change the Air Filter”.  John would get a notification when it’s time to perform a task and it would have retired tools and a step-by-step guide.  They follow this schedule, marking tasks as complete, and use the task profiles for guidance on how to perform them. They would also browse the knowledge base and upvote tips for their community.
  - **Edge Cases:**
    - **A:** Jane Doe comes to own a unique, older home with a geothermal system and the app’s knowledgebase is not all that helpful because it’s an obscure home feature. When her profile’s created and the input is submitted, the scheduling tool struggles to create a schedule for her or provide any helpful information. The worst case scenario is that instead of improving the algorithm or admitting that the tool is not fully capable yet of assisting in this scenario, the app spits out a low quality result which runs the risk of a user receiving bad advice, which would run counter to the app’s overarching mission which is to reduce  stress and improve people’s situation.
    - **B:** John Doe II is an inexperienced new homeowner who attempts to use the app to solve his leaky faucet problem.  Using the Localized Tips Module, he sees a DIY suggestion with a lot of upvotes, which makes him feel secure in trying it for himself.  During the repair, something breaks (a burst pipe perhaps) which leads to substantial and expensive water damage.  The app would have an upfront and “bulletproof” disclaimer but that doesn’t prevent the user from browsing the unverified results and implementing them. This highlights the potential liability with crowd-sourced tips and the necessity of content moderation to confirm the quality of the content, as well as the need to promote a “consult a professional” advisory.

---
## 6. Functional Requirements
- FR-001: Requirement text
- FR-002: Requirement text
- FR-003: Requirement text/
> Tip: Tie each FR to a user story or acceptance criteria below.
---
## 7. Non-Functional Requirements
- Performance: e.g., p95 response time under 200 ms
- Scalability: expected load, growth assumptions
- Accessibility: WCAG targets, keyboard nav, color contrast
- Security/Compliance: authz/authn, data handling, PII, regulatory
- Reliability/Availability: SLOs, error budgets, degradation behavior
---
## 8. Dependencies
- Internal system dependencies
- External APIs/third-party services
- Cross-team deliverables
---
## 9. Risks & Assumptions
- Risks: Potential pitfalls and mitigation strategies.
- Assumptions: Preconditions believed to be true.
---
## 10. Acceptance Criteria
- Clear, testable conditions for acceptance.
- Example: FR-001 passes when a user uploads a file up to 100 MB within 3 s without
error.
---
## 11. Success Metrics
- KPIs or OKRs that indicate success (adoption %, NPS, revenue impact, error
reduction, task completion rate).
---
## 12. Rollout & Release Plan
- Phasing: MVP vs. future iterations.
- Release Channels: Beta, staged rollout, general availability.
- Training/Documentation Needs: Internal docs, support guides, user education.
---
## 13. Open Questions
- What are the necessary inputs to include in order to create a dynamic maintenance schedule to balance effectiveness and user effort?
- How do we incentivize local community contributors to contribute to the space and ensure a consistent flow of high-quality tips?

---
## 14. References
- Links to related PRDs, design records, ADRs, technical specs, or strategy docs.
  - [https://www.kin.com/blog/generational-homeownership-survey-2025/]
  - [https://www.opendoor.com/articles/homeseller-report]
  - [https://newsroom.bankofamerica.com/content/newsroom/press-releases/2025/07/confronted-with-higher-living-costs--72--of-young-adults-take-ac.html]
  - [https://blog.thumbtack.com/investing-in-home-maintenance-pays-off-yet-the-majority-of-homeowners-are-under-budgeting-84426995b6c5]
  - [https://www.thumbtack.com/guide/content/survey-home-maintenance-stress-454171293741948943.]
  - [https://partnerships.homeserve.com/water-solutions/millennial-homeowners-surprised-by-maintenance-costs-2/]
  - [https://talkerresearch.com/gen-z-millennials-fall-behind-on-this-home-necessity/]
- Example: FR-001 passes when a user uploads a file up to 100 MB within 3 s without
error.
