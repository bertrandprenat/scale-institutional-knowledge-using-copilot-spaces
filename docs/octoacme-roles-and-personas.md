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

## QA/Testing Specialist

### Role Summary
QA/Testing Specialists validate that features meet acceptance criteria and quality standards before release. They design and execute test plans, automate regression coverage, and act as the quality gate for the team.

### Responsibilities
- Define and execute test plans, test cases, and acceptance tests
- Build and maintain automated test suites (unit, integration, end-to-end)
- Validate features against acceptance criteria defined by PdM and BA
- Report defects and track them through resolution
- Participate in sprint ceremonies to identify testability requirements early
- Perform manual exploratory testing for feature acceptance

### Goals
- Prevent regressions and surface defects before production
- Increase automated coverage to reduce manual testing overhead
- Ensure Definition of Done includes quality checkpoints

### Typical Communication
- Daily standups and sprint planning to flag testing risks
- Bug reports and test result summaries shared with PM and PdM
- Coordination with Developers on testability and CI pipeline integration

### Interactions with Other Roles
- **Developers**: Collaborate on test infrastructure and reproduce/verify bug fixes
- **Product Manager (PdM)**: Clarify acceptance criteria and edge cases in feature specs
- **Project Manager (PM)**: Report test status and block/unblock release readiness
- **Business Analyst**: Align on requirements to ensure test coverage matches business intent
- **DevOps Engineer**: Integrate automated tests into CI/CD pipelines

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers ensure that software is reliably built, deployed, and operated. They own CI/CD pipelines, cloud infrastructure, monitoring, and security scanning tooling, enabling fast and safe delivery.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines and build automation
- Manage cloud infrastructure and environment provisioning (infrastructure as code)
- Implement and monitor security scanning in the delivery pipeline
- Operate observability tooling (logging, metrics, alerting)
- Automate deployment and rollback procedures
- Serve as the on-call point of contact for security-related infrastructure incidents
- Advise teams on operational best practices and cost optimization

### Goals
- Maximize deployment frequency while minimizing change failure rate
- Ensure system reliability through automation and proactive monitoring
- Embed security and compliance checks into every pipeline stage

### Typical Communication
- Incident reports and post-mortems shared with PM and engineering leads
- Infrastructure change proposals reviewed with Developers and security stakeholders
- Pipeline status and alerting dashboards visible to the whole team

### Interactions with Other Roles
- **Developers**: Support local dev environments, review deployment configs, and pair on pipeline issues
- **Project Manager (PM)**: Communicate infrastructure dependencies and deployment readiness
- **QA/Testing Specialist**: Integrate automated tests and quality gates into pipelines
- **Scrum Master**: Surface infrastructure impediments in retrospectives
- **Business Analyst**: Clarify non-functional requirements (availability, performance, compliance)

---

## Scrum Master

### Role Summary
The Scrum Master facilitates agile ceremonies, protects team focus, and removes process impediments. They coach the team and organization on agile practices, enabling continuous improvement and sustainable delivery pace.

### Responsibilities
- Facilitate sprint ceremonies: planning, daily standups, reviews, and retrospectives
- Identify and remove blockers; escalate when resolution is outside the team's control
- Coach team members and stakeholders on agile principles and practices
- Track team velocity and health metrics; surface trends to leadership
- Protect the team from unplanned work and scope creep during sprints
- Support the PM and PdM in refining the backlog and managing dependencies

### Goals
- Maintain a consistent, predictable delivery cadence
- Foster a culture of continuous improvement and psychological safety
- Reduce time blocked by impediments or unclear process

### Typical Communication
- Daily facilitation of standups and asynchronous status updates
- Sprint retrospective action items published to the team
- Coaching conversations and process reviews with PM and PdM

### Interactions with Other Roles
- **Project Manager (PM)**: Align on delivery risks, dependencies, and milestone commitments
- **Product Manager (PdM)**: Support backlog refinement and sprint goal clarity
- **Developers**: Remove technical and organizational blockers; support realistic sprint commitments
- **QA/Testing Specialist**: Ensure quality gates are reflected in the Definition of Done
- **UX Designer**: Include design review and usability checkpoints in sprint cadence

---

## UX Designer

### Role Summary
UX Designers ensure that features are intuitive, accessible, and aligned with real user needs. They represent the end-user perspective throughout the project lifecycle—from early discovery through acceptance testing.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity design assets
- Define and advocate for UI/UX acceptance criteria in collaboration with PdM
- Ensure designs meet accessibility standards (e.g., WCAG)
- Review implemented features against design specifications before sign-off
- Contribute to and maintain a shared design system or component library

### Goals
- Deliver experiences that meet user needs and reduce friction
- Ensure every shipped feature meets agreed usability and accessibility standards
- Bridge the gap between business requirements and intuitive user interactions

### Typical Communication
- Design critiques and review sessions with Developers and PdM
- Usability test findings shared with PM, PdM, and Business Analyst
- Design asset handoffs and annotation in the team's collaboration tooling

### Interactions with Other Roles
- **Product Manager (PdM)**: Co-define user stories and acceptance criteria with a user-experience lens
- **Developers**: Provide design specs, answer implementation questions, and review delivered UI
- **Business Analyst**: Incorporate user-research insights into requirements and process flows
- **QA/Testing Specialist**: Define usability and visual-regression test cases
- **Scrum Master**: Ensure design review milestones are accounted for in sprint planning

---

## Business Analyst

### Role Summary
Business Analysts bridge business needs and technical implementation. They work with stakeholders, PdM, and PM to gather, document, and validate requirements, ensuring that delivered solutions meet intended business outcomes.

### Responsibilities
- Elicit and document business and user requirements through workshops and stakeholder interviews
- Translate business needs into clear, testable acceptance criteria and user stories
- Map current and future-state process flows; identify inefficiencies and improvement opportunities
- Maintain the requirements traceability matrix and change log
- Support validation of delivered features against business goals and success metrics
- Facilitate sign-off with stakeholders on requirements and delivered outcomes

### Goals
- Ensure requirements are complete, unambiguous, and agreed before development begins
- Reduce rework caused by misunderstood or changing requirements
- Provide clear business context that helps the team make better technical trade-offs

### Typical Communication
- Requirements workshops and stakeholder interviews documented and shared with PM and PdM
- Regular review of acceptance criteria with QA/Testing Specialist and Developers
- Change requests and impact assessments communicated to PM for scheduling

### Interactions with Other Roles
- **Product Manager (PdM)**: Translate product vision into detailed, prioritized requirements
- **Project Manager (PM)**: Surface scope changes and dependency impacts on the project plan
- **Developers**: Clarify requirements and resolve ambiguity during implementation
- **QA/Testing Specialist**: Ensure test cases trace back to documented business requirements
- **UX Designer**: Incorporate user-research data to refine requirements and process flows

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

