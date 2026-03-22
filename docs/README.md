# OctoAcme Project Management Documentation

Welcome to the central entry point for all OctoAcme project management process documentation. This README provides an overview of our guiding principles, a summary of how we work, and links to every detailed process document in this folder.

---

## Project Management Philosophy

OctoAcme's approach to project management is grounded in five core principles:

- **Customer-first** — Every decision starts with the impact on the people we serve.
- **Iterative delivery** — We favour small, frequent releases over large, infrequent ones, so we can learn and adapt quickly.
- **Clear ownership** — Each work item, risk, and action has a named owner and a due date.
- **Data-informed decisions** — We use metrics, retrospective findings, and release outcomes to guide prioritisation and process changes.
- **Psychological safety** — We create an environment where team members can raise concerns, admit mistakes, and propose improvements without fear.

---

## Process Summary

OctoAcme follows a structured, lifecycle-driven approach to project management that spans five key phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Every project begins with a lightweight initiation process where a Project One-pager is created to define the problem statement, goals, success metrics, stakeholders, and a high-level timeline. Work only moves forward once a clear decision gate is passed — confirming that success metrics are defined, stakeholders are aligned, and team availability is confirmed. This ensures that only well-scoped, prioritised initiatives receive investment.

Once approved, projects move into **planning**, where the team holds a kickoff meeting, builds a prioritised backlog with acceptance criteria, estimates effort, defines a Definition of Done (DoD), and maps out a release timeline. Risks and cross-team dependencies are captured in a **Risk Register** — tracking impact, likelihood, ownership, and mitigation — and are reviewed regularly throughout delivery. Execution is guided by a consistent team rhythm of daily standups, weekly delivery syncs, and sprint demos, with work flowing through a structured project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull Requests are kept small (≤ 400 lines when possible), require automated CI checks (tests, linting, security scans), and need at least one approval before merging.

OctoAcme's **core roles** include the Project Manager (PM), who owns delivery coordination, schedules, and risk management; the Product Manager (PdM), who defines outcomes and prioritises the backlog; Developers, who implement and test features while collaborating on design; and QA, who validates acceptance criteria. Communication is intentional and tiered — weekly PM/PdM syncs, twice-weekly team standups, and monthly stakeholder updates keep all parties aligned. Escalation follows a clear path from team-level triage → PM → Product Lead → Sponsor, ensuring blockers are resolved at the right level. Structured templates for weekly status updates and incident communications provide consistency and transparency across stakeholder groups.

**Quality and continuous improvement** are deeply embedded in OctoAcme's culture. Releases are gated behind passing CI, security scans, staging smoke tests, and documented rollback plans before any production deployment. After each sprint, release, or significant incident, the team holds a **retrospective** (timeboxed at 45–75 minutes) structured around what went well, what could be improved, and concrete action items with owners and due dates. These action items feed back into the project backlog and are reviewed in weekly PM syncs, ensuring that improvements are tracked, measured, and celebrated — driving an iterative, evidence-based culture of continuous delivery.

---

## Key Stages and Docs

| Document | Description |
|---|---|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | Principles, roles, artifacts, and delivery lifecycle |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Steps, templates, and checklists for starting new work |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Backlogs, estimates, risk registers, and milestones |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Delivery routines, boards, PR conventions, QA & reporting |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Risk registers, stakeholder comms, escalation guidance |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Release types, deployment practices, and checklists |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | After-action reflection and process evolution |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Responsibilities for Devs, PMs, PdMs, and Stakeholders |

---

*To suggest updates or report gaps in this documentation, please use the [issue template](../.github/ISSUE_TEMPLATE/) or open a new issue.*
