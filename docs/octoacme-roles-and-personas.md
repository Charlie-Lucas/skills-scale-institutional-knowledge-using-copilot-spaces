# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

**Changelog**: Expanded to include UX Designer, DevOps Engineer, Data Analyst, and Support Lead personas with handoff examples and onboarding guidance. See issue [#4](https://github.com/Charlie-Lucas/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) for details.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX Designer

### Role Summary
UX Designers research user needs, design intuitive interfaces, and validate that features are usable and accessible. They collaborate with Product Managers and Developers to ensure the user experience aligns with product goals.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specs
- Define user flows and interaction patterns
- Collaborate with accessibility and design system standards
- Validate implementations against design intent

### Goals
- Deliver user-centered, accessible designs
- Reduce friction and improve user satisfaction
- Maintain consistency across the product experience

### Typical Communication
- Weekly design reviews with Product and Engineering
- Design specs and handoff artifacts (Figma, mockups)
- User research findings and recommendations

### Interaction with Other Roles
- **Handoffs to Product Managers**: Share research insights during roadmap planning to inform prioritization decisions.
- **Handoffs to Developers**: Provide detailed design specs, assets, and prototypes at sprint planning; attend sprint reviews to validate implementation.
- **Escalations**: When user research reveals critical usability issues, escalate to Product Manager for scope/priority adjustments.
- **Ownership**: Accountable for design quality and user experience consistency. Shares responsibility with PdM for user satisfaction metrics.

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, infrastructure, and deployment systems. They enable reliable, automated releases and ensure observability and system health.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code and environment provisioning
- Monitor system performance, uptime, and alerts
- Implement security and compliance standards in deployment
- Support incident response and recovery

### Goals
- Minimize deployment lead time and failure rate
- Ensure high availability and reliability
- Automate repetitive operations tasks

### Typical Communication
- Release readiness reviews with PM and Developers
- Incident postmortems and runbooks
- Infrastructure and deployment status updates

### Interaction with Other Roles
- **Handoffs to Developers**: Provide deployment schedules, environment readiness, and rollback procedures before releases.
- **Handoffs to Project Managers**: Communicate release windows, downtime requirements, and deployment risks during planning.
- **Escalations**: When infrastructure issues block releases or cause outages, escalate to PM and coordinate stakeholder communication.
- **Ownership**: Accountable for deployment reliability and system uptime. Shares responsibility with Developers for production issues.

---

## Data Analyst

### Role Summary
Data Analysts collect, analyze, and interpret data to inform product decisions and measure outcomes. They collaborate with Product Managers and stakeholders to track metrics and uncover insights.

### Responsibilities
- Define and track key performance indicators (KPIs)
- Build dashboards and reports for stakeholders
- Conduct data analysis to support decision-making
- Validate data quality and instrumentation
- Identify trends, anomalies, and opportunities

### Goals
- Enable data-driven decisions across the organization
- Ensure accurate, timely access to key metrics
- Surface actionable insights from user and system data

### Typical Communication
- Weekly metric reviews with Product and Leadership
- Analysis reports and recommendations
- Data definitions and documentation

### Interaction with Other Roles
- **Handoffs to Product Managers**: Deliver insights and metric reports before prioritization and planning sessions.
- **Handoffs to Developers**: Define instrumentation requirements (events, logs) during feature planning; validate data accuracy post-release.
- **Escalations**: When data reveals unexpected issues (drop in key metrics, data integrity problems), escalate to PdM and PM immediately.
- **Ownership**: Accountable for data accuracy and metric definitions. Shares responsibility with PdM for measuring success criteria.

---

## Support Lead

### Role Summary
Support Leads manage customer support operations, triage escalations, and ensure customer issues are resolved effectively. They act as the voice of the customer within the product and engineering teams.

### Responsibilities
- Oversee support ticket triage and resolution
- Coordinate escalations to Engineering or Product
- Track support metrics (response time, resolution rate)
- Document common issues and solutions (knowledge base)
- Advocate for customers in product planning

### Goals
- Maintain high customer satisfaction and support quality
- Reduce time to resolution for customer issues
- Surface product improvements based on support trends

### Typical Communication
- Weekly support metrics and trends to PM and PdM
- Escalation handoffs to Developers for bugs or urgent issues
- Customer feedback summaries and feature requests

### Interaction with Other Roles
- **Handoffs to Developers**: Escalate critical bugs with reproduction steps and customer impact; coordinate on fixes and workarounds.
- **Handoffs to Product Managers**: Share customer feedback, support volume trends, and feature requests during roadmap reviews.
- **Escalations**: When customer-impacting issues require immediate action, escalate to PM and coordinate cross-team response.
- **Ownership**: Accountable for customer satisfaction and timely issue resolution. Shares responsibility with Product for addressing systemic issues.

---

## How to use these personas

### Assigning Owners on Project Artifacts
- **Project One-pagers**: Clearly identify the Project Manager (PM), Product Manager (PdM), and other key roles (e.g., Lead Developer, UX Designer) in the "Proposed team / roles" section.
- **During Initiation**: Assign a named owner for each role in the initiation checklist. This ensures accountability and clarifies communication channels.
- **Cross-functional Projects**: For projects requiring UX, DevOps, Data, or Support involvement, explicitly name those role owners during kickoff and update the RACI matrix.

### Roles Onboarding Checklist
Teams can copy this checklist into project repos (e.g., `.github/PROJECT_ROLES.md`) to track role assignments and onboarding:

```markdown
## Project Roles and Onboarding

- [ ] **Project Manager (PM)**: [Name] — Coordinates delivery, manages schedule and risks
- [ ] **Product Manager (PdM)**: [Name] — Defines outcomes, prioritizes backlog
- [ ] **Lead Developer**: [Name] — Implements features, reviews code
- [ ] **UX Designer**: [Name] — Designs user experience, validates usability
- [ ] **DevOps Engineer**: [Name] — Manages CI/CD, infrastructure, and deployments
- [ ] **Data Analyst**: [Name] — Tracks metrics, analyzes outcomes
- [ ] **Support Lead**: [Name] — Handles escalations, represents customer voice
- [ ] All roles have reviewed relevant OctoAcme process docs in `docs/`
- [ ] Communication cadence and channels established (Slack, standups, etc.)
- [ ] Key handoff points and escalation paths documented
```

### Using Personas in the Exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

