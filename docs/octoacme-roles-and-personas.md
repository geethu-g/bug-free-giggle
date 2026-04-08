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

## UX Designer

### Role Summary
UX Designers guide user research, create wireframes and prototypes, and ensure the product is intuitive and accessible. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Design wireframes, prototypes, and high-fidelity mockups
- Define and maintain design systems and style guides
- Collaborate with Product Managers on requirements and acceptance criteria
- Provide design assets and specifications to Developers
- Participate in sprint reviews to validate implemented designs

### Goals
- Deliver user experiences that are intuitive, accessible, and delightful
- Reduce usability issues identified post-launch
- Ensure design decisions are grounded in user research and data

### Typical Communication
- Design reviews and critique sessions
- Handoff notes and annotated prototypes in design tools
- Participation in sprint planning and retrospectives

### Key Interactions
- **Product Manager**: Collaborates on feature requirements, user stories, and success metrics
- **Developers**: Provides design specs and assets; clarifies intent during implementation
- **Project Manager**: Coordinates design milestones and review timelines
- **Technical Writer**: Aligns on UI copy, tooltips, and in-product guidance

---

## Agile Coach / Scrum Master

### Role Summary
Agile Coaches and Scrum Masters facilitate Agile ceremonies, remove blockers, mentor the team on Agile practices, and drive continuous improvement. They serve the team by creating an environment where delivery can flow smoothly.

### Responsibilities
- Facilitate standups, sprint planning, sprint reviews, and retrospectives
- Identify and remove impediments affecting team velocity
- Coach team members and stakeholders on Agile principles and practices
- Track and follow up on retrospective action items
- Shield the team from unplanned interruptions and scope creep
- Monitor team health and foster a culture of psychological safety

### Goals
- Improve team velocity and predictability over time
- Ensure Agile ceremonies are effective and time-efficient
- Build a self-organizing, high-performing team

### Typical Communication
- Daily standups and retrospective facilitating
- Impediment logs and action item trackers
- Coaching sessions and workshop facilitation

### Key Interactions
- **Project Manager**: Aligns on delivery cadence, risks, and escalations
- **Product Manager**: Ensures backlog is refined and sprint goals are clear
- **Developers**: Removes blockers and coaches on technical Agile practices
- **UX Designer**: Integrates design feedback loops into sprint rhythm

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, manage cloud infrastructure, automate deployments, and ensure system reliability and observability. They enable fast, safe delivery of software to production.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Manage cloud infrastructure using infrastructure-as-code practices
- Set up and maintain monitoring, alerting, and logging systems
- Ensure security, compliance, and access controls in infrastructure
- Support Developers during integration and release activities
- Participate in incident response and post-mortem reviews

### Goals
- Reduce deployment lead time and failure rate
- Maintain high system availability and observability
- Automate repetitive operational tasks to free developer capacity

### Typical Communication
- Release coordination meetings and runbooks
- Infrastructure documentation and architecture diagrams
- Incident retrospectives and on-call rotation schedules

### Key Interactions
- **Developers**: Provides deployment tooling and supports integration workflows
- **Project Manager**: Coordinates release windows and infrastructure milestones
- **Agile Coach / Scrum Master**: Flags infrastructure risks as impediments
- **Technical Writer**: Contributes to runbooks and deployment guides

---

## Technical Writer

### Role Summary
Technical Writers create, update, and maintain project and product documentation. They ensure that knowledge is captured accurately, accessibly, and consistently for internal teams and end users.

### Responsibilities
- Write and maintain process documentation, runbooks, and onboarding guides
- Document architecture decisions, release notes, and API references
- Collaborate with all roles to ensure documentation reflects current practices
- Establish and enforce documentation standards and templates
- Support onboarding by curating role-specific reading paths
- Review in-product copy for clarity in collaboration with UX Designers

### Goals
- Ensure all critical knowledge is documented and easy to find
- Reduce onboarding time for new team members
- Maintain a single source of truth for processes and decisions

### Typical Communication
- Documentation reviews and feedback cycles
- Participation in sprint reviews to capture feature changes
- Coordination with subject-matter experts across all roles

### Key Interactions
- **Developers**: Documents technical processes, APIs, and architecture decisions
- **Product Manager**: Captures product specs and release notes
- **Project Manager**: Maintains project-level documentation and decision logs
- **UX Designer**: Aligns on in-product copy and user-facing documentation
- **DevOps Engineer**: Documents infrastructure runbooks and deployment procedures

---

## Role Interaction Matrix

The table below shows which roles collaborate most closely at each phase of the project lifecycle.

| Role                        | Initiation | Planning | Execution | Release | Retrospective |
|-----------------------------|:----------:|:--------:|:---------:|:-------:|:-------------:|
| Developer                   |            | ✓        | ✓         | ✓       | ✓             |
| Product Manager             | ✓          | ✓        | ✓         |         | ✓             |
| Project Manager             | ✓          | ✓        | ✓         | ✓       | ✓             |
| UX Designer                 | ✓          | ✓        | ✓         |         | ✓             |
| Agile Coach / Scrum Master  |            | ✓        | ✓         |         | ✓             |
| DevOps Engineer             |            | ✓        | ✓         | ✓       |               |
| Technical Writer            |            | ✓        | ✓         | ✓       | ✓             |

### Key Collaboration Points by Phase

- **Initiation**: Product Manager, Project Manager, and UX Designer align on scope, goals, and initial user research.
- **Planning**: All roles participate in backlog refinement, estimation, and sprint planning facilitated by the Agile Coach.
- **Execution**: Developers, UX Designer, DevOps Engineer, and Technical Writer work in parallel to build, design, deploy, and document.
- **Release**: Project Manager, DevOps Engineer, and Technical Writer coordinate deployment, release notes, and stakeholder communications.
- **Retrospective**: All roles except DevOps reflect on outcomes; the Agile Coach facilitates and tracks action items.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

