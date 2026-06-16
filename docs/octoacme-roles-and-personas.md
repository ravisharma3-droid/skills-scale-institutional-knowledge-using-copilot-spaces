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

## Release Manager

### Role Summary
Release Managers own the end-to-end release process, from planning through post-deployment verification. They ensure releases are well-coordinated, tracked, and communicated to all stakeholders.

### Responsibilities
- Plan and schedule release windows in coordination with PM and Developers
- Maintain and execute release checklists and runbooks
- Coordinate deployment activities across infrastructure and development teams
- Verify rollback and mitigation plans are documented before release
- Communicate release status, blockers, and outcomes to stakeholders
- Conduct post-release verification and monitor for critical issues
- Document release notes and known issues

### Goals
- Deliver releases on schedule with minimal risk and disruption
- Reduce time to rollback if critical issues arise
- Maintain clear visibility and communication throughout release lifecycle
- Enable fast, reliable deployments with confidence

### Interaction Points
- **Project Manager**: Coordinates release scheduling and stakeholder communication
- **Developers**: Validates merge readiness, CI/CD pipeline status, and code deployment
- **QA/Testing**: Confirms pre-release verification and smoke test completion
- **Support Lead**: Shares post-release monitoring observations and customer impact alerts
- **Observability Engineer**: Uses metrics and dashboards to verify deployment success

### Typical Communication
- Release planning meetings and go/no-go decisions
- Deployment window coordination and status updates
- Post-release incident escalations
- Release notes and stakeholder announcements

---

## Observability Engineer

### Role Summary
Observability Engineers define, implement, and maintain the monitoring, alerting, and observability strategy for applications and services. They ensure systems are measurable and incidents are detectable early.

### Responsibilities
- Design monitoring and alerting strategy aligned with product goals and SLOs
- Instrument code and services with metrics, logs, and traces
- Own SLO/SLA definitions and recommendations for new services
- Create dashboards and runbooks for common operational scenarios
- Establish alert routing, escalation, and on-call playbooks
- Collaborate on incident response and post-mortem improvements
- Validate monitoring coverage for critical features before release

### Goals
- Detect and respond to incidents quickly with actionable signals
- Provide visibility into system health and performance
- Enable data-driven decisions on performance optimization
- Reduce time to resolution for production issues

### Interaction Points
- **Developers**: Defines instrumentation requirements and reviews implementation
- **SRE/Operations**: Coordinates alert routing, on-call schedules, and runbook execution
- **Product Manager**: Aligns metric definitions with business success criteria
- **Release Manager**: Verifies monitoring is ready before deployments
- **Support Lead**: Provides dashboards and triage playbooks for customer-reported issues

### Typical Communication
- SLO/SLA definition meetings with stakeholders
- Instrumentation reviews during code design phase
- Post-incident reviews and alert tuning discussions
- Weekly observability sync on dashboard coverage and alert effectiveness

---

## UX Researcher

### Role Summary
UX Researchers plan, conduct, and synthesize user research to inform product and design decisions. They translate customer needs into actionable insights and acceptance criteria.

### Responsibilities
- Plan and conduct user research sessions (interviews, usability tests, surveys)
- Synthesize findings and translate into actionable insights
- Define user personas, jobs-to-be-done, and pain points
- Provide acceptance criteria and design recommendations to Product and Design teams
- Validate solutions through user testing before and after release
- Advocate for user needs during prioritization discussions
- Document research findings and share learnings with the team

### Goals
- Ensure features solve real user problems and are usable
- Reduce rework and post-release issues through early validation
- Build shared understanding of user needs across the organization
- Enable confident prioritization decisions based on user evidence

### Interaction Points
- **Product Manager**: Collaborates on research goals, prioritization, and success metrics
- **Designers**: Provides user insights and validates design solutions
- **Developers**: Answers implementation questions and clarifies user requirements
- **QA/Testing**: Defines acceptance criteria and conducts usability validation tests
- **Support Lead**: Gathers recurring customer pain points for research prioritization

### Typical Communication
- Research plan kick-offs and user recruitment discussions
- Findings presentations and insight synthesis sessions
- Design critique and usability feedback
- Acceptance criteria refinement with Product and QA

---

## Support Lead

### Role Summary
Support Leads manage customer-facing support operations, triage escalations, and ensure customer issues feed back into the product development process. They are the voice of the customer.

### Responsibilities
- Triage and prioritize customer-reported issues
- Manage escalation paths and coordinate resolution with technical teams
- Own support communication templates and escalation communications
- Track recurring issues and patterns for backlog prioritization
- Coordinate with Developers on bug fixes and hotfixes
- Gather customer feedback and pain points for research and product teams
- Provide post-release monitoring and quick issue detection

### Goals
- Resolve customer issues quickly and maintain high satisfaction
- Reduce resolution time through effective escalation coordination
- Convert customer feedback into actionable product improvements
- Enable proactive issue detection through monitoring and communication

### Interaction Points
- **Project Manager**: Communicates customer impact and escalation decisions
- **Developers**: Coordinates bug fixes, provides repro steps, and validates solutions
- **QA/Testing**: Confirms fixes and validates resolution
- **Release Manager**: Alerts to post-release issues and customer impact
- **Observability Engineer**: Uses dashboards and triage playbooks for issue diagnosis
- **Product Manager**: Feeds recurring issues into prioritization discussions

### Typical Communication
- Customer issue triage in daily or weekly standups
- Escalation coordination with technical teams
- Post-release incident coordination
- Weekly customer feedback and trend reports to Product

---

## Security Liaison

### Role Summary
Security Liaisons coordinate security reviews, scanning, and remediation efforts. They ensure the organization meets security standards and regulatory requirements while maintaining development velocity.

### Responsibilities
- Coordinate security reviews for new features and architecture changes
- Track and monitor security scanning results (dependency, code, container scans)
- Advise on security findings severity, risk, and mitigation approaches
- Ensure security issues are prioritized and tracked in the backlog
- Document security requirements and acceptance criteria for features
- Conduct security training and awareness activities
- Escalate high-severity findings to sponsors and incident response teams

### Goals
- Reduce security vulnerabilities and compliance violations
- Enable fast, secure development through early review and scanning
- Maintain security compliance without blocking delivery
- Build security awareness and culture across the organization

### Interaction Points
- **Developers**: Reviews code and architecture for security, advises on fixes
- **CI/Security Tooling**: Configures and monitors automated scanning pipelines
- **Project Manager**: Prioritizes security work and communicates risk to sponsors
- **Product Manager**: Incorporates security requirements into feature specifications
- **Release Manager**: Verifies security scans pass before release
- **Sponsors**: Escalates high-risk findings and compliance gaps

### Typical Communication
- Security review meetings during design phase
- Vulnerability scanning and remediation planning
- Security findings and risk reports
- Post-incident security review and lessons learned

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When describing handoffs or dependencies, reference the explicit Interaction Points section for each role to clarify responsibilities and decision-making authority.
