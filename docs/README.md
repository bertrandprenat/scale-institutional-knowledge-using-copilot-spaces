# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub. This README provides a brief overview of our PM approach and links to the detailed process documents that guide our teams from project initiation through retrospective.

---

## Table of Contents

- [Overview](#overview)
- [Core Principles](#core-principles)
- [Key Roles & Personas](#key-roles--personas)
- [Project Lifecycle Overview](#project-lifecycle-overview)
- [Communication & Cadence](#communication--cadence)
- [Getting Started / How to Use These Docs](#getting-started--how-to-use-these-docs)
- [Process Documents](#process-documents)

---

## Overview

OctoAcme follows a comprehensive, lifecycle-based project management approach that emphasizes customer value, iterative delivery, and clear ownership. The framework spans five key phases: **Initiation**, where business needs and success metrics are validated with stakeholders; **Planning**, where work is broken into shippable increments with acceptance criteria and risk identification; **Execution**, where teams build and track progress through daily standups and project boards; **Release**, where features move to production with pre-release quality gates and rollback plans; and **Close & Retrospective**, where learnings are captured and converted into actionable improvements. This structured yet flexible lifecycle ensures alignment across stakeholders, reduces unplanned work, and enables consistent delivery.

The organization operates with clearly defined roles and responsibilities that foster collaboration and accountability. **Project Managers** coordinate schedules, risks, and communications to keep teams on track and escalate blockers appropriately. **Product Managers** define what should be built, prioritize the backlog based on customer impact, and measure outcomes using success metrics established during initiation. **Developers** implement features with quality and testability in mind, participating in design reviews and risk identification. **QA and Testing teams** validate quality and acceptance criteria. This multi-disciplinary structure ensures that product decisions, technical feasibility, and project delivery are balanced throughout execution.

Quality and risk management are embedded into every phase of OctoAcme projects. The execution workflow requires small pull requests (≤400 lines when possible) with automated CI testing, linting, and security scanning before review. Teams maintain a **Risk Register** that tracks identified risks with impact, likelihood, mitigation plans, and ownership. A three-level escalation path—team-level triage in standups, PM escalation to Product Leads, and sponsor-level escalation for business-impacting issues—ensures rapid response to blockers. Additionally, release requirements include acceptance criteria verification, staging smoke tests, and documented rollback plans to minimize production risk.

Communication and continuous improvement are central to OctoAcme's culture. Weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates maintain transparency and alignment. Teams track velocity and burndown to monitor progress against milestones, and comprehensive retrospectives held after sprints or releases convert team feedback into documented action items with clear owners and success criteria. By combining structured processes with psychological safety and data-informed decisions, OctoAcme enables teams to scale delivery while maintaining quality and fostering a culture of learning and improvement.

---

## Core Principles

- **Customer-first:** prioritize customer value and usability in every decision.
- **Iterative delivery:** ship small, testable increments to reduce risk and gather feedback early.
- **Clear ownership:** every project has a named Project Manager and Product Lead accountable for outcomes.
- **Data-informed decisions:** measure impact and iterate based on evidence, not assumptions.
- **Psychological safety:** encourage open feedback, learning from failure, and continuous improvement.

---

## Key Roles & Personas

| Role | Responsibilities |
|------|-----------------|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk, and communications; escalates blockers appropriately. |
| **Product Manager (PdM)** | Defines outcomes, prioritizes the backlog based on customer impact, and measures success metrics. |
| **Developers** | Implement features with quality and testability in mind; participate in design reviews and risk identification. |
| **QA / Testing** | Validate quality and acceptance criteria; own pre-release smoke testing. |
| **Stakeholders** | Provide inputs, approvals, and business context throughout the project lifecycle. |

For detailed persona profiles, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

---

## Project Lifecycle Overview

| Phase | Key Activities |
|-------|---------------|
| **1. Initiation** | Define problem statement, identify stakeholders, validate business need, set success metrics. |
| **2. Planning** | Break work into shippable increments, define acceptance criteria, identify risks and dependencies. |
| **3. Execution** | Build, test, and review in iterations; track progress via standups and project boards. |
| **4. Release** | Verify acceptance criteria, run staging smoke tests, deploy to production with a rollback plan. |
| **5. Close & Retrospective** | Capture learnings, document action items with owners, and feed improvements back into the process. |

For detailed guidance on each phase, see the [Process Documents](#process-documents) below.

---

## Communication & Cadence

| Meeting / Update | Frequency | Participants |
|-----------------|-----------|-------------|
| PM + PdM sync | Weekly | Project Manager, Product Manager |
| Delivery standup | Twice-weekly (or as agreed) | Full delivery team |
| Stakeholder update | Monthly | PM, PdM, Stakeholders |
| Escalation (ad-hoc) | As needed | PM, Product Lead, Sponsor |

Teams also track **velocity** and **burndown** to monitor progress against milestones and provide transparent, data-driven status reporting.

---

## Getting Started / How to Use These Docs

1. **New to OctoAcme PM?** Start with the [Project Management Overview](./octoacme-project-management-overview.md) to understand our principles, roles, and lifecycle at a high level.
2. **Starting a new project?** Follow the [Project Initiation](./octoacme-project-initiation.md) guide to validate the business need and set up your project charter.
3. **Planning your next sprint?** See [Project Planning](./octoacme-project-planning.md) for backlog structuring, acceptance criteria, and milestone planning.
4. **In active delivery?** Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for daily workflows, PR standards, and quality practices.
5. **Managing risks or blockers?** See [Risks & Communication](./octoacme-risks-and-communication.md) for the Risk Register template and escalation path.
6. **Preparing for a release?** Use the [Release & Deployment](./octoacme-release-and-deployment.md) guide for pre-release gates and rollback planning.
7. **After a sprint or release?** Run a retrospective using [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).

> **Tip:** Add these docs to your `.copilot/` folder to make them available as context in GitHub Copilot Spaces, giving all team members role-specific, process-aware guidance.

---

## Process Documents

| Document | Description |
|----------|-------------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Foundational principles, core roles, key artifacts, and lifecycle summary. |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed role definitions for Project Managers, Product Managers, Developers, and QA. |
| [Project Initiation](./octoacme-project-initiation.md) | Gate 1 checklist, stakeholder alignment, and problem statement validation. |
| [Project Planning](./octoacme-project-planning.md) | Scope definition, backlog creation, acceptance criteria, and milestone planning. |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Day-to-day delivery workflows, PR standards, CI practices, and quality gates. |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk Register format, escalation path, and communication templates. |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Deployment safety checklist, smoke testing, and rollback procedures. |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective facilitation guide and action item tracking. |
