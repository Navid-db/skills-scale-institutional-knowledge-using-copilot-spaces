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

### Cross-Role Interactions
- **With Product Managers:** Clarify requirements, acceptance criteria, and technical constraints
- **With Project Managers:** Provide estimates, report progress, and flag technical risks
- **With UX Designers:** Collaborate on implementation feasibility and resolve design-tech gaps
- **With QA Lead:** Coordinate on testing approaches, bug prioritization, and quality metrics
- **With DevOps Engineers:** Align on deployment strategies, infrastructure needs, and monitoring

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

### Cross-Role Interactions
- **With Developers:** Define and refine feature requirements, prioritize bug fixes and technical debt
- **With Project Managers:** Align on scope, timelines, and resource allocation
- **With UX Designers:** Validate user experience aligns with product vision and strategy
- **With Business Analysts:** Collaborate on requirements discovery and stakeholder needs
- **With QA Lead:** Define acceptance criteria and quality gates for releases
- **With Customer Success Representatives:** Gather customer feedback and prioritize feature requests

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

### Cross-Role Interactions
- **With Product Managers:** Coordinate delivery timelines, manage scope changes, and align on priorities
- **With Developers:** Track progress, identify blockers, and facilitate resolution of dependencies
- **With QA Lead:** Plan testing phases, coordinate quality gates, and manage release readiness (see [Risk Management](octoacme-risks-and-communication.md))
- **With DevOps Engineers:** Schedule deployments, coordinate rollback plans, and manage release logistics
- **With Business Analysts:** Ensure requirements are captured and tracked appropriately

---

## UX Designer

### Role Summary
UX Designers are responsible for designing the user experience, ensuring usability and accessibility. They collaborate closely with Product Managers and Developers to realize design intent and maintain consistency across the product.

### Responsibilities
- Create user journeys, flows, wireframes, and mockups
- Validate designs with user research and usability testing
- Coordinate with Developers to resolve implementation questions and edge cases
- Maintain design consistency and accessibility standards across releases
- Document design patterns and component libraries

### Goals
- Deliver intuitive and accessible user experiences
- Ensure design consistency across all product touchpoints
- Reduce user friction and improve satisfaction metrics
- Advocate for user needs throughout the development process

### Typical Communication
- Design reviews and critique sessions
- User research findings and testing reports
- Design specifications and handoff documentation
- Accessibility compliance documentation

### Cross-Role Interactions
- **With Product Managers:** Align design solutions with product strategy and user needs
- **With Developers:** Collaborate on implementation feasibility, provide design specifications, and resolve edge cases
- **With QA Lead:** Participate in usability testing and validate design implementation
- **With Business Analysts:** Incorporate business requirements into user experience design

---

## Business Analyst

### Role Summary
Business Analysts act as a liaison between business stakeholders and technical teams, capturing business requirements and translating them into actionable backlog items. They ensure technical delivery aligns with stakeholder outcomes.

### Responsibilities
- Lead requirements discovery and documentation
- Translate stakeholder goals into measurable outcomes
- Facilitate backlog refinement and prioritization
- Create process flows and business requirement documents
- Analyze business impacts of proposed solutions

### Goals
- Bridge communication gaps between business and technical teams
- Ensure complete and accurate requirement capture
- Reduce rework by clarifying requirements upfront
- Support data-driven decision making

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and business models
- Stakeholder interview summaries
- Acceptance criteria definitions

### Cross-Role Interactions
- **With Product Managers:** Regular syncs on roadmap priorities and feature requirements
- **With Developers:** Clarify business context, answer requirement questions, and validate solutions
- **With Project Managers:** Support project planning with requirements analysis and impact assessments
- **With Customer Success Representatives:** Gather insights on customer needs and pain points

---

## QA Lead

### Role Summary
QA Leads coordinate testing strategy, ensure quality standards, and manage QA team activities. They act as the quality gatekeeper before releases and help establish quality metrics across the organization.

### Responsibilities
- Define and implement test strategy for releases
- Coordinate both manual and automated testing efforts
- Track and report on quality metrics and test coverage
- Establish quality gates and acceptance criteria standards
- Lead bug triage and prioritization
- Manage test environments and data

### Goals
- Maintain high product quality and reliability
- Minimize defect escape rate to production
- Improve testing efficiency and coverage
- Build a culture of quality across the team

### Typical Communication
- Test plans and testing status reports
- Bug reports and quality metrics dashboards
- Test case documentation and automation reports
- Quality gate reviews and release readiness reports

### Cross-Role Interactions
- **With Developers:** Collaborate on testability, review code for quality, and coordinate bug fixes
- **With Product Managers:** Ensure acceptance criteria coverage and validate feature completeness
- **With Project Managers:** Report on testing progress, quality risks, and release readiness (see [Risk Management](octoacme-risks-and-communication.md))
- **With UX Designers:** Conduct usability testing and validate user experience implementation
- **With DevOps Engineers:** Coordinate test environment setup and deployment validation

---

## DevOps Engineer

### Role Summary
DevOps Engineers own CI/CD pipelines, deployment processes, and system reliability. They bridge development and operations, ensuring smooth, automated, and reliable software delivery.

### Responsibilities
- Manage automated deployments and rollback procedures
- Monitor system stability, performance, and scalability
- Maintain operational documentation and runbooks
- Implement and maintain CI/CD pipelines
- Manage infrastructure as code and cloud resources
- Ensure security compliance in deployment processes

### Goals
- Maximize deployment frequency and reliability
- Minimize downtime and mean time to recovery
- Automate repetitive operational tasks
- Ensure system observability and monitoring

### Typical Communication
- Deployment notifications and schedules
- Incident reports and post-mortems
- Infrastructure documentation and architecture diagrams
- Performance metrics and monitoring dashboards

### Cross-Role Interactions
- **With Developers:** Support integration needs, provide deployment tooling, and troubleshoot production issues
- **With Project Managers:** Share deployment schedules, coordinate release windows, and report on operational metrics
- **With QA Lead:** Provide test environments, coordinate deployment validation, and support testing infrastructure
- **With Product Managers:** Report on system performance and capacity planning needs

---

## Customer Success Representative

### Role Summary
Customer Success Representatives represent the customer voice, gather feedback, and ensure post-launch insights circulate back to the product team. They advocate for customers and help drive product adoption and satisfaction.

### Responsibilities
- Collect, organize, and report user feedback
- Collaborate with PMs and project leads to enhance product satisfaction
- Participate in retrospectives to surface customer-impacting issues
- Track customer health metrics and adoption trends
- Provide product training and support to customers
- Identify expansion opportunities and at-risk accounts

### Goals
- Maximize customer satisfaction and retention
- Ensure customer feedback informs product decisions
- Drive product adoption and feature utilization
- Build strong customer relationships

### Typical Communication
- Customer feedback reports and satisfaction surveys
- Feature request summaries and usage analytics
- Escalation reports for critical customer issues
- Success stories and case studies

### Cross-Role Interactions
- **With Product Managers:** Share customer insights, prioritize feature requests, and validate product roadmap alignment
- **With Developers:** Communicate customer-reported bugs and provide reproduction steps
- **With QA Lead:** Report quality issues impacting customers and validate fixes
- **With Business Analysts:** Provide customer perspective on requirements and business value
- **With Project Managers:** Participate in retrospectives and continuous improvement discussions (see [Retrospective Process](octoacme-retrospective-and-continuous-improvement.md))

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

