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

## Technical Lead

### Role Summary
The Technical Lead guides the technical direction of a project or workstream. They partner with the Project Manager, Product Manager, and Developers to balance delivery speed with architectural quality.

### Responsibilities
- Define and communicate technical approach and architecture decisions
- Review designs and code for quality, scalability, and maintainability
- Identify and mitigate technical risks early
- Mentor developers and facilitate technical knowledge sharing
- Provide effort estimates and surface engineering trade-offs to PM and Product Manager

### Goals
- Maintain a healthy, sustainable codebase
- Ensure technical decisions align with product and business goals
- Reduce rework caused by unclear technical direction

### Typical Communication
- Architecture review meetings and design docs
- PR reviews and inline code comments
- Regular sync with PM and Product Manager on scope and feasibility

### Interactions with Existing Roles
- **Project Manager**: escalates technical blockers, contributes to risk register, provides timeline input
- **Product Manager**: negotiates trade-offs between features and technical debt
- **Developers**: reviews code, provides guidance, and pairs on complex tasks
- **QA/Testing**: aligns on testability requirements and quality standards
- **Stakeholders**: translates technical constraints into business impact

### How This Role Improves Accountability
Having a dedicated Technical Lead prevents diffuse ownership of architecture decisions. It creates a single point of accountability for technical quality, reduces re-work, and ensures engineering trade-offs are surfaced early.

---

## QA Lead / Test Owner

### Role Summary
The QA Lead owns the overall test strategy and quality process. They coordinate validation activities across the team and work with Developers and the Project Manager to confirm acceptance criteria are met before release.

### Responsibilities
- Define and maintain the test strategy, test plans, and coverage goals
- Coordinate manual and automated testing activities
- Triage defects and communicate quality status to the team
- Collaborate with Developers to improve testability of new features
- Gate releases by verifying quality standards are satisfied

### Goals
- Reduce defect escape rate to production
- Ensure acceptance criteria are validated consistently
- Build confidence in releases through thorough, repeatable testing

### Typical Communication
- Test plans and coverage reports shared with PM and Developers
- Defect triage meetings and bug status updates
- Sign-off communication to Release Manager and PM before deployment

### Interactions with Existing Roles
- **Project Manager**: reports quality status; flags risks that may delay release
- **Product Manager**: clarifies acceptance criteria and edge cases
- **Developers**: collaborates on testability, reviews test coverage, and resolves defects
- **Stakeholders**: provides quality summaries ahead of reviews or demos
- **Release Manager**: provides final quality sign-off before deployment

### How This Role Improves Accountability
A QA Lead ensures testing is not an afterthought. Clear ownership of quality gates reduces last-minute defect surprises, improves release confidence, and provides a single escalation point for quality concerns.

---

## Release Manager

### Role Summary
The Release Manager coordinates release readiness and manages the deployment process from final validation through production delivery. They ensure all stakeholders are informed and all checks are complete before and after a release.

### Responsibilities
- Define and maintain the release checklist and go/no-go criteria
- Coordinate deployment scheduling with engineering, QA, and operations
- Communicate release timelines and status to stakeholders and PM
- Manage rollback plans and incident response coordination during releases
- Document release notes and post-deployment validation steps

### Goals
- Enable predictable, low-risk deployments
- Ensure all teams are aligned on release scope and schedule
- Minimize production incidents through thorough release governance

### Typical Communication
- Release planning meetings with PM and Technical Lead
- Pre-release status updates to stakeholders
- Post-release retrospective summaries

### Interactions with Existing Roles
- **Project Manager**: aligns on release scope, schedule, and risk
- **Product Manager**: confirms feature readiness and communicates release notes
- **Technical Lead / Developers**: validates deployment steps and rollback procedures
- **QA Lead**: receives quality sign-off and final test results
- **Stakeholders**: provides go-live communications and post-release status updates

### How This Role Improves Accountability
The Release Manager creates a clear owner for deployment outcomes, preventing gaps between development completion and production delivery. Structured release governance reduces production incidents and improves stakeholder trust.

---

## Stakeholder Champion / Business Owner

### Role Summary
The Stakeholder Champion represents the business domain and end-user perspective within the project team. They provide context, prioritization feedback, and approvals to ensure the solution meets real-world needs.

### Responsibilities
- Represent business requirements and end-user needs throughout the project
- Participate in backlog grooming and provide prioritization input
- Review and approve deliverables, demos, and acceptance criteria outcomes
- Serve as the primary point of contact for domain-specific questions
- Facilitate access to subject-matter experts within the business

### Goals
- Ensure delivered solutions solve the right problems for the business
- Accelerate decision-making by providing timely domain input
- Champion adoption and change management within the business unit

### Typical Communication
- Sprint reviews and demos
- Backlog refinement sessions with Product Manager and PM
- Escalation or approval workflows for scope changes

### Interactions with Existing Roles
- **Project Manager**: provides business priorities and escalation decisions
- **Product Manager**: collaborates on roadmap priorities and validates user stories
- **Developers**: answers domain questions and clarifies business rules
- **QA Lead**: reviews test scenarios to confirm they reflect real business workflows
- **Stakeholders**: acts as a bridge between the delivery team and broader stakeholder group

### How This Role Improves Accountability
A named Stakeholder Champion ensures the business is actively engaged rather than passively informed. This reduces rework from late-stage requirement changes and ensures delivered features are accepted and adopted.

---

## Security / Compliance Reviewer

### Role Summary
The Security / Compliance Reviewer advises the team on security standards, compliance requirements, and risk controls. They participate in review gates when work affects sensitive systems, data, or regulated processes.

### Responsibilities
- Review designs and implementations for security risks and compliance gaps
- Define required security controls and acceptance criteria for sensitive work
- Participate in threat modeling and risk assessment activities
- Validate that security requirements are satisfied before release
- Document findings and track remediation of identified issues

### Goals
- Prevent security vulnerabilities from reaching production
- Ensure regulatory and compliance obligations are met
- Build a security-aware culture within the delivery team

### Typical Communication
- Security review sessions during design and pre-release phases
- Risk findings reports shared with PM and Technical Lead
- Compliance sign-off documentation for regulated features

### Interactions with Existing Roles
- **Project Manager**: communicates security risks and compliance gates that affect the schedule
- **Product Manager**: advises on security and compliance constraints that shape feature design
- **Technical Lead / Developers**: reviews code and architecture for vulnerabilities; recommends mitigations
- **QA Lead**: ensures security test cases are included in the test plan
- **Stakeholders**: provides assurance that regulatory obligations are met

### How This Role Improves Accountability
Embedding a Security / Compliance Reviewer in the project lifecycle ensures security is addressed continuously rather than as a final gate. Clear ownership of compliance requirements reduces audit findings and production security incidents.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

