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

## QA / Quality Assurance Lead

### Role Summary
The QA Lead defines the testing strategy and ensures that products meet functional, usability, and release quality standards before they are accepted by stakeholders.

### Responsibilities
- Own the test strategy, test plans, and release validation checklist
- Partner with developers and product owners on acceptance criteria and regression risks
- Review defects, triage severity, and track issue closure
- Coordinate manual and automated testing for milestones and releases
- Validate that user stories are ready for sign-off and production readiness

### Goals
- Reduce quality escape risk
- Improve release confidence and product stability
- Align testing effort with product priorities and customer expectations

### Typical Communication
- Test planning sessions and release readiness reviews
- Defect triage and bug severity discussions
- Weekly QA status updates with PM, engineering, and stakeholders

### Interaction with Existing Roles
- Works closely with Developers to define test coverage and bug reproduction steps
- Aligns with Product Managers on acceptance criteria and release quality gates
- Reports quality risks to the Project Manager so schedule and scope trade-offs are visible
- Supports the Stakeholder Sponsor with evidence for go/no-go decisions at milestone checkpoints

---

## Technical Architect / Tech Lead

### Role Summary
The Technical Architect or Tech Lead shapes the system design, technical standards, and solution direction so the team can deliver scalable and maintainable work.

### Responsibilities
- Guide technical design, architecture decisions, and integration patterns
- Identify technical risks, dependencies, and performance concerns early
- Ensure solutions align with platform standards, scalability goals, and maintainability
- Mentor developers and support design and code review quality
- Balance delivery speed with technical debt and long-term sustainability

### Goals
- Create a coherent technical direction across the project
- Reduce avoidable rework and architectural drift
- Enable safe, scalable delivery as the team grows

### Typical Communication
- Architecture reviews and design discussions
- Technical risk reviews during planning and execution
- Coordination with engineering leads, PMs, and stakeholders on technical trade-offs

### Interaction with Existing Roles
- Partner with Developers to translate product requirements into technical implementation plans
- Works with Product Managers to assess feasibility, sequencing, and trade-offs against roadmap goals
- Informs Project Managers about dependencies, risks, and delivery constraints
- Supports the QA Lead by identifying risk areas that need deeper validation and testing

---

## Scrum Master / Iteration Facilitator

### Role Summary
The Scrum Master or Iteration Facilitator helps the team work effectively by coaching agile practices, improving flow, and removing barriers to delivery.

### Responsibilities
- Facilitate sprint planning, daily standups, and retrospectives
- Help the team maintain clear priorities, predictable delivery, and healthy collaboration
- Identify blockers, dependencies, and process friction that slow execution
- Coach the team on agile rituals, story quality, and continuous improvement
- Support transparency through visible work tracking and decisions

### Goals
- Improve team effectiveness and delivery consistency
- Create a healthier, more predictable rhythm of work
- Reduce friction so developers and PMs can focus on value creation

### Typical Communication
- Sprint ceremonies, standups, and retrospectives
- Team coaching and process improvement discussions
- Escalation updates with PMs for blockers that require cross-functional action

### Interaction with Existing Roles
- Supports Developers by improving workflow, reducing confusion, and protecting focus time
- Works with Project Managers to surface risks, dependency issues, and delivery bottlenecks
- Helps Product Managers refine backlog readiness and prioritization through better sprint flow
- Coordinates with Stakeholder Sponsors when delivery changes affect strategic milestones or commitments

---

## Stakeholder / Executive Sponsor

### Role Summary
The Executive Sponsor provides strategic context, business sponsorship, and final decision support for major milestones, trade-offs, and escalations.

### Responsibilities
- Represent the business case and strategic priorities for the initiative
- Approve key milestones, scope trade-offs, and go/no-go decisions
- Help resolve escalated issues that require broader organizational support
- Provide sponsorship for cross-team dependencies and resource decisions
- Ensure the project stays aligned with company goals and measurable outcomes

### Goals
- Keep delivery aligned with business value and strategic importance
- Remove organizational barriers that slow execution
- Support confident, informed decisions at key checkpoints

### Typical Communication
- Steering reviews, milestone governance, and executive updates
- Decisions on scope, urgency, and funding or resourcing trade-offs
- Escalations when the team needs decision support or sponsor-level intervention

### Interaction with Existing Roles
- Partners with Product Managers to confirm priorities and validate business outcomes
- Receives status and risk insights from the Project Manager and PM team
- Uses QA, technical, and delivery signals to support milestone approvals and release decisions
- Provides direction to the team when decisions have broader organizational impact

---

## Design / UX Lead

