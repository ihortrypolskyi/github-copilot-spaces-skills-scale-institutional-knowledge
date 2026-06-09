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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional personas / roles to add (proposed)

Below are recommended personas to add to the standard roles above. Each entry includes a short summary, key responsibilities, and typical interactions with existing roles to improve clarity and accountability.

### QA Lead
Summary:
Owns test strategy, planning, and verification activities across features/releases.

Responsibilities:
- Define test strategy for features (unit, integration, E2E, regression)
- Maintain automated test pipelines and coordinate manual testing where required
- Triage test failures, maintain test documentation, and track quality-related metrics
- Approve release readiness from a QA perspective

Interactions:
- Works closely with Developers to ensure tests exist and pass in CI
- Partners with PM and PdM on acceptance criteria and definition of done
- Coordinates with Release Manager and Support Lead on post-release smoke checks

Success signals:
- High test coverage of critical flows
- Low production escape rate for regressions

---

### UX Designer / Product Designer
Summary:
Focuses on user experience, research, and design deliverables that shape product behavior and interfaces.

Responsibilities:
- Conduct user research, usability testing, and create prototypes
- Produce wireframes, flows, and visual assets
- Define UX acceptance criteria and review implementation
- Advocate for accessibility and usability standards

Interactions:
- Works with Product Manager to translate user needs into features
- Reviews PRs for UX changes and partners with Developers to ensure fidelity
- Coordinates with QA Lead for usability and accessibility checks

Success signals:
- Improved user task completion rates and lower UX-related support tickets

---

### Release Manager
Summary:
Coordinates release planning, deployment execution, and rollback/mitigation planning.

Responsibilities:
- Maintain the release calendar and schedule release windows
- Ensure deployment runbooks and rollback plans exist
- Coordinate stakeholders (PM, DevOps, QA, Support) during release
- Verify post-release checks and lead communications to stakeholders

Interactions:
- Works with DevOps/Platform Engineer to run deployments
- Informs PM/PdM and Support Lead about release impacts and timing
- Collaborates with QA Lead on release gating criteria

Success signals:
- Predictable, low-incident deployments and fast recovery for failed releases

---

### Business Analyst (BA)
Summary:
Translates stakeholder/business needs into clear, testable requirements and user stories.

Responsibilities:
- Elicit requirements, document acceptance criteria and edge cases
- Create or refine user stories and examples
- Help prioritize scope and clarify functional questions during development
- Assist testing by providing domain knowledge and test scenarios

Interactions:
- Works with Product Manager and Stakeholders to capture requirements
- Supports Developers and QA Lead with clarifications and validation during implementation

Success signals:
- Reduced rework due to ambiguous requirements and fewer scope-related clarifications during sprints

---

### DevOps / Platform Engineer
Summary:
Builds and maintains CI/CD, infrastructure, observability, and deployment automation.

Responsibilities:
- Maintain CI pipelines, deployment automation, and infrastructure-as-code
- Ensure monitoring, alerting, and reliability best practices are in place
- Support Release Manager with deployment runbooks and post-deploy verifications
- Secure and scale platform components

Interactions:
- Works with Developers to ensure smooth CI builds and deployments
- Coordinates with Security Liaison on production security requirements
- Partners with Release Manager and QA Lead on environment management

Success signals:
- Stable pipelines, fast build times, and high environment availability

---

### Support Lead / SRE Liaison
Summary:
Represents operational and support concerns, manages on-call routing and escalations after release.

Responsibilities:
- Triage incidents, maintain runbooks, and coordinate incident response
- Provide feedback to the team about production issues and patterns
- Own communication to customer-facing teams during incidents

Interactions:
- Works with PM/PdM to prioritize bug fixes and post-incident action items
- Partners with DevOps and Release Manager on incident mitigation and rollbacks

Success signals:
- Short mean time to detect and resolve incidents; clear post-incident actions

---

### Data Analyst
Summary:
Provides analysis and instrumentation guidance to measure feature impact and product metrics.

Responsibilities:
- Define tracking requirements and success metrics
- Build dashboards and analyze experiment/feature results
- Support Product Managers with data-driven recommendations

Interactions:
- Works with PdM/PM to set success metrics and measurement plans
- Coordinates with Developers and DevOps for event instrumentation

Success signals:
- Reliable telemetry for feature metrics and actionable insights that guide decisions

---

### Security Liaison
Summary:
Represents security and compliance requirements across features and releases.

Responsibilities:
- Review designs for security risks and compliance impacts
- Define security acceptance criteria and required scans
- Assist in incident response for security issues

Interactions:
- Works with Developers, DevOps, and PM to embed security checks in the lifecycle
- Escalates to the Security team for complex issues

Success signals:
- Minimal security issues in production and timely remediation for vulnerabilities

---

## How to use these entries
- Each new persona entry should include:
  - Summary
  - Responsibilities (concise bullet list)
  - Typical interactions with existing roles
  - Success signals (how to know the role is having impact)
- Add these as a new "Additional personas" section in the document (above). For large orgs/teams, consider creating per-project role assignments and a RACI matrix derived from these templates.
