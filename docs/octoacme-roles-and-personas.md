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

## Engineering Manager / Engineering Lead

### Role Summary
Engineering Managers and Engineering Leads are accountable for engineering delivery health, team capacity, and execution quality. They align staffing and technical execution with roadmap commitments.

### Responsibilities
- Plan team capacity, staffing, and skill coverage
- Track engineering delivery health and unblock execution risks
- Coach developers on implementation quality and collaboration
- Partner with PM and Product Manager on scope and sequencing trade-offs

### Goals
- Deliver committed scope with sustainable team velocity
- Reduce delivery risk through early escalation and support
- Improve engineering quality and predictability

### Typical Communication
- Sprint planning, standups, and delivery health reviews
- Capacity planning updates and risk escalations
- One-on-ones and engineering syncs

### Interaction Points and Handoffs
- With Developers: assigns ownership, removes blockers, and confirms implementation readiness for planned work
- With Product Managers: confirms feasibility and sequencing for roadmap priorities before commitment
- With Project Managers: provides capacity plans, delivery risk inputs, and escalation decisions for schedule changes

### Accountability
- Decisions: staffing priorities, engineering sequencing, and escalation paths
- Artifacts: capacity plan, engineering risk list, and delivery health updates
- Risks/Approvals/Handoffs: approves engineering commitments for target milestones and hands off schedule-impacting risks to the Project Manager

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects define technical direction and architecture guardrails. They ensure solutions meet functional and non-functional requirements while remaining maintainable.

### Responsibilities
- Define technical approach, architecture boundaries, and integration patterns
- Drive key technical decisions and document trade-offs
- Identify cross-system dependencies and technical constraints
- Support developers through design reviews and implementation guidance

### Goals
- Keep architecture aligned with product and delivery goals
- Reduce rework caused by unclear technical direction
- Ensure security, performance, reliability, and maintainability standards

### Typical Communication
- Technical design reviews and architecture decision sessions
- Design docs, ADRs, and dependency coordination threads
- Implementation check-ins with developers

### Interaction Points and Handoffs
- With Developers: provides design direction before build, reviews implementation alignment, and signs off on architecture-sensitive changes
- With Product Managers: translates requirements into technical options and trade-offs affecting scope or timeline
- With Project Managers: flags dependency and architecture risks that affect planning and milestone confidence

### Accountability
- Decisions: architecture, integration patterns, and major technical trade-offs
- Artifacts: architecture diagrams, ADRs, and technical risk assessments
- Risks/Approvals/Handoffs: approves technical design baselines and hands off dependency risks to the Project Manager for cross-team tracking

---

## UX/UI Designer or Product Designer

### Role Summary
UX/UI or Product Designers own the end-user experience from user flows to interaction and visual design. They ensure solutions are usable, consistent, and aligned with product intent.

### Responsibilities
- Produce user flows, wireframes, and high-fidelity designs
- Define interaction behaviors and accessibility expectations
- Validate design assumptions through lightweight testing and feedback
- Maintain reusable design patterns with engineering alignment

### Goals
- Deliver intuitive and accessible user experiences
- Reduce implementation ambiguity with clear design specifications
- Improve adoption and satisfaction through usability improvements

### Typical Communication
- Design reviews and backlog refinement with Product Managers
- Handoff sessions with developers and QA
- Feedback loops from demos and usability checks

### Interaction Points and Handoffs
- With Developers: hands off approved designs and clarifies edge-case behavior during implementation
- With Product Managers: refines requirements into user journeys and acceptance expectations
- With Project Managers: communicates design dependencies and review timing that affect delivery milestones

### Accountability
- Decisions: interaction and visual design choices within product requirements
- Artifacts: user flows, mockups/prototypes, and design specifications
- Risks/Approvals/Handoffs: approves final design intent before development and hands off implementation-ready specs to Developers and QA

---

## QA / Test Engineer

### Role Summary
QA and Test Engineers own validation strategy and release quality confidence. They provide independent quality signals and drive risk-based testing across the lifecycle.

### Responsibilities
- Define test strategy, coverage priorities, and acceptance validation approach
- Create and execute manual and automated tests
- Report defects with impact, severity, and reproduction clarity
- Track quality trends and release-readiness status

### Goals
- Prevent critical defects from reaching production
- Increase confidence in release quality and stability
- Shorten feedback loops on quality risks

### Typical Communication
- Test plan reviews and triage meetings
- Defect reports and release-quality summaries
- Acceptance test alignment with Product Managers and Developers

### Interaction Points and Handoffs
- With Developers: aligns on testability, automation scope, and defect resolution priorities
- With Product Managers: validates acceptance criteria and confirms behavior against expected outcomes
- With Project Managers: provides release-readiness status, quality risk escalation, and go/no-go inputs

### Accountability
- Decisions: test depth by risk area and defect severity classification
- Artifacts: test plans, test cases, defect reports, and release quality summaries
- Risks/Approvals/Handoffs: approves quality readiness recommendation and hands off unresolved high-risk defects for escalation decisions

---

