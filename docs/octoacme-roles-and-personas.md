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
The QA Lead ensures product quality by defining testing strategy, validating acceptance criteria, and identifying release risks before work reaches production.

### Responsibilities
- Define test plans, quality gates, and regression coverage
- Validate feature readiness against acceptance criteria and business goals
- Partner with developers and product teams to triage defects and root causes
- Coordinate user acceptance testing and release verification
- Track quality trends across milestones and releases

### Goals
- Reduce escaped defects and customer-facing issues
- Improve confidence in release readiness and stability
- Create a shared quality bar across teams and projects

### Typical Communication
- Test strategy reviews and quality sign-off meetings
- Defect triage with engineering and product partners
- Release readiness updates with PMs and stakeholders

### Interaction with Existing Roles
- Works closely with Developers to review quality risks and validate fixes
- Supports Product Managers by confirming the implemented work meets acceptance criteria
- Informs Project Managers about release readiness and blockers that affect milestone timing

---

## Technical Architect / Tech Lead

### Role Summary
The Technical Architect or Tech Lead guides technical direction, resolves design trade-offs, and helps the team deliver solutions that are scalable, maintainable, and aligned with platform constraints.

### Responsibilities
- Define or validate technical architecture and design patterns
- Identify technical dependencies, risks, and integration constraints early
- Review implementation decisions to ensure maintainability and scalability
- Support developers with technical guidance and escalation paths
- Align engineering choices with product priorities and delivery timelines

### Goals
- Deliver solutions that are robust, extensible, and operationally sound
- Reduce unnecessary rework and architectural drift
- Ensure the team can execute confidently and predictably

### Typical Communication
- Architecture reviews and design discussions
- Technical risk updates in planning and weekly syncs
- Guidance to developers during implementation and incident response

### Interaction with Existing Roles
- Partners with Developers on technical decisions and implementation quality
- Advises Product Managers on feasibility, timing, and trade-offs
- Works with Project Managers to flag cross-team dependencies or technical blockers

---

## Scrum Master / Iteration Facilitator

### Role Summary
The Scrum Master or Iteration Facilitator helps the team work effectively, removes blockers, and strengthens healthy delivery practices without becoming the owner of the work itself.

### Responsibilities
- Facilitate sprint planning, standups, retrospectives, and backlog refinement
- Help the team remove impediments and improve workflow visibility
- Support adoption of agile practices and team rituals
- Coach on prioritization, planning discipline, and continuous improvement
- Surface delivery risks before they affect commitments

### Goals
- Improve team flow, predictability, and collaboration
- Keep the delivery process lightweight and effective
- Strengthen accountability without creating unnecessary ceremony

### Typical Communication
- Sprint ceremonies and facilitation sessions
- Team check-ins for blockers, dependencies, and escalation needs
- Retrospective follow-up and process improvement tracking

### Interaction with Existing Roles
- Supports Project Managers by improving team execution rhythm and stakeholder transparency
- Works with Developers to maintain smooth sprint flow and backlog health
- Collaborates with Product Managers to ensure priorities are clear and manageable

---

## Stakeholder / Executive Sponsor

### Role Summary
The Executive Sponsor or Stakeholder representative provides strategic context, approves major milestones, and helps resolve decisions that require business-level alignment.

### Responsibilities
- Provide business context, sponsorship, and priority framing
- Approve key milestones, budget decisions, and major scope changes
- Escalate unresolved dependencies or strategic trade-offs
- Represent stakeholder interests and expected business outcomes
- Help align the project with broader organizational goals

### Goals
- Ensure the initiative remains valuable, prioritized, and business-aligned
- Support timely decisions and sponsorship for strategic work
- Maintain confidence in project outcomes and stakeholder trust

### Typical Communication
- Steering meetings, milestone reviews, and executive check-ins
- Business updates and sponsor-level decision requests
- Escalation communications during major risk or timing issues

### Interaction with Existing Roles
- Works with Product Managers to confirm business objectives and priorities
- Provides strategic direction to Project Managers on scope and milestone approval
- Supports Developers and technical leads by confirming the value and urgency of trade-offs

