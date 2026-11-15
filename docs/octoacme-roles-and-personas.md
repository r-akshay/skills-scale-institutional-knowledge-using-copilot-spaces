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

## Product Lead / Sponsor

### Role Summary
The Product Lead or Sponsor provides strategic direction, prioritization context, and executive sponsorship for the initiative. They ensure the work remains aligned with business objectives and that major trade-offs are visible to the right stakeholders.

### Responsibilities
- Confirm business priority and strategic fit for the project
- Approve major scope, trade-off, or resourcing decisions
- Partner with the Product Manager on roadmap direction and outcomes
- Escalate cross-functional blockers when executive support is needed
- Review milestone progress against business value and customer impact

### Goals
- Maintain strategic alignment across the program
- Support timely decisions and executive sponsorship
- Improve confidence in investment and prioritization

### Typical Communication
- Steering meetings and milestone briefings
- Executive status updates and decision reviews
- Goal alignment and trade-off discussions with Product and PM leadership

### Interaction with Existing Roles
- Works with the Product Manager to translate strategy into roadmap priorities
- Collaborates with the Project Manager on escalations, risk exposure, and timeline trade-offs
- Provides business context and sponsorship while allowing the delivery team to manage technical execution

---

## Design / UX Researcher

### Role Summary
Design and UX Researchers shape user-centered decision making. They bring customer insight, usability feedback, and interaction design guidance into planning and delivery so solutions are both valuable and easy to use.

### Responsibilities
- Conduct user research and synthesize findings into needs and opportunities
- Define or refine usability goals and interaction patterns
- Collaborate on acceptance criteria and experience quality standards
- Partner with Product and Engineering on trade-offs between business goals and user experience
- Validate that delivered experiences meet user needs before release

### Goals
- Increase usability, clarity, and adoption of the product
- Ensure customer needs are represented in planning and reviews
- Reduce rework caused by poor product or experience fit

### Typical Communication
- Research notes and user insight summaries
- Design review sessions and usability feedback loops
- Product and engineering collaboration during discovery and validation

### Interaction with Existing Roles
- Supports the Product Manager with customer research and problem framing
- Collaborates with Developers on UI/UX implementation details and edge cases
- Shares validated insight with QA/Testing to ensure the experience is tested against real user workflows

---

## Engineering / Technical Lead

### Role Summary
The Engineering or Technical Lead guides solution design, technical direction, and delivery quality. They help the team make sound architecture and implementation decisions while managing technical risk and dependencies.

### Responsibilities
- Define technical direction, architecture patterns, and delivery sequencing
- Help estimate complexity and identify dependencies or blockers
- Guide design reviews, implementation standards, and technical trade-offs
- Support Developers in solving difficult technical issues
- Communicate engineering risks and constraints to Product and Project leadership

### Goals
- Deliver a technically sound, maintainable solution
- Reduce delivery risk and avoid avoidable rework
- Keep the team aligned on architectural and quality standards

### Typical Communication
- Technical design discussions and architecture reviews
- Dependency tracking and risk updates
- Collaboration with Product, PM, and QA stakeholders during planning and review

### Interaction with Existing Roles
- Works closely with Developers to guide implementation and technical quality
- informs the Product Manager and Project Manager about delivery risk, sequencing, and trade-offs
- Coordinates with QA/Testing to ensure technical quality and testability are built into delivery

---

## Release Manager

### Role Summary
The Release Manager coordinates release readiness, timing, communications, and verification. They ensure that product changes are released predictably and with the right support in place.

### Responsibilities
- Manage release plans, sequencing, and deployment windows
- Verify acceptance criteria, release readiness, and rollback preparedness
- Prepare release notes, communication plans, and stakeholder notifications
- Coordinate with QA/Testing, Engineering, and Support on verification steps
- Help detect and communicate release risks or issues before and after deployment

### Goals
- Improve release predictability and operational readiness
- Reduce deployment-related surprises and customer impact
- Align launch activities with project milestones and support readiness

### Typical Communication
- Release checklists and launch coordination
- Deployment readiness reviews and post-release follow-ups
- Status updates with Project Manager, Product Manager, and support teams

### Interaction with Existing Roles
- Works with the Project Manager on launch timing and dependencies
- Partners with Engineering/Technical Lead and QA/Testing for staging, smoke tests, and release verification
- Shares customer impact and support-readiness information with the Support/Operations partner and stakeholders

---

## Customer Support / Operations Representative

### Role Summary
The Customer Support or Operations representative ensures that product changes are supportable, understandable, and safe for the people who will use or maintain them after launch.

### Responsibilities
- Share supportability requirements and operational constraints during planning
- Prepare support teams for changes, incidents, or new workflows
- Surface recurring customer pain points and post-release issues
- Help define documentation, escalation paths, and handoff plans
- Contribute to release readiness and issue triage after deployment

### Goals
- Reduce customer friction and operational disruption
- Improve the readiness of support and operations teams for change
- Ensure product changes are sustainable after launch

### Typical Communication
- Support readiness briefs and issue escalation reviews
- Post-release feedback loops and operations updates
- Collaboration with Product and PM teams on customer impact

### Interaction with Existing Roles
- Works with the Product Manager and Project Manager to surface customer-impact signals and support readiness needs
- Collaborates with Release Manager and QA/Testing to validate support processes and known issues
- Provides feedback to Developers and Design teams on real-world usage, edge cases, and operational concerns

---

## Security / Privacy Partner

### Role Summary
The Security or Privacy Partner helps the team identify and manage security, compliance, and privacy concerns across the lifecycle. They ensure that risks are addressed before they reach production.

### Responsibilities
- Review requirements, risks, and controls impacting security and privacy
- Assess product changes for exposure, compliance impact, or sensitive data handling
- Partner with Engineering and QA/Testing to define verification steps and evidence
- Recommend mitigations, review processes, and support risk acceptance decisions
- Support release gating for high-risk or regulated changes

### Goals
- Reduce security and privacy risk across the delivery lifecycle
- Promote trust, compliance, and safe product operations
- Prevent late-stage surprises that delay or block release

### Typical Communication
- Security reviews and risk assessments
- Privacy/compliance check-ins and escalation tracking
- Coordination with release and project leadership before launch

### Interaction with Existing Roles
- Advises Developers and Technical Leads on secure design patterns and risk treatment
- Supports QA/Testing with validation of controls and sensitive data scenarios
- Coordinates with the Release Manager to ensure launch readiness, approvals, and risk communication are in place

---

## Role Boundaries and Collaboration

These personas are not mutually exclusive and may be combined or omitted depending on project size, risk, and complexity. The Project Manager coordinates schedule, dependencies, and communication flow; the Product Manager owns product outcomes and backlog priority; and each additional persona contributes specialized expertise within a defined scope. This structure helps teams clarify accountability, decision ownership, and handoffs without creating unnecessary overhead.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
