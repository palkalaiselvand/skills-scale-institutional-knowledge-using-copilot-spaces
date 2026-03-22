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

## QA Lead

### Role Summary
The QA Lead owns the overall testing strategy and ensures that quality standards are met before features are released. They bridge the gap between development and release by managing test planning, execution, and reporting.

### Responsibilities
- Define and maintain the test strategy, test plans, and test cases
- Oversee manual and automated testing efforts
- Track and report on defects, test coverage, and quality metrics
- Coordinate with Developers on bug triage and resolution
- Validate acceptance criteria are met before release sign-off

### Goals
- Ensure high-quality, regression-free releases
- Reduce production defects through proactive testing
- Improve test automation coverage over time

### Typical Communication
- Daily standups with the delivery team
- QA status reports and defect summaries
- Sign-off communications to PM before releases

### Interactions with Existing Roles
- Works with **Developers** to coordinate test coverage and resolve defects
- Coordinates with **Project Managers** on release readiness and timelines
- Aligns with **Product Managers** on acceptance criteria and edge cases

---

## UX Designer

### Role Summary
UX Designers advocate for the end user by designing intuitive, accessible interfaces and user flows. They translate product requirements into testable design artifacts.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and user flow diagrams
- Collaborate with Product Managers to refine requirements
- Deliver design specifications and assets to Developers
- Advocate for accessibility and inclusive design

### Goals
- Ensure product interfaces are usable, accessible, and delightful
- Reduce rework by validating designs before development begins
- Align design decisions with user research and data

### Typical Communication
- Design reviews and prototype walkthroughs
- Figma/design tool links shared in issues and PRs
- Usability test findings shared with PdM and PM

### Interactions with Existing Roles
- Works with **Product Managers** to translate requirements into usable interface designs
- Collaborates with **Developers** to ensure design feasibility and implementation fidelity
- Shares usability findings with **Project Managers** to surface UX-related risks

---

## DevOps / Site Reliability Engineer (SRE)

### Role Summary
The DevOps/SRE role ensures that systems are reliable, deployable, and observable. They own the CI/CD pipeline, infrastructure, and incident response tooling to support seamless delivery.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Monitor system health, latency, error rates, and availability
- Manage infrastructure provisioning and configuration
- Support incident response and post-incident reviews
- Collaborate with Developers on build, test, and deployment standards

### Goals
- Maximize system uptime and deployment reliability
- Reduce mean time to recovery (MTTR) during incidents
- Enable fast, safe, and repeatable deployments

### Typical Communication
- On-call schedules and incident alerts
- Infrastructure and deployment documentation
- Post-incident retrospectives and action items

### Interactions with Existing Roles
- Partners with **Developers** to automate testing and deployment processes
- Coordinates with **Project Managers** on deployment windows and release checklists
- Provides observability data to **Product Managers** to inform feature decisions

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for processes, APIs, user guides, and release notes. They ensure that institutional knowledge is captured and accessible to all team members.

### Responsibilities
- Write, review, and maintain process documents, onboarding guides, and release notes
- Collaborate across teams to ensure documentation accuracy and completeness
- Establish and enforce documentation standards and templates
- Keep `docs/` and related knowledge bases up to date
- Identify and close gaps in existing documentation

### Goals
- Reduce onboarding time for new team members
- Ensure all processes and decisions are clearly documented
- Maintain a single source of truth for project knowledge

### Typical Communication
- Documentation reviews with subject-matter experts
- Contributions to `docs/` via PRs
- Coordination with PM on release notes and changelogs

### Interactions with Existing Roles
- Collaborates with **Project Managers** to document processes, decisions, and retrospective action items
- Works with **Developers** to document APIs, onboarding guides, and technical runbooks
- Partners with **Product Managers** to produce user-facing release notes and feature documentation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The seven roles — **Developers**, **Product Managers**, **Project Managers**, **QA Lead**, **UX Designer**, **DevOps/SRE**, and **Technical Writer** — together represent the full cross-functional team needed to deliver high-quality software.