---

## Design / UX Lead

### Role Summary
The Design or UX Lead ensures the product experience is usable, accessible, and aligned with customer needs and brand expectations.

### Responsibilities
- Define user experience strategy, design direction, and interaction patterns
- Ensure accessibility, usability, and consistency across flows and components
- Collaborate with product and engineering on feasibility and implementation details
- Maintain alignment with design systems, customer feedback, and usability goals
- Review product experience before release to catch gaps early

### Goals
- Deliver products that are intuitive, inclusive, and valuable to users
- Align design quality with product outcomes and customer expectations
- Reduce friction in the end-to-end experience

### Typical Communication
- Design reviews, user journey discussions, and usability feedback loops
- Cross-functional workshops with product and engineering teams
- Stakeholder updates on customer experience risks and improvements

### Interaction with Existing Roles
- Helps Product Managers validate user needs and feature fit
- Partners with Developers to ensure designs are implemented consistently and accessibly
- Informs Project Managers about design dependencies or user experience risks that could affect release timing

---

## DevOps / Release Engineer

### Role Summary
The DevOps or Release Engineer manages the delivery pipeline, deployment automation, environment reliability, and operational readiness for each release.

### Responsibilities
- Maintain CI/CD pipelines, deployment automation, and environment configuration
- Support reliable releases, rollback readiness, and infrastructure health
- Monitor deployment risks and production readiness signals
- Collaborate with engineering teams on automation and observability standards
- Help maintain security, reliability, and operational consistency across environments

### Goals
- Reduce release friction and deployment risk
- Improve delivery speed without sacrificing stability
- Create a reliable operating environment for product teams

### Typical Communication
- Release planning and deployment readiness reviews
- Incident and production support coordination
- Infrastructure or pipeline issue updates with engineering partners

### Interaction with Existing Roles
- Works with Developers to ensure automated builds, test gates, and deployability
- Collaborates with QA to validate release quality and smoke-test execution
- Supports Project Managers and Product Managers with release timing, rollback readiness, and risk communication

---

## Security Champion

### Role Summary
The Security Champion ensures security requirements are considered throughout the lifecycle, from design and development through deployment and ongoing operations.

### Responsibilities
- Review features, architecture, and dependencies for security risk
- Define and support secure development practices and compliance requirements
- Partner with engineering to remediate vulnerabilities and improve controls
- Help assess security trade-offs during planning and release reviews
- Support incident prevention and secure deployment standards

### Goals
- Reduce security exposure and compliance risk
- Embed security into normal delivery rather than treating it as a late-stage check
- Increase confidence in system resilience and trustworthiness

### Typical Communication
- Security review meetings and risk assessments
- Developers’ design check-ins and remediation discussions
- Leadership updates on security posture and critical concerns

### Interaction with Existing Roles
- Collaborates with Developers to apply secure coding patterns and validation checks
- Advises Product Managers and Project Managers on risk, timing, and mitigation needs
- Works with DevOps and QA to ensure deployment pipelines and release quality support security standards

---

## Customer Success / Support Lead

### Role Summary
The Customer Success or Support Lead represents the customer voice after release, ensuring that product value, support readiness, and feedback loops are connected back into the delivery process.

### Responsibilities
- Capture customer feedback, pain points, and support trends
- Help define support readiness requirements and service expectations
- Coordinate release communication with customer-facing teams
- Identify post-launch issues, usage gaps, and customer impact
- Feed lessons learned back into product planning and backlog prioritization

### Goals
- Improve adoption, retention, and customer satisfaction
- Ensure support teams are prepared for new releases or changes
- Close the loop between deployment and customer outcomes

### Typical Communication
- Customer feedback reviews and support escalations
- Release readiness briefings with product and support teams
- Post-release impact reports and continuous improvement discussions

### Interaction with Existing Roles
- Informs Product Managers with customer evidence and support trends
- Helps Project Managers understand operational readiness and rollout risks
- Provides Developers and QA with real-world product issues that require follow-up or improvement

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles clarify decision ownership, communication paths, and accountability across the full OctoAcme project lifecycle.

