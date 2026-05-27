# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

### Key Interactions
- **With UX Designer**: Collaborate on design feasibility and implementation details
- **With QA/Testing**: Coordinate on test requirements and bug resolution
- **With Release Manager**: Provide deployment readiness status
- **With Data Analyst**: Integrate instrumentation for metrics collection

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

### Key Interactions
- **With UX Designer**: Align on user needs and feature requirements
- **With Data Analyst**: Review metrics and validate hypothesis
- **With Customer Support Lead**: Incorporate user feedback and pain points
- **With Project Manager**: Align on scope, timeline, and resource constraints

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

### Key Interactions
- **With Release Manager**: Coordinate release schedules and deployment windows
- **With Product Manager**: Align on priorities and resource allocation
- **With all roles**: Facilitate communication and resolve blockers

---

## UX Designer

### Role Summary
UX Designers ensure products are user-centric, intuitive, and accessible. They conduct user research, create designs, and validate solutions through testing to improve user satisfaction and adoption.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate with Product Managers to refine requirements
- Work with Developers to ensure design feasibility
- Validate solutions against user needs
- Document design patterns and guidelines

### Goals
- Deliver user-centric, intuitive designs
- Reduce user friction and improve adoption
- Maintain consistency across products and platforms
- Advocate for user needs in cross-functional discussions

### Typical Communication
- Design reviews with development team
- User research findings and insights
- Design specifications and documentation
- Weekly collaboration with Product Manager

### Key Interactions
- **With Product Manager**: Align on user needs and business objectives
- **With Developers**: Ensure design feasibility and implementation accuracy
- **With Data Analyst**: Analyze user behavior data to inform design decisions
- **With Customer Support Lead**: Understand common user pain points and support requests

---

## Data Analyst

### Role Summary
Data Analysts provide insights from usage data and metrics to inform decision-making. They track key performance indicators (KPIs), validate hypotheses, and help teams understand user behavior and product impact.

### Responsibilities
- Define and track success metrics and KPIs
- Create dashboards and reports for visibility
- Analyze user behavior and product performance
- Support hypothesis validation and A/B testing
- Identify trends and opportunities for improvement
- Work with teams to instrument code for data collection

### Goals
- Enable data-informed decision-making
- Measure and communicate product impact
- Identify growth and optimization opportunities
- Reduce guesswork in prioritization

### Typical Communication
- Weekly metric reviews with Product Manager
- Dashboard updates and performance reports
- Ad-hoc analysis for specific questions
- Data-driven recommendations in planning meetings

### Key Interactions
- **With Product Manager**: Support prioritization with data insights
- **With Developers**: Define instrumentation requirements
- **With UX Designer**: Analyze user behavior to improve designs
- **With Customer Support Lead**: Track common issues and pain points

---

## Release Manager

### Role Summary
Release Managers coordinate and oversee the release process, ensuring smooth deployment to production. They manage release planning, deployment checklists, communication, and rollback procedures.

### Responsibilities
- Plan and coordinate release schedules
- Create and maintain release notes
- Execute deployment checklists and procedures
- Manage rollback and incident response
- Communicate release status to stakeholders
- Document lessons learned from releases

### Goals
- Minimize deployment risk and downtime
- Ensure clear communication during releases
- Maintain repeatable and reliable release processes
- Enable rapid recovery from issues

### Typical Communication
- Release status updates to stakeholders
- Deployment window coordination
- Post-release verification and communication
- Incident and rollback coordination

### Key Interactions
- **With Project Manager**: Coordinate release schedules and timelines
- **With Developers**: Ensure code readiness and deployment procedures
- **With QA/Testing**: Coordinate pre-release testing and smoke tests
- **With Customer Support Lead**: Plan communication and support handoff

---

## Customer Support Lead

### Role Summary
Customer Support Leads serve as the voice of the customer, communicating user pain points, feature requests, and support challenges back to the product and engineering teams. They help prioritize work based on customer impact.

### Responsibilities
- Gather and escalate customer feedback and pain points
- Document common support issues and trends
- Participate in release planning and feature discussions
- Provide insights on feature usability and adoption
- Coordinate support communication for releases
- Help triage and prioritize customer-impacting issues

### Goals
- Improve customer satisfaction and retention
- Reduce support volume through product improvements
- Enable rapid resolution of customer issues
- Advocate for customer needs in product decisions

### Typical Communication
- Weekly feedback summaries and trends
- Participation in planning and retrospective meetings
- Communication to customers about releases and changes
- Escalation of critical customer issues

### Key Interactions
- **With Product Manager**: Communicate customer feedback and impact
- **With UX Designer**: Share usability feedback and support patterns
- **With Developers**: Report bugs and prioritize fixes
- **With Release Manager**: Coordinate support communication for releases

---

## Cross-Functional Role Interaction Matrix

| Role | Works closely with | Communication frequency | Key deliverables |
|------|-------------------|----------------------|------------------|
| Developer | Developers, QA, UX Designer, Data Analyst, Release Manager | Daily | Code, tests, design implementation |
| Product Manager | UX Designer, Data Analyst, Project Manager, Customer Support Lead | Weekly | Requirements, metrics, prioritization |
| Project Manager | All roles | Weekly | Plans, status reports, risk management |
| UX Designer | Product Manager, Developers, Data Analyst | Weekly | Designs, research findings, specs |
| Data Analyst | Product Manager, UX Designer, Developers, Customer Support Lead | Weekly | Metrics, dashboards, insights |
| Release Manager | Project Manager, Developers, QA, Customer Support Lead | Per release | Release notes, deployment status |
| Customer Support Lead | Product Manager, UX Designer, Data Analyst, Developers | Weekly | Feedback trends, escalations, insights |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction matrix to understand cross-functional dependencies and communication needs.
