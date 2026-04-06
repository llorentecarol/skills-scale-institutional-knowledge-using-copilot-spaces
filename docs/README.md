# OctoAcme Project Management Docs

Welcome! This README provides a quick introduction to the project management process artifacts and how they work together in OctoAcme. The goal is to make it easy for new and current teammates to understand workflows, roles, and where to find more detailed guidance.

## Overview: Project Management Processes at OctoAcme

OctoAcme follows a structured, lifecycle-driven approach to project management grounded in clear principles: customer-first value, iterative delivery, explicit ownership, evidence-based decision making, and psychological safety. Projects begin with a lightweight but comprehensive Project One-pager that captures the business need, success metrics, stakeholder list, and initial resource estimates. Once stakeholder alignment is confirmed, the team moves into detailed planning, where work is broken into prioritized backlog items with clear acceptance criteria, dependencies are mapped, and a release timeline is established.

Three core personas drive execution: **Project Managers** coordinate delivery, manage risks, and maintain transparency; **Product Managers** define what to build, prioritize work, and measure outcomes; and **Developers** implement features and collaborate on design and quality. The team maintains a regular rhythm of daily standups (15 minutes), weekly delivery syncs between PM and Product Manager, and monthly stakeholder updates. A three-level escalation path ensures blockers are surfaced and resolved. All work flows through a GitHub project board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), and small pull requests (<400 lines) are required with automated testing and linting before review.

Quality and testing are embedded throughout delivery: unit tests, integration tests, end-to-end smoke tests, and security scanning in CI are mandatory, with manual QA applied for feature acceptance when needed. Risk management is continuous, with a Risk Register maintained throughout the project lifecycle and reviewed in weekly syncs. Post-project retrospectives capture learnings and convert them into prioritized action items with named owners. This focus on measurement — tracking velocity and burndown, monitoring success metrics, and measuring the impact of improvement initiatives — ensures OctoAcme projects remain data-informed and adaptable throughout their lifecycle.

## Core Lifecycle Phases

| Phase | Description |
|-------|-------------|
| **1. Initiation** | Validate the problem, define success metrics, identify stakeholders, and draft a Project One-pager (problem, goal, metrics, stakeholders, timeline). |
| **2. Planning** | Break work into increments, prioritize the backlog, assign ownership, estimate effort, and develop a risk register and release plan. |
| **3. Execution** | Manage day-to-day progress with standups, syncs, and the project board; require small PRs, linked issues, checklists, and CI quality gates. |
| **4. Release** | Standardize pre-release steps (CI/CD, rollback plans, smoke tests, stakeholder comms) and follow deployment checklists. |
| **5. Retrospective / Improvement** | Hold retros, capture learnings, log action items with named owners, measure follow-through, and refine processes continuously. |

## Key Roles

- **Project Manager** — coordinates delivery, manages risks, maintains transparency, and escalates blockers
- **Product Manager** — defines what to build, prioritizes work, and measures outcomes
- **Developers** — implement features, write tests, and collaborate on design and quality
- **QA** — validates deliverables against acceptance criteria and ensures release readiness
- **Stakeholders** — provide input, approve scope changes, and receive regular progress updates

## 📚 Docs Directory

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management philosophy and principles |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps, templates, and checklists for kicking off a new project |
| [Project Planning](octoacme-project-planning.md) | Backlog structure, estimation, dependency mapping, and release planning |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day delivery workflows, board hygiene, PR standards, and CI requirements |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register process, escalation paths, and stakeholder communication cadence |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklists, deployment steps, rollback procedures, and post-deploy verification |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, action item tracking, and process improvement workflows |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, decision rights, and collaboration expectations for each role |

## Purpose of This Copilot Space

This repository serves as the living knowledge base for OctoAcme's project management practices. The Copilot Space built on these docs is designed to:

- **Centralize scattered knowledge** — bring all process documentation into one versioned, searchable location
- **Enable equal access** — give every team member instant access to processes, decisions, and rationale, regardless of tenure
- **Accelerate onboarding** — help new teammates ramp up quickly by providing clear, discoverable guidance
- **Reduce single-person dependency** — convert tribal knowledge held by individuals into documented, shared practices
- **Feed continuous improvement** — allow validated process improvements to flow back into living documentation that evolves with the team

For more about the purpose of this repository and how project process docs connect to Copilot Spaces, see the main [repository README](../README.md).
