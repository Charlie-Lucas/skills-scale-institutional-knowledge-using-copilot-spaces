# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Changelog**: Expanded to include UX Designer, DevOps Engineer, Data Analyst, and Support Lead personas with handoff examples and onboarding guidance. See issue #4 for context.

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
UX Designers create user-centered designs that balance usability, accessibility, and business goals. They research user needs, design interfaces, and validate solutions through testing and feedback.

### Responsibilities
- Conduct user research and synthesize findings into personas and user journeys
- Create wireframes, prototypes, and high-fidelity mockups
- Design accessible, inclusive interfaces aligned with brand standards
- Collaborate with Product and Engineering on feasibility and trade-offs
- Validate designs through usability testing and iterate based on feedback

### Goals
- Improve user satisfaction and task completion rates
- Reduce user friction and support escalations
- Ensure consistent, accessible experiences across products

### Typical Communication
- Design critiques and reviews with cross-functional teams
- User research readouts and insights presentations
- Design specs and style guides for handoff to developers

### Interaction with Other Roles
**Handoffs to Product Manager & Developers:**
- During planning: shares research insights and design proposals to inform scope and acceptance criteria
- Before development: provides design specs, assets, and interaction notes
- During implementation: reviews developer questions and design fidelity

**Escalation & Ownership:**
- Owns design decisions and rationale documentation
- Escalates accessibility or brand guideline issues to Product Lead
- Coordinates with PM when user feedback conflicts with business goals

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain infrastructure, CI/CD pipelines, and deployment automation. They enable reliable, secure, and efficient delivery of software to production.

### Responsibilities
- Design and maintain CI/CD pipelines and build automation
- Manage infrastructure as code (IaC) and cloud resources
- Implement monitoring, logging, and alerting systems
- Automate deployments and rollback procedures
- Collaborate on security, compliance, and performance optimization

### Goals
- Reduce deployment lead time and increase deployment frequency
- Improve system reliability and reduce incident response time
- Automate repetitive operations and reduce manual toil

### Typical Communication
- Release readiness reviews and deployment schedules
- Incident postmortems and infrastructure health reports
- Runbooks, playbooks, and infrastructure documentation

### Interaction with Other Roles
**Handoffs to Developers & Project Manager:**
- During planning: provides infrastructure requirements, deployment timelines, and capacity constraints
- Before release: coordinates deployment windows and communicates release schedules to PM
- Post-deployment: shares metrics, logs, and health checks with developers for validation

**Escalation & Ownership:**
- Owns infrastructure stability, deployment pipelines, and release automation
- Escalates capacity or security concerns to engineering leadership
- Coordinates with PM to prioritize infrastructure work alongside feature delivery

---

## Data Analyst

### Role Summary
Data Analysts collect, analyze, and interpret data to inform product and business decisions. They translate data into actionable insights and dashboards that measure success and guide strategy.

### Responsibilities
- Define key metrics and build dashboards to track product performance
- Conduct data analysis to identify trends, patterns, and opportunities
- Support A/B testing and experimentation design and analysis
- Collaborate with Product and Engineering to ensure data integrity
- Communicate findings through reports, visualizations, and presentations

### Goals
- Enable data-driven decision-making across teams
- Measure product success against defined metrics and OKRs
- Identify optimization opportunities and inform roadmap priorities

### Typical Communication
- Metric review meetings and quarterly business reviews
- Experiment results and analysis reports
- Data quality and instrumentation reviews with engineering

### Interaction with Other Roles
**Handoffs to Product Manager & Developers:**
- During initiation: works with PM to define success metrics and data collection requirements
- During development: provides instrumentation specs to developers for event tracking
- Post-launch: delivers analysis of feature performance and user behavior to PM

**Escalation & Ownership:**
- Owns metric definitions, data quality, and analysis accuracy
- Escalates data privacy or compliance issues to Legal/Security teams
- Coordinates with PM when data insights conflict with strategic direction

---

## Support Lead

### Role Summary
Support Leads manage customer support operations, triage escalations, and ensure users get timely, high-quality assistance. They bridge customer feedback to Product and Engineering teams to improve product quality.

### Responsibilities
- Oversee support ticket management and response time SLAs
- Triage and escalate critical issues to Engineering or Product
- Document common issues, workarounds, and knowledge base articles
- Analyze support trends and advocate for product improvements
- Train support team on new features and troubleshooting techniques

### Goals
- Maintain high customer satisfaction (CSAT) and low resolution times
- Reduce repeat issues through proactive communication and fixes
- Ensure support team has tools and knowledge to resolve issues independently

### Typical Communication
- Weekly support metrics reviews and trend analysis
- Escalation briefs and incident coordination with Engineering
- Release readiness sessions to prepare support for new features

### Interaction with Other Roles
**Handoffs to Product Manager & Developers:**
- During planning: shares customer pain points and top support issues to inform prioritization
- Before release: reviews new features and documentation to prepare support team
- Post-release: escalates bugs and usability issues to developers, provides customer impact context

**Escalation & Ownership:**
- Owns customer experience, support quality, and SLA adherence
- Escalates critical incidents and outages to DevOps/Engineering on-call
- Coordinates with PM to advocate for customer-reported improvements and fixes

---

## How to use these personas

### In project documentation and exercises
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

### Assigning owners in project one-pagers
When creating a project one-pager (see [Project Initiation Guide](./octoacme-project-initiation.md)):
- Identify which personas are needed for the project scope
- Assign a named individual to each role in the "Proposed team / roles" section
- Clarify primary vs. consulting roles (e.g., full-time developer vs. ad-hoc UX review)
- Document communication expectations for each role in the stakeholder plan

### During project initiation
- Review the personas relevant to your project during kickoff
- Ensure each role understands their responsibilities and interaction points
- Establish handoff schedules (e.g., UX designs due 1 week before sprint start)
- Clarify escalation paths and decision-making authority for each role

### Roles-Onboarding Checklist for Project Teams
Copy this checklist into your project repo to track role setup:

```markdown
## Project Roles Onboarding Checklist

- [ ] Identify all required roles for this project (reference octoacme-roles-and-personas.md)
- [ ] Assign named individuals to each role in the Project One-pager
- [ ] Document primary vs. consulting roles and expected time commitment
- [ ] Schedule kickoff meeting with all role owners
- [ ] Clarify handoff points and timing (e.g., UX → Dev, DevOps → PM for releases)
- [ ] Define escalation paths for each role (technical, priority, resource constraints)
- [ ] Share relevant documentation (roadmap, design files, runbooks) with each role
- [ ] Add role owners to communication channels (Slack, email lists, project board)
- [ ] Review role-specific goals and success metrics
- [ ] Confirm availability for standing meetings (standups, planning, retrospectives)
```

### Tips for effective role collaboration
- Keep handoff documentation in the project repo for easy reference
- Schedule regular syncs between interdependent roles (e.g., UX + PM, DevOps + Developers)
- Document decisions and trade-offs in the project README or decision log
- Revisit role assignments during retrospectives if collaboration isn't working smoothly


