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

## QA Lead / Quality Assurance

### Role Summary
The QA Lead oversees the quality strategy and execution for the project. They ensure that all deliverables meet acceptance criteria and are ready for production release through comprehensive testing and verification.

### Responsibilities
- Define and oversee the test strategy for each project phase
- Coordinate manual and automated testing efforts
- Verify that acceptance criteria are met before release
- Act as the primary point of contact for quality issues and defect resolution
- Partner with Developers and Project Managers to triage, prioritize, and resolve defects
- Maintain test plans, test cases, and test coverage documentation
- Communicate quality metrics and risks to stakeholders

### Goals
- Minimize production defects and rework
- Ensure high test coverage and quality standards
- Enable fast, confident releases
- Reduce time spent on manual testing through automation

### Typical Communication
- QA status updates in standups and sprint reviews
- Defect reports and test results
- Test strategy and approach documentation
- Collaboration with developers on acceptance criteria clarity
- Post-release quality reports

### Key Interactions
- **With Developers**: Reviews acceptance criteria, tests features, provides timely feedback on defects
- **With Product Managers**: Clarifies expected behaviors and edge cases
- **With Project Managers**: Reports test progress, blockers, and quality risks
- **With UX/UI Designer**: Validates user experience and usability during testing

---

## UX/UI Designer

### Role Summary
The UX/UI Designer creates the user experience and visual interface for features. They work collaboratively with Product Managers and Developers to ensure solutions are intuitive, usable, and aligned with customer needs.

### Responsibilities
- Design user flows, interactions, and information architecture
- Create wireframes and prototypes based on product requirements
- Conduct user research and gather feedback to inform design decisions
- Work closely with Developers to ensure usability is embedded throughout development
- Participate in design reviews and iterate based on feedback
- Document design decisions and maintain design systems/patterns
- Support accessibility standards and inclusive design practices

### Goals
- Deliver intuitive, user-centric solutions
- Reduce user friction and support burden
- Maintain visual and interaction consistency across products
- Enable rapid iteration based on user feedback

### Typical Communication
- Design specs, wireframes, and prototypes
- Design review sessions with stakeholders and developers
- User research findings and design rationale
- Feedback loops during development sprints
- Post-release user feedback and design iterations

### Key Interactions
- **With Product Managers**: Understands customer needs and priorities
- **With Developers**: Collaborates on technical feasibility and implementation
- **With QA Lead**: Works together on usability testing and user acceptance criteria
- **With Customer Support Lead**: Incorporates user feedback and pain points into future iterations

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business needs and technical delivery. They elicit requirements, clarify objectives, and translate business processes into actionable specifications for the delivery team.

### Responsibilities
- Gather and document business requirements from stakeholders
- Map current and future state business processes
- Clarify and prioritize requirements with Product Managers and stakeholders
- Translate business objectives into detailed functional specifications
- Identify dependencies, constraints, and potential risks
- Validate solutions meet business requirements before release
- Document process flows, decision trees, and use cases
- Support change management and stakeholder alignment

### Goals
- Ensure business requirements are fully understood and accurately implemented
- Minimize rework and scope creep through clear specification
- Bridge communication gaps between business and technical teams
- Improve traceability from business goals to delivered features

### Typical Communication
- Requirements documentation and specifications
- Business process diagrams and decision matrices
- Stakeholder meeting facilitation and notes
- Change requests and impact assessments
- Validation checklists and sign-offs

### Key Interactions
- **With Product Managers**: Collaborates on prioritization and requirement validation
- **With Stakeholders**: Gathers business context and success criteria
- **With Developers**: Provides detailed specifications and clarifications
- **With Project Managers**: Supports scope management and requirement traceability

---

## Customer Support Lead

### Role Summary
The Customer Support Lead represents the voice of the customer and end-user throughout the project lifecycle. They gather feedback, identify pain points, and channel insights back into the planning and improvement processes.

### Responsibilities
- Gather post-release user feedback and identify trends
- Synthesize support tickets, user reports, and feedback into actionable insights
- Communicate recurring pain points and improvement opportunities to the delivery team
- Represent the end-user perspective during planning and retrospectives
- Support user documentation and knowledge base content
- Facilitate communication between users and the product delivery team
- Track and report on user adoption and satisfaction metrics
- Identify training or support gaps that inform future improvements

### Goals
- Strengthen the feedback loop from users to the product team
- Reduce user friction and support burden
- Improve user adoption and satisfaction
- Drive continuous product improvement based on real-world usage

### Typical Communication
- User feedback summaries and trend reports
- Support ticket analysis and categorization
- User satisfaction metrics and NPS insights
- Feature requests and improvement recommendations
- Release impact assessments and user adoption tracking

### Key Interactions
- **With Product Managers**: Shares user insights to inform roadmap decisions
- **With UX/UI Designer**: Communicates usability issues and user preferences
- **With Developers**: Clarifies user-reported issues and unexpected behaviors
- **With Project Managers**: Provides user feedback for retrospectives and continuous improvement

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference specific responsibilities and interactions when assigning tasks or resolving cross-team issues.

---

## Role Interaction Matrix

The following table shows how different roles collaborate throughout the project lifecycle:

| Phase | Developer | Product Manager | Project Manager | QA Lead | UX/UI Designer | Business Analyst | Customer Support Lead |
|-------|-----------|-----------------|-----------------|---------|----------------|------------------|----------------------|
| **Initiation** | Provides technical input | Defines vision & goals | Plans timeline | - | - | Clarifies requirements | - |
| **Planning** | Estimates work | Prioritizes features | Manages schedule | Designs test strategy | Creates design specs | Validates requirements | - |
| **Execution** | Builds features | Validates acceptance | Tracks progress | Tests features | Supports implementation | Clarifies specs | - |
| **Review/QA** | Addresses findings | Reviews quality | Manages risks | Verifies acceptance | Reviews usability | Validates completeness | - |
| **Release** | Deploys changes | Announces features | Coordinates release | Verifies release | Final usability check | Confirms scope | Prepares communications |
| **Post-Release** | Monitors issues | Gathers impact data | Conducts retrospective | Reports quality metrics | Collects user feedback | Updates documentation | Gathers customer insights |

---

*Last Updated: 2026-06-09*
*For questions or additions to this documentation, please open an issue in the repository.*
