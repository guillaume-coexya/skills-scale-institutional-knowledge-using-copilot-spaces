# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. A person may hold more than one role, and some roles may not be needed on every project. The Project Manager and Product Manager should make role coverage explicit during planning, assigning an accountable owner for each responsibility even when a dedicated specialist is unavailable.

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

### Collaboration
- Work with the Product Manager to clarify acceptance criteria and with the Project Manager to communicate progress, blockers, and dependencies.
- Coordinate implementation with the Engineering/Technical Lead and relevant design, QA, security, data, and operations roles.

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

### Collaboration
- Partner with the Project Manager on scope, priority, and delivery trade-offs, and with stakeholders to validate needs and outcomes.
- Coordinate with design/research and data/analytics roles on discovery, usability, and measurement; consult engineering, QA, security, and operations roles to ensure proposed work is feasible and ready for users.

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

### Collaboration
- Work with the Product Manager to turn priorities into an actionable delivery plan and keep stakeholders informed of progress and decisions.
- Coordinate role owners and cross-team handoffs, track risks and dependencies, and escalate issues; technical and product decisions remain with their accountable leads.

---

## UX/UI Designer or Researcher

### Role Summary
Design and research specialists develop an evidence-based understanding of user needs and shape accessible, usable experiences that support the product goals.

### Responsibilities
- Plan and conduct user research or usability evaluation appropriate to the project
- Create user journeys, interaction designs, prototypes, and design specifications
- Identify accessibility and usability needs and communicate them as testable requirements
- Share research findings and design rationale with the team

### Goals
- Help ensure solutions address real user needs
- Reduce usability and accessibility gaps before release
- Enable consistent, understandable user experiences

### Typical Communication
- Research readouts, design reviews, and prototype walkthroughs
- Design specifications and collaboration with developers and QA during implementation

### Collaboration
- Partner with the Product Manager to inform discovery, validate problem framing, and refine acceptance criteria; the Product Manager remains accountable for product priorities.
- Work with Developers and the Engineering/Technical Lead to assess design feasibility, and with QA to make usability and accessibility expectations verifiable. Share relevant user insights with Customer Support/Operations.

---

## Engineering / Technical Lead

### Role Summary
The Engineering/Technical Lead guides technical direction and implementation coordination for a project or engineering team, helping ensure that solutions are secure, maintainable, and feasible.

### Responsibilities
- Facilitate technical design and document significant decisions
- Help break down technical work, assess estimates, and identify sequencing and integration needs
- Surface technical risks, constraints, and dependencies and propose mitigations
- Support code quality through engineering practices and review

### Goals
- Deliver a coherent, maintainable technical solution
- Make technical trade-offs visible early
- Help the team make predictable progress without compromising necessary quality

### Typical Communication
- Technical design notes and architecture reviews
- Backlog refinement, estimation, and delivery coordination with Developers
- Risk and dependency updates with the Project Manager

### Collaboration
- Guide and coordinate Developers while encouraging shared technical ownership; the lead does not replace individual implementation or review responsibilities.
- Work with the Product Manager on feasibility, options, and scope trade-offs, and with the Project Manager on sequencing, capacity constraints, and technical dependencies.
- Coordinate with Security/Privacy, DevOps/SRE, QA, and Data/Analytics roles where their expertise affects technical decisions.

---

## DevOps / Site Reliability Engineering (SRE) or Release Manager

### Role Summary
This role supports reliable delivery and operation of software through deployment practices, automation, observability, and release coordination. Depending on the team, these responsibilities may be shared between platform, SRE, engineering, and release coordination roles.

### Responsibilities
- Advise on CI/CD, environment, deployment, and rollback readiness
- Define or support operational signals, monitoring, and reliability expectations
- Identify infrastructure and operational risks and help plan mitigations
- Coordinate release readiness and deployment activities when assigned

### Goals
- Make releases repeatable, observable, and recoverable
- Reduce operational risk and improve service reliability
- Ensure the right teams are prepared to support a release

### Typical Communication
- Deployment plans, runbooks, and release readiness reviews
- Monitoring and incident updates with Developers and operations stakeholders
- Release coordination and status updates with the Project Manager

### Collaboration
- Work with Developers and the Engineering/Technical Lead on automation, deployment, and operational design, and with QA on smoke-test and verification plans.
- Coordinate release timing and dependencies with the Project Manager and Product Manager; the Product Manager owns product scope while the Project Manager coordinates the delivery plan.
- Partner with Customer Support/Operations on support readiness, known issues, and post-release monitoring.

---

## Security / Privacy Lead

### Role Summary
The Security/Privacy Lead advises the team on security and privacy requirements, risk assessment, and appropriate review so that risks are considered throughout delivery.

### Responsibilities
- Identify applicable security and privacy requirements and review needs
- Facilitate risk assessment and recommend mitigations or escalation for material risks
- Advise on secure design, data handling, and privacy considerations
- Coordinate security/privacy validation and communicate findings to accountable owners

