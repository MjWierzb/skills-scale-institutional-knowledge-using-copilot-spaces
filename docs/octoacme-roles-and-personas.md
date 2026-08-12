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
The Release Manager coordinates all activities required to deliver a software release safely and predictably. They act as the central point of accountability for release readiness, cutover execution, and post-release verification.

### Responsibilities
- Define and maintain the release calendar and cutover runbook
- Confirm go/no-go readiness with Project Manager, Developers, and QA Lead before each release
- Coordinate deployment windows, environment promotions, and rollback plans
- Communicate release status and any blocking issues to stakeholders
- Conduct post-release retrospectives and capture lessons learned

### Goals
- Reduce release risk through clear checklists and sign-off gates
- Ensure repeatable, low-friction deployments
- Maintain a reliable release cadence aligned with product commitments

### Typical Communication
- Release readiness checklists and go/no-go meeting notes
- Deployment runbooks and rollback plans
- Post-release status emails and incident summaries

---

## QA Lead

### Role Summary
The QA Lead owns the overall test strategy, quality gates, and sign-off readiness for each release. They ensure that quality standards are met before software advances through the delivery pipeline.

### Responsibilities
- Define test strategy, coverage targets, and acceptance criteria with Developers and Product Manager
- Identify and track coverage gaps, regression risks, and blocking defects
- Coordinate test execution across functional, integration, and regression suites
- Provide formal sign-off or escalate blockers before releases advance
- Champion quality improvements such as test automation and shift-left practices

### Goals
- Prevent defects from reaching production through rigorous coverage and early feedback
- Shorten feedback loops between development and quality validation
- Maintain a shared understanding of release readiness across the team

### Typical Communication
- Test plans and coverage reports
- Defect triage summaries and severity assessments
- Sign-off notifications shared with the Release Manager and Project Manager

---

## Stakeholder Champion

### Role Summary
The Stakeholder Champion represents the interests of business stakeholders within the delivery team. They bridge the gap between stakeholder expectations and day-to-day project decisions, ensuring that priorities remain aligned throughout the project lifecycle.

### Responsibilities
- Maintain a current understanding of key stakeholder priorities and constraints
- Review project updates and surface concerns or priority conflicts early
- Facilitate trade-off conversations between stakeholder needs and delivery capacity
- Ensure stakeholders receive timely, accurate, and actionable communications
- Escalate unresolved priority conflicts to the appropriate decision-makers

### Goals
- Reduce misalignment between stakeholder expectations and delivered outcomes
- Improve the quality and relevance of stakeholder communications
- Enable faster priority decisions by providing context to the project team

### Typical Communication
- Stakeholder briefings and feedback summaries
- Escalation notes and priority trade-off recommendations
- Input into roadmap reviews and release communications

---

## Support/Operations Liaison

### Role Summary
The Support/Operations Liaison ensures that the team adequately prepares for the operational impact of each release. They coordinate operational readiness activities, communicate known issues to support teams, and serve as the first point of contact for incident escalation after deployment.

### Responsibilities
- Assess operational readiness for each release, including runbooks, monitoring, and support documentation
- Communicate known issues, workarounds, and expected behavior changes to support teams before release
- Coordinate with Developers and the Release Manager on incident response procedures
- Track and report post-release operational issues back to the project team
- Identify recurring operational pain points and advocate for reliability improvements

### Goals
- Minimize operational disruption and customer impact from new releases
- Ensure support and operations teams are prepared before any deployment
- Shorten mean time to resolution (MTTR) for post-release incidents

### Typical Communication
- Operational readiness checklists and support handoff notes
- Known-issues summaries distributed before each release
- Post-release incident reports and trend analyses

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
