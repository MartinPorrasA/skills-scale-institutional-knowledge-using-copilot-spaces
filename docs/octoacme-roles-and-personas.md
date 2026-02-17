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

## Change Manager

### Role Summary
Change Managers oversee the change management process, ensuring that all proposed project adjustments are properly documented, evaluated for impact, approved, and communicated to stakeholders. They act as gatekeepers for scope and baseline changes.

### Responsibilities
- Review and triage incoming change requests
- Assess impact of proposed changes on schedule, budget, scope, and quality
- Coordinate Change Control Board (CCB) meetings and decision-making
- Document change decisions and maintain the change log
- Communicate approved changes to affected stakeholders
- Track implementation of approved changes
- Ensure change management process is followed consistently

### Key Outputs/Artifacts
- Change request forms (see [Change Request Template](templates/change-request-template.md))
- Change impact assessments
- Change log and decision records
- CCB meeting minutes
- Change notifications to stakeholders

### Interactions with Other Roles
- **Project Manager**: Partners closely to evaluate impact of changes on project baselines; escalates critical changes; coordinates CCB meetings
- **Sponsor**: Seeks approval for high-impact changes that affect budget or strategic scope
- **Execution Lead / Developers**: Collects technical impact assessments; coordinates implementation timing
- **Communications Lead**: Collaborates on messaging for significant changes
- **Product Manager**: Reviews changes that affect product vision or customer commitments

### Decision Rights (RACI)
- **Accountable** for: Change management process execution, change impact analysis
- **Responsible** for: Documenting changes, facilitating CCB decisions, tracking change implementation
- **Consulted** by: Project Manager (on scope/schedule impacts), Execution Teams (on technical feasibility)
- **Informs**: Stakeholders, Sponsor, Project Team of approved changes

---

## Communications Lead

### Role Summary
Communications Leads develop and execute communication strategies for projects, ensuring consistent, timely, and effective messaging to internal and external stakeholders throughout the project lifecycle.

### Responsibilities
- Create project communication plans (see [Communications Plan Template](templates/communications-plan-template.md))
- Define communication channels, frequency, and audience segmentation
- Develop key messages and talking points for project milestones
- Coordinate stakeholder updates and presentations
- Manage communication risks and issues
- Ensure brand and messaging consistency
- Support change management communications
- Monitor communication effectiveness and adjust as needed

### Key Outputs/Artifacts
- Communications plan and calendar
- Stakeholder communication matrix (audience, message, frequency, channel)
- Email updates, newsletters, and announcements
- Presentation decks for stakeholder briefings
- FAQ documents
- Communication effectiveness metrics

### Interactions with Other Roles
- **Project Manager**: Partners to align communication timing with project milestones; receives project status for stakeholder updates
- **Sponsor**: Coordinates executive communications and major announcements
- **Change Manager**: Collaborates on change notification messaging
- **Product Manager**: Aligns product messaging with project communications
- **Execution Lead**: Coordinates technical deep-dives and demos for stakeholder audiences

### Decision Rights (RACI)
- **Accountable** for: Communication strategy and plan execution, message consistency
- **Responsible** for: Creating and distributing communications, managing communication channels
- **Consulted** by: Project Manager (on stakeholder messaging), Change Manager (on change communications)
- **Informs**: All project stakeholders through coordinated communications

---

## Quality Assurance (QA) Lead

### Role Summary
QA Leads define quality standards, oversee testing and review phases, and ensure that all deliverables meet agreed-upon quality thresholds before release or client handoff.

### Responsibilities
- Define quality standards and acceptance criteria
- Create and maintain test plans and test cases
- Coordinate testing activities (functional, integration, performance, security)
- Review code quality metrics and test coverage
- Validate that deliverables meet quality gates (see [Quality Gates Checklist](checklists/quality-gates-checklist.md))
- Identify and track defects through resolution
- Report on quality metrics and testing progress
- Recommend go/no-go decisions for releases

### Key Outputs/Artifacts
- Quality assurance plan
- Test plans and test cases
- Test execution reports and metrics
- Defect logs and trend analysis
- Quality gate sign-offs
- Quality metrics dashboards

### Interactions with Other Roles
- **Project Manager**: Coordinates quality activities within project schedule; escalates quality risks
- **Execution Lead / Developers**: Defines quality standards; reviews code quality; coordinates defect resolution
- **Product Manager**: Validates that quality standards align with customer expectations
- **Release Manager**: Partners on release readiness assessment
- **Data Steward**: Collaborates on data quality standards and validation

### Decision Rights (RACI)
- **Accountable** for: Quality standards definition, testing strategy, quality gate validation
- **Responsible** for: Test execution, defect tracking, quality reporting
- **Consulted** by: Project Manager (on release readiness), Developers (on testing approach)
- **Informs**: Project Manager, Sponsor, Execution Team of quality status and risks

---

## Data Steward

### Role Summary
Data Stewards manage the integrity, security, accessibility, and usability of project data assets. They ensure compliance with data policies, support data-informed decision-making, and coordinate data governance activities.

### Responsibilities
- Define data quality standards and validation rules
- Ensure data security, privacy, and compliance with policies (GDPR, etc.)
- Manage data access controls and permissions
- Coordinate data integration and migration activities
- Monitor data quality metrics and remediate issues
- Document data lineage and metadata
- Support analytics and reporting needs
- Conduct data quality audits (see [Data Stewardship Checklist](checklists/data-stewardship-checklist.md))

### Key Outputs/Artifacts
- Data governance plan
- Data quality standards and metrics
- Data access control matrix
- Data validation rules and scripts
- Data quality reports and dashboards
- Data lineage documentation
- Data compliance audit reports

### Interactions with Other Roles
- **Project Manager**: Coordinates data-related activities and timelines; escalates data risks
- **Execution Lead / Developers**: Defines data standards; reviews data architecture; validates data quality
- **QA Lead**: Collaborates on data quality testing and validation
- **Sponsor**: Reports on data compliance and governance status
- **Product Manager**: Ensures data supports product analytics and decision-making needs

### Decision Rights (RACI)
- **Accountable** for: Data quality, data governance compliance, data security
- **Responsible** for: Data validation, data access management, data quality monitoring
- **Consulted** by: Developers (on data architecture), QA Lead (on data testing)
- **Informs**: Project Manager, Sponsor of data quality issues and compliance status

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For a comprehensive view of role interactions and decision-making responsibilities, see the [RACI Matrix](octoacme-raci-matrix.md).