### Goals
- Surface and address security and privacy risks early
- Support responsible handling of systems and user data
- Make security and privacy requirements clear and actionable

### Typical Communication
- Risk register entries, review findings, and security/privacy guidance
- Design and release readiness consultations with engineering and product
- Escalations through established security incident or risk processes

### Collaboration
- Work with the Product Manager to understand intended data use and user impact, and with the Engineering/Technical Lead and Developers to incorporate safeguards into design and implementation.
- Coordinate with QA on relevant verification and with the Project Manager on review dependencies and escalation tracking. Follow the organization’s security incident process for security incidents.

---

## Data / Analytics Lead

### Role Summary
The Data/Analytics Lead helps define how product outcomes will be measured and how reliable, appropriate instrumentation and analysis will support decisions.

### Responsibilities
- Translate product success metrics into measurement and instrumentation requirements
- Advise on data quality, definitions, and responsible data use
- Coordinate dashboards or analysis needed to assess outcomes
- Identify measurement gaps and communicate limitations in interpreting results

### Goals
- Make product outcomes measurable and interpretable
- Provide trustworthy evidence for product decisions
- Avoid ambiguous or inconsistent metric definitions

### Typical Communication
- Metric definitions and instrumentation plans
- Analysis and dashboard reviews with Product Managers and stakeholders
- Data validation coordination with Developers and QA

### Collaboration
- Partner with the Product Manager to define success measures and interpret results; the Product Manager remains accountable for product outcomes and prioritization.
- Work with Developers and the Engineering/Technical Lead to implement instrumentation, and with QA to verify events and data behavior. Consult the Security/Privacy Lead on data collection and use.

---

## Customer Support / Operations Representative

### Role Summary
Customer Support and Operations representatives bring customer-facing and service-operational knowledge into planning and help prepare teams to support users after delivery.

### Responsibilities
- Share recurring customer issues, support insights, and operational constraints
- Identify support documentation, training, and readiness needs
- Review user-facing communications and known-issue guidance for clarity
- Relay post-release feedback and operational signals to the delivery team

### Goals
- Ensure teams can support users effectively through changes
- Reduce avoidable customer impact and confusion
- Create a feedback loop from support and operations to product planning

### Typical Communication
- Support readiness reviews and release briefings
- Knowledge-base updates, known-issue reports, and post-release feedback
- Operational handoffs and escalation updates

### Collaboration
- Work with the Product Manager to communicate user impact and prioritize feedback, and with the Project Manager to coordinate readiness actions, owners, and stakeholder communications.
- Coordinate with Developers, QA, and DevOps/SRE or the Release Manager on known issues, troubleshooting guidance, and operational handoffs. Escalate service or customer-impacting issues through established channels.

---

## QA / Testing

### Role Summary
QA/Testing validates that delivered work meets acceptance criteria and quality expectations, helping the team identify defects and release risks.

### Responsibilities
- Plan and perform appropriate testing, including integration and end-to-end testing where applicable
- Review acceptance criteria for testability and identify coverage gaps
- Record, communicate, and help triage defects
- Coordinate smoke or release verification with relevant delivery roles

### Goals
- Provide timely evidence about product quality and release readiness
- Detect important defects before they reach users
- Support clear, repeatable validation practices

### Typical Communication
- Test plans, defect reports, and test results
- Planning and triage with Product Managers, Developers, and Project Managers
- Release verification with DevOps/SRE or the Release Manager

### Collaboration
- Work with the Product Manager to clarify acceptance criteria and with Developers and the Engineering/Technical Lead to plan testability and resolve defects.
- Share test status and risks with the Project Manager; coordinate release verification with DevOps/SRE or the Release Manager and consult design, security, and data roles on their relevant quality criteria.

---

## Stakeholders

### Role Summary
Stakeholders represent groups affected by or invested in the project and provide context, feedback, and decisions within their areas of responsibility.

### Responsibilities
- Share business, user, operational, or regulatory needs relevant to the project
- Review plans or deliverables when their input or approval is required
- Make decisions or provide timely feedback within their authority
- Help communicate project impact to the groups they represent

### Goals
- Ensure the project accounts for important needs and constraints
- Support timely, informed decisions
- Help the delivered outcome create the intended value

### Typical Communication
- Kickoffs, milestone reviews, demos, and status updates
- Decision requests and documented feedback
- Release or operational readiness communications as relevant

### Collaboration
- The Project Manager coordinates stakeholder engagement and makes decision owners and due dates visible; the Product Manager gathers product input and remains accountable for product priorities.
- Stakeholders provide input and approvals within their remit but do not replace the accountable delivery, product, technical, quality, security, or operational role owners.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt role assignments to project scope and team size, but explicitly assign an accountable owner to every responsibility and make handoffs clear.