## DevOps / Site Reliability Engineer

### Role Summary
DevOps and SRE roles own deployment reliability, operational readiness, and service health. They ensure delivery processes and runtime systems are resilient and observable.

### Responsibilities
- Maintain CI/CD pipelines and deployment automation
- Manage environment reliability, configuration, and release controls
- Define observability baselines (metrics, logs, alerts)
- Lead incident response practices and rollback preparedness

### Goals
- Enable safe, repeatable, low-friction releases
- Improve uptime and reduce mean time to recovery
- Detect and mitigate operational risk early

### Typical Communication
- Release planning and operational readiness reviews
- Incident channels, postmortems, and reliability updates
- Deployment status and environment change notices

### Interaction Points and Handoffs
- With Developers: aligns on deployability, runtime dependencies, and instrumentation requirements
- With Product Managers: clarifies operational constraints and release sequencing impacts for customer-facing changes
- With Project Managers: provides release window constraints, rollback plans, and operational risk status

### Accountability
- Decisions: deployment strategy, environment controls, and reliability guardrails
- Artifacts: runbooks, pipeline configs, monitoring/alert definitions, and postmortems
- Risks/Approvals/Handoffs: approves operational readiness for release execution and hands off incident impact updates to Project and Product Managers

---

## Business Analyst

### Role Summary
Business Analysts translate stakeholder needs into clear, actionable requirements. They improve requirement quality, traceability, and shared understanding across business and delivery teams.

### Responsibilities
- Elicit and document business processes, constraints, and outcomes
- Clarify requirements, assumptions, and acceptance conditions
- Maintain traceability from business needs to delivery scope
- Support backlog refinement and dependency discovery

### Goals
- Reduce ambiguity in requirements and expected outcomes
- Improve alignment between business stakeholders and delivery teams
- Minimize rework caused by incomplete requirement definition

### Typical Communication
- Stakeholder interviews and process walkthroughs
- Requirement workshops and backlog refinement sessions
- Clarification notes and requirement traceability updates

### Interaction Points and Handoffs
- With Developers: clarifies business rules, process edge cases, and data expectations during implementation
- With Product Managers: refines discovered needs into prioritized, testable backlog items
- With Project Managers: provides requirement readiness signals and dependency impacts for planning

### Accountability
- Decisions: requirement interpretation recommendations and process clarification outcomes
- Artifacts: requirement briefs, process maps, and traceability matrices
- Risks/Approvals/Handoffs: confirms requirement completeness before planning handoff and escalates business-rule ambiguity risks

---

## Executive Sponsor

### Role Summary
Executive Sponsors provide strategic direction, funding support, and organizational escalation authority. They ensure initiatives stay aligned with business priorities and expected outcomes.

### Responsibilities
- Confirm strategic objectives and success criteria
- Resolve high-impact scope, budget, or priority conflicts
- Sponsor major cross-functional decisions and escalations
- Review milestone outcomes and continued investment rationale

### Goals
- Ensure delivery effort remains aligned with business strategy
- Remove organizational blockers beyond team-level authority
- Increase confidence in business value realization

### Typical Communication
- Steering committee reviews and milestone briefings
- Escalation meetings for business-critical decisions
- Outcome and KPI reviews with leadership stakeholders

### Interaction Points and Handoffs
- With Developers: limited direct interaction; receives technical impact summaries through leads when escalations require sponsor decisions
- With Product Managers: aligns on value outcomes, priority shifts, and success metrics
- With Project Managers: reviews status, approves major plan changes, and resolves escalated risks

### Accountability
- Decisions: strategic priority trade-offs, major funding/resource approvals, and escalation outcomes
- Artifacts: decision records from governance checkpoints and sponsor approvals
- Risks/Approvals/Handoffs: approves major stage-gate or scope-change decisions and hands off execution direction to Product and Project Managers

---

## Customer Support / Customer Success Representative

### Role Summary
Customer Support and Customer Success representatives bring customer-impact context into delivery and ensure post-release readiness. They connect product changes to real user outcomes and support operations.

### Responsibilities
- Provide customer issue trends and feedback signals to the delivery team
- Prepare support enablement materials and known-issue guidance
- Validate support workflows for new features and release changes
- Route post-release insights to product and project tracking

### Goals
- Reduce customer disruption during releases
- Improve response quality and speed for user-facing issues
- Strengthen product decisions with real-world customer evidence

### Typical Communication
- Support readiness checklists before release
- Feedback summaries and incident impact reports
- Cross-functional release debriefs and follow-up actions

### Interaction Points and Handoffs
- With Developers: shares reproducible customer issues and receives technical workaround/fix details
- With Product Managers: contributes customer-impact insights for prioritization and adoption decisions
- With Project Managers: aligns on release communication timing, support readiness, and issue escalation flow

### Accountability
- Decisions: support communication priority and customer escalation routing
- Artifacts: support readiness checklist, FAQ updates, and customer feedback summaries
- Risks/Approvals/Handoffs: confirms support readiness prior to release and hands off customer-impact risks to Product and Project Managers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
