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
UX Designers ensure the product's workflows and interfaces are usable, accessible, and consistent with brand standards. They bridge user needs with technical and business constraints through research, design, and iterative testing.

### Responsibilities
- Design product workflows, wireframes, and interfaces with focus on usability and accessibility
- Facilitate user research and testing to validate design decisions
- Provide design specifications and handoff documentation to developers
- Collaborate in backlog refinement to define user stories and acceptance criteria
- Review deliverables during iteration demos and provide design feedback
- Advocate for user needs and usability in trade-off discussions

### Goals
- Deliver intuitive, accessible user experiences
- Reduce friction in user workflows and increase adoption
- Ensure design consistency across the product

### Typical Communication
- Design critique sessions with stakeholders and developers
- User research findings and design rationale documentation
- Collaboration in sprint planning and review meetings
- Feedback during code reviews and QA testing phases

### Key Interactions
- **Product Managers**: Collaborate on priorities, user stories, and success metrics
- **Developers**: Partner on feasibility, technical handoff, and implementation details
- **QA/Testing**: Validate design against acceptance criteria and user expectations
- **Stakeholders**: Present designs and incorporate feedback

---

## Tech Lead / Architect

### Role Summary
Tech Leads and Architects guide the technical direction of projects, ensure code quality and system scalability, and remove technical blockers. They work closely with developers and collaborate with product and project leadership on technical trade-offs.

### Responsibilities
- Define and communicate technical direction, architecture, and technology stack decisions
- Conduct code reviews and ensure adherence to quality standards
- Advise on scalability, performance, and security considerations
- Resolve technical blockers and mentor developers on complex problems
- Participate in sprint planning and estimation discussions
- Lead design reviews and architecture discussions

### Goals
- Maintain high code quality and maintainability
- Ensure system scalability and reliability
- Enable team velocity through clear technical guidance

### Typical Communication
- Technical design documents and architecture reviews
- Code review comments and feedback
- Architecture decision records (ADRs)
- Participation in planning and retrospectives

### Key Interactions
- **Developers**: Support implementation, conduct code reviews, resolve blockers
- **Project Managers**: Collaborate on timeline feasibility and resource planning
- **Product Managers**: Discuss technical trade-offs and feasibility of features
- **DevOps/Release Engineers**: Coordinate on infrastructure and deployment considerations

---

## QA Lead / QA Engineer

### Role Summary
QA Leads and QA Engineers own the testing strategy, ensure product quality, and verify that deliverables meet acceptance criteria and user expectations. They work throughout the development lifecycle to prevent defects and enable confident releases.

### Responsibilities
- Define QA process, testing strategy, and quality criteria for the project
- Select and maintain testing tools and frameworks
- Write and execute test plans, including unit, integration, and end-to-end tests
- Report on testing progress and product quality metrics
- Verify that acceptance criteria are met before moving work to "Done"
- Collaborate with developers on bug triage and regression testing

### Goals
- Ensure product quality and user satisfaction
- Catch defects early and reduce production issues
- Enable rapid, confident releases

### Typical Communication
- Test plans and QA status reports
- Bug reports with reproduction steps and severity levels
- Participation in acceptance criteria discussions
- Collaboration during sprint planning and demos

### Key Interactions
- **Developers**: Partner on issue discovery, fixes, and test coverage
- **Product Managers**: Clarify acceptance criteria and validate feature completeness
- **Project Managers**: Communicate quality status and release readiness
- **UX Designers**: Validate design implementation and user experience

---

## Stakeholder (Business / Customer)

### Role Summary
Stakeholders represent business, customer, or end-user interests in projects. They provide requirements, feedback, and approvals at key milestones to ensure the project delivers value and aligns with organizational goals.

### Responsibilities
- Communicate business needs, priorities, and constraints
- Provide feedback on prototypes, demos, and deliverables
- Participate in milestone reviews and sign-off ceremonies
- Escalate issues or changes that impact business value
- Help define success metrics and validate outcomes

### Goals
- Ensure product delivers business value
- Reduce misalignment between stakeholder expectations and delivery
- Maintain visibility and confidence in project progress

### Typical Communication
- Requirements and prioritization inputs
- Participation in demos and review meetings
- Feedback and approval for milestone gates
- Executive summaries and status updates

### Key Interactions
- **Product Managers**: Clarify requirements, priorities, and business context
- **Project Managers**: Track progress, escalations, and milestone status
- **UX Designers**: Provide feedback on usability and user experience
- **Developers & QA**: Participate in acceptance testing and sign-off

---

## DevOps / Release Engineer

### Role Summary
DevOps and Release Engineers build, maintain, and operate the infrastructure and deployment pipelines that enable reliable, frequent releases. They ensure deployments are automated, traceable, and recoverable.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, environments, and configuration management
- Monitor deployments and production systems for issues
- Coordinate releases and manage rollback procedures
- Lead incident response and post-incident reviews when deployments cause issues
- Work with developers on build optimization and deployment strategies

### Goals
- Enable fast, safe, and frequent releases
- Minimize deployment failures and reduce time-to-recovery
- Maintain high system availability and observability

### Typical Communication
- Deployment runbooks and release procedures
- Build and deployment status dashboards
- Incident notifications and post-mortems
- Collaboration during release planning and retrospectives

### Key Interactions
- **Developers**: Support on build optimization, deployment questions, and CI integration
- **QA/Testing**: Validate builds, manage test environments, and support smoke tests
- **Project Managers**: Coordinate deployment windows and communicate release status
- **Tech Leads**: Collaborate on infrastructure decisions and scaling strategies

---

## Support / Operations

### Role Summary
Support and Operations teams handle post-release customer issues, gather feedback, and close the feedback loop by communicating recurring issues back to the product and engineering teams. They are the voice of the customer in production.

### Responsibilities
- Respond to customer issues and provide first-line troubleshooting
- Document and categorize recurring incidents and error patterns
- Communicate product usage insights and customer feedback to the team
- Escalate bugs or critical issues to the engineering team
- Participate in incident response and post-incident reviews
- Help prioritize improvements based on customer impact

### Goals
- Maximize customer satisfaction and retention
- Reduce time-to-resolution for customer issues
- Feed customer insights back into product planning

### Typical Communication
- Issue reports and escalation tickets
- Customer feedback and usage analytics
- Incident summaries and trends
- Participation in retrospectives and product planning

### Key Interactions
- **Project Managers**: Escalate issues, communicate customer impact, and coordinate fixes
- **Developers**: Provide detailed issue information, collaborate on bug triage and fixes
- **QA/Testing**: Report patterns for regression testing and quality improvements
- **Product Managers**: Share customer feedback, usage trends, and feature requests

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to these role descriptions when defining responsibilities, communication patterns, and interactions in project planning and execution.
