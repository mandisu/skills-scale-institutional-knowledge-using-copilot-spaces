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
The Technical Lead provides engineering direction for the team. They make architectural decisions, set coding standards, and act as the primary technical liaison between developers, product, and project stakeholders.

### Responsibilities
- Define and own the technical architecture and design decisions
- Review and approve significant code changes and technical approaches
- Identify and mitigate technical debt and systemic risks
- Mentor developers and support their professional growth
- Collaborate with Product and Project Managers on effort estimates and feasibility

### Goals
- Maintain a healthy, scalable, and well-understood codebase
- Enable the team to deliver with confidence and speed
- Reduce technical risk across planning, execution, and release

### Typical Communication
- Architecture decision records (ADRs) and design docs
- Code review feedback and pair programming sessions
- Technical risk discussions in sprint planning and retrospectives

### Interactions with Other Roles
- **Planning:** Partners with Project and Product Managers to size work, flag dependencies, and identify technical blockers early.
- **Execution:** Provides hands-on guidance to developers and resolves escalated technical blockers.
- **Risk Management:** Surfaces technical risks in risk registers and collaborates with the Security/Compliance Partner on mitigations.
- **Release:** Signs off on readiness from a technical quality and stability perspective before deployments.

---

## Delivery Manager / Scrum Master

### Role Summary
The Delivery Manager or Scrum Master facilitates agile ceremonies, removes impediments, and ensures the team follows agreed delivery practices. They focus on team health, flow, and continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and reviews
- Track and communicate team velocity and delivery metrics
- Remove blockers and escalate impediments that cannot be resolved within the team
- Coach the team on agile principles and practices
- Protect the team from unplanned interruptions and scope changes mid-sprint

### Goals
- Maintain a sustainable and predictable delivery cadence
- Foster a culture of continuous improvement and psychological safety
- Ensure ceremonies are effective and outcomes are acted upon

### Typical Communication
- Sprint board updates and velocity charts
- Retrospective action items and follow-up tracking
- Escalation summaries to Project Managers and leadership

### Interactions with Other Roles
- **Planning:** Collaborates with Project and Product Managers to translate roadmap items into sprint-ready work.
- **Execution:** Runs daily standups and monitors the sprint board to keep delivery on track.
- **Risk Management:** Surfaces team-level impediments and flags capacity risks to the Project Manager.
- **Release:** Coordinates sprint review and confirmation that done criteria are met before release activities begin.

---

## UX / Design Lead

### Role Summary
The UX/Design Lead is responsible for the user experience strategy, interaction design, and visual consistency of OctoAcme products. They champion the end-user perspective throughout discovery and delivery.

### Responsibilities
- Conduct user research and synthesize findings into actionable insights
- Create wireframes, prototypes, and high-fidelity designs
- Maintain and evolve the design system and component library
- Collaborate with Product Managers to validate problem statements and solutions
- Review implemented features for design fidelity and usability

### Goals
- Deliver intuitive, accessible, and visually consistent experiences
- Reduce usability issues discovered late in the delivery cycle
- Ensure design decisions are informed by real user data

### Typical Communication
- Design reviews and prototype walkthroughs with product and engineering
- Usability test reports and research summaries
- Design system documentation and annotated specs

### Interactions with Other Roles
- **Planning:** Works with Product Managers during discovery to define user needs and acceptance criteria that include UX requirements.
- **Execution:** Collaborates with Developers to clarify design intent and review implementations early and often.
- **Risk Management:** Identifies usability risks and accessibility gaps that could affect adoption or compliance.
- **Release:** Validates final implementations against approved designs before sign-off.

---

## Security / Compliance Partner

### Role Summary
The Security/Compliance Partner ensures that OctoAcme products and processes adhere to security standards, regulatory requirements, and internal policies. They act as an embedded advisor throughout the delivery lifecycle.

### Responsibilities
- Review features and architectures for security vulnerabilities and compliance gaps
- Maintain threat models and security documentation
- Define and enforce secure development guidelines and standards
- Coordinate security testing (e.g., penetration testing, vulnerability scanning)
- Act as the point of contact for audits, regulatory inquiries, and security incidents

### Goals
- Prevent security and compliance issues from reaching production
- Build a security-conscious culture across engineering and product teams
- Ensure the organization meets its regulatory and contractual obligations

### Typical Communication
- Security review outcomes and sign-off documentation
- Threat model updates and risk assessments
- Incident response communications and post-mortems

### Interactions with Other Roles
- **Planning:** Reviews epics and features for security and compliance implications early, so requirements are captured before implementation begins.
- **Execution:** Provides guidance to Developers and Technical Lead on secure coding practices and reviews sensitive changes.
- **Risk Management:** Owns the security and compliance section of the risk register and escalates critical findings to the Project Manager and leadership.
- **Release:** Completes a security sign-off checklist before production deployments and approves any exceptions.

---

## Support / Customer Operations Representative

### Role Summary
The Support/Customer Operations Representative is the voice of the customer inside the delivery team. They surface real-world issues, relay user feedback, and ensure that operational readiness is considered during development.

### Responsibilities
- Log, triage, and escalate customer-reported bugs and feature requests
- Represent the customer perspective in backlog grooming and planning sessions
- Develop and maintain support runbooks, FAQs, and knowledge base articles
- Validate that new features and changes are supportable and well-documented before release
- Coordinate with the team on customer communications for planned changes or incidents

### Goals
- Reduce customer-impacting issues through proactive involvement in delivery
- Ensure support teams are prepared and equipped before any release
- Close the feedback loop between customers and the product and engineering teams

### Typical Communication
- Escalated support tickets and trend summaries shared with Product and Project Managers
- Pre-release readiness reviews and support documentation reviews
- Incident update communications to affected customers

### Interactions with Other Roles
- **Planning:** Brings patterns from support tickets into backlog refinement to prioritize quality-of-life and reliability improvements.
- **Execution:** Reviews work-in-progress documentation and release notes for accuracy and clarity.
- **Risk Management:** Flags customer-facing risks (e.g., breaking changes, degraded experiences) to the Project Manager and Product Manager.
- **Release:** Confirms that support documentation, runbooks, and customer communications are ready before release sign-off.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