### Role Summary
The Design/UX Lead ensures that solutions are intuitive, accessible, and aligned with customer needs and the product experience vision.

### Responsibilities
- Define user flows, interaction patterns, and product experience standards
- Align design work with accessibility, usability, and brand requirements
- Partner with Product Managers and Developers on feature clarity and implementation feasibility
- Review design quality, edge cases, and customer pain points
- Support decision-making with customer-centric evidence and design principles

### Goals
- Improve product usability and customer satisfaction
- Ensure consistent, inclusive, and accessible experiences
- Deliver solutions that are both valuable and easy to use

### Typical Communication
- UX reviews, customer journey workshops, and design critiques
- Collaboration with PM and engineering on feature definition and readiness
- Design handoff and implementation feedback loops during delivery

### Interaction with Existing Roles
- Works with Product Managers to turn user needs into clear experience goals and priorities
- Collaborates with Developers to ensure design intent is implemented accurately and accessibly
- Shares user experience risks and design trade-offs with the Project Manager and QA Lead
- Helps ensure customer success and release quality align with the intended experience

---

## DevOps / Release Engineer

### Role Summary
The DevOps or Release Engineer manages the delivery pipeline, infrastructure, and deployment reliability needed to ship software safely and consistently.

### Responsibilities
- Maintain CI/CD pipelines, release automation, and environment readiness
- Support deployment planning, rollout sequencing, and rollback preparation
- Improve observability, environment consistency, and operational health
- Coordinate with engineering and QA on staging, smoke tests, and release validation
- Help teams reduce deployment risk and improve recovery speed when issues occur

### Goals
- Increase deployment confidence and release reliability
- Reduce manual operational effort and release bottlenecks
- Improve system resilience and operational visibility

### Typical Communication
- Release planning, deployment readiness, and production check-ins
- Incident coordination and rollback decision support
- Pipeline and environment status reporting with engineering and PM stakeholders

### Interaction with Existing Roles
- Supports Developers by enabling smooth integration, build, and deployment workflows
- Coordinates with QA Lead on staging validation and smoke test execution
- Works with Project Managers on deployment windows, release risk, and communication timing
- Helps Security Champion and Product teams ensure controls are in place before production rollout

---

## Security Champion

### Role Summary
The Security Champion ensures that security, privacy, and compliance requirements are considered throughout planning, implementation, and release.

### Responsibilities
- Identify security risks, vulnerabilities, and compliance considerations early
- Partner with engineering and product teams on secure design and testing practices
- Review features for privacy, authentication, authorization, and data protection concerns
- Support secure deployment practices and threat mitigation planning
- Help the team maintain an acceptable security posture before release

### Goals
- Reduce security and compliance risk
- Build secure-by-default practices into delivery workflows
- Protect customer trust and organizational reputation

### Typical Communication
- Risk reviews, security checkpoints, and compliance discussions
- Escalation for urgent issues or high-risk vulnerabilities
- Cross-functional coordination with engineering, QA, and PM stakeholders

### Interaction with Existing Roles
- Advises Developers and Technical Architects on secure implementation approaches
- Works with QA Lead to include security validation in test plans and release checks
- Supports Project Managers in risk tracking and escalation for security-related blockers
- Connects with Stakeholder Sponsors when security issues affect go/no-go decisions or external obligations

---

## Customer Success / Support Lead

### Role Summary
The Customer Success or Support Lead represents the post-release customer experience and ensures the team is prepared to support adoption, issues, and ongoing value realization.

### Responsibilities
- Gather customer feedback, support trends, and release impact signals
- Partner with Product and PM teams on adoption, usability, and issue prioritization
- Help define support readiness, documentation, and escalation paths
- Ensure teams are prepared to respond to customer-facing incidents and service concerns
- Connect product delivery outcomes to real customer outcomes after release

### Goals
- Improve customer satisfaction and retention
- Reduce friction after release
- Ensure product value is realized and sustained in real-world use

### Typical Communication
- Customer feedback loops, support triage, and post-release reviews
- Product and release readiness discussions with PMs and stakeholders
- Escalation of critical customer-impacting issues and recurring support themes

### Interaction with Existing Roles
- Feeds customer needs and pain points back to Product Managers and the backlog
- Provides release context to QA and DevOps teams so support readiness is considered before launch
- Helps Project Managers communicate release readiness and operational impact to stakeholders
- Supports Executive Sponsors by showing whether outcomes are meeting customer expectations and business value goals

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together with the core roles, these personas help clarify accountability across planning, delivery, quality, security, release, and customer impact.












































































































































































































































































































































































































































































