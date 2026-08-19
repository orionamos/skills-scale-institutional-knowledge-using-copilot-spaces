# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This directory contains comprehensive guidance for running projects at OctoAcme — from initiation through delivery and continuous improvement. These docs are the single source of truth for process, roles, and key artifacts used to plan, execute, and improve projects.

## Process Summary

OctoAcme runs projects with a clear, outcome-oriented lifecycle: Initiation, Planning, Execution, Release, and Close. Work starts with a concise Project One-pager that captures the problem, measurable success metrics, stakeholders, and a high-level timeline. Initiatives that pass the decision gate (clear metrics, stakeholder alignment, and confirmed team availability) move into planning where scope is broken into a prioritized backlog, acceptance criteria are defined, estimates are produced, and an initial risk register is created.

Day-to-day execution is organized around a predictable team rhythm—short daily standups, weekly delivery syncs, and end-of-sprint demos—and a lightweight project board workflow (Backlog → Ready → In Progress → In Review → QA → Done). The pull request workflow emphasizes small, reviewable changes, linking PRs to issues and acceptance criteria, and requiring passing CI (tests, lint, security scans) plus at least one approval before merging. Dependencies are tracked on the project board and escalated during weekly syncs.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize work; Project Managers coordinate delivery, manage risks, and communicate status; Developers implement features and maintain tests and docs; QA validates acceptance criteria and performs manual checks when needed; stakeholders provide inputs and approvals. These personas drive accountability for artifacts (e.g., risk owners, action owners) and determine who receives which communications and escalations.

Quality assurance and releases follow checklist-driven practices to reduce risk and improve observability. Teams write unit and integration tests, run smoke tests for critical flows, and include automated security scanning in CI. Releases follow pre-release requirements (passing CI, release notes, rollback plan), deploy to staging for smoke tests, and use automated pipelines for production deploys where possible. Retrospectives convert learnings into prioritized action items that feed back into the backlog for continuous improvement.

## Quick Overview

OctoAcme follows a structured, customer-first approach to project delivery that emphasizes:

- Clear ownership with named Project Managers and Product Leads
- Iterative delivery of small, testable increments
- Data-informed decisions based on measurable outcomes
- Psychological safety that encourages team feedback and learning

## Documentation Guide

### Start Here
- [Project Management Overview](docs/octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, core roles, and key artifacts

### By Project Lifecycle Phase

**Initiation**
- [Project Initiation Guide](docs/octoacme-project-initiation.md) — Define business need, align stakeholders, and decide go/no-go

**Planning**
- [Project Planning](docs/octoacme-project-planning.md) — Break work into actionable backlog, estimate scope, and identify dependencies

**Execution**
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md) — Team rhythm, workflow management, quality standards, and blocker escalation
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md) — Identify and manage risks; communicate status to stakeholders

**Release**
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md) — Standardized release process, pre-release requirements, and rollback procedures

**Retrospective & Improvement**
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — Run effective retrospectives and track action items

**Reference**
- [Roles and Personas](docs/octoacme-roles-and-personas.md) — Detailed descriptions of key roles (Project Manager, Product Manager, Developers, QA)

## Quick Start — Which doc to read first
1. New to OctoAcme? Start with the Project Management Overview.
2. Preparing a new initiative? Use the Project Initiation Guide to create a one-pager and validate the idea.
3. Ready to plan? Follow Project Planning to create a prioritized backlog and release plan.
4. During delivery? Use Execution & Tracking and Risk Management to run day-to-day work and escalate blockers.
5. Releasing? Follow the Release & Deployment Guide for checklists and rollback plans.
6. After delivery? Run a retrospective and track action items in the backlog.

## Key Principles (Quick Reference)
- Customer-first: prioritize customer value and usability
- Iterative delivery: ship small increments, learn quickly
- Clear ownership: name PM and Product Lead for each project
- Data-informed decisions: define and measure success metrics
- Psychological safety: encourage candid feedback and learning

## Key Artifacts
- Project One-pager / Charter — Problem, goal, success metrics, stakeholders
- Roadmap & Release Plan — Timeline and milestones
- Sprint/Iteration Backlog — Prioritized work with acceptance criteria
- Definition of Done & Acceptance Criteria — Quality gates for work items
- Risk Register — Tracked risks with impact, likelihood, owner, and mitigation
- Retrospective Notes — Action items, owners, due dates

## Contributing & Process Updates
To request additions or changes to these process docs, use the Issue Template: 
- Add or update content via the "Add Content to Project Management Process Docs" template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml

For questions or urgent changes, reach out to your Project Manager or the document owner listed in the relevant file.
