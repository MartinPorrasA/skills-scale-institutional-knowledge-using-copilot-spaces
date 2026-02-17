# OctoAcme RACI Matrix

## Purpose
This RACI matrix clarifies roles and responsibilities for key project lifecycle activities. It defines who is **Responsible** (does the work), **Accountable** (ultimately answerable), **Consulted** (provides input), and **Informed** (kept updated) for each activity.

---

## RACI Key

- **R - Responsible**: The person(s) who perform the work to complete the task
- **A - Accountable**: The person ultimately answerable for the correct and thorough completion of the task (only one A per activity)
- **C - Consulted**: People whose opinions are sought; two-way communication
- **I - Informed**: People who are kept up-to-date on progress; one-way communication

**Note:** Each activity should have exactly one Accountable person, but may have multiple Responsible, Consulted, or Informed roles.

---

## Project Initiation Phase

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Define business need and objectives | C | R | A | C | I | I | C | I | I |
| Create project charter | R | C | A | C | I | I | I | I | I |
| Identify stakeholders | R | C | A | I | I | I | R | I | I |
| Define success metrics | C | R | A | I | C | I | I | I | I |
| Conduct feasibility assessment | C | C | A | R | I | I | I | C | R |
| Secure project funding | I | I | A | I | I | I | I | I | I |
| Assign project team | A | I | C | I | I | I | I | I | I |

---

## Project Planning Phase

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Create project plan and timeline | A | C | C | R | C | I | I | I | C |
| Define scope and requirements | C | A | C | C | R | I | I | C | C |
| Develop work breakdown structure | R | C | I | A | I | I | I | I | C |
| Estimate effort and resources | C | I | I | A | C | I | I | C | R |
| Create communication plan | C | I | I | I | I | I | A | I | I |
| Identify and assess risks | A | C | I | R | R | C | I | C | C |
| Define quality standards | C | C | I | C | A | I | I | C | C |
| Establish data governance plan | C | I | I | C | C | I | I | A | C |
| Define change management process | C | I | I | I | I | A | I | I | I |
| Baseline project scope/schedule | A | C | C | C | I | R | I | I | I |

---

## Design Phase

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Create architecture design | I | C | I | A | C | I | I | C | R |
| Define data model and schemas | I | I | I | C | I | I | I | A | R |
| Design user interfaces | C | A | I | C | C | I | I | I | R |
| Define API contracts | I | C | I | A | I | I | I | I | R |
| Conduct design reviews | C | C | I | A | R | I | I | C | R |
| Complete security threat modeling | C | I | I | R | C | I | I | C | C |
| Create test strategy | C | C | I | C | A | I | I | I | C |

---

## Development Phase

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Implement features | I | I | I | A | I | I | I | I | R |
| Write unit tests | I | I | I | C | C | I | I | I | A/R |
| Conduct code reviews | I | I | I | R | I | I | I | I | A |
| Implement data validation | I | I | I | C | I | I | I | R | A |
| Track development progress | R | I | I | A | I | I | I | I | C |
| Manage technical debt | C | C | I | A | C | I | I | I | R |
| Document code and APIs | I | I | I | C | I | I | I | I | A/R |

---

## Testing Phase

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Create test cases | I | C | I | C | A | I | I | C | C |
| Execute integration tests | I | I | I | C | A | I | I | I | R |
| Conduct performance testing | C | I | I | C | A | I | I | I | R |
| Perform security testing | C | I | I | C | A | I | I | C | R |
| Validate data quality | C | I | I | C | R | I | I | A | C |
| Track and triage defects | C | C | I | C | A | I | I | C | R |
| Approve test results | C | C | I | C | A | I | I | I | I |
| Conduct UAT | C | A | C | C | R | I | I | I | I |

---

## Change Management

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Submit change request | I | C | I | C | C | I | I | I | C |
| Assess change impact | C | C | I | R | R | A | I | C | R |
| Review change request | C | C | C | C | C | A | I | C | I |
| Approve/reject change | A | C | C | C | C | R | I | I | I |
| Communicate approved changes | C | I | I | I | I | R | A | I | I |
| Implement approved change | C | I | I | A | I | I | I | I | R |
| Validate change implementation | C | C | I | C | R | R | I | C | I |

---

## Communication Activities

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Develop communication plan | C | I | I | I | I | C | A | I | I |
| Create stakeholder updates | R | C | I | I | I | C | A | I | I |
| Conduct status meetings | A | C | C | R | C | C | C | C | I |
| Manage project communications | C | I | I | I | I | C | A | I | I |
| Handle stakeholder escalations | A | C | C | C | I | I | C | I | I |
| Prepare executive briefings | R | C | I | I | I | I | A | I | I |

---

## Release & Deployment

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Create deployment plan | C | I | I | A | C | I | I | C | R |
| Conduct release readiness review | A | C | C | R | R | I | I | C | C |
| Approve production release | A | C | C | C | R | R | I | I | I |
| Execute deployment | I | I | I | A | C | I | I | I | R |
| Validate production deployment | C | C | I | R | A | I | I | C | R |
| Communicate go-live | C | I | I | I | I | C | A | I | I |
| Monitor post-deployment | C | C | I | A | R | I | I | C | R |
| Execute rollback (if needed) | C | I | C | A | C | I | I | I | R |

---

## Data Governance Activities

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Define data quality standards | C | I | I | C | R | I | I | A | C |
| Implement data access controls | I | I | I | C | I | I | I | A | R |
| Monitor data quality | C | I | I | C | R | I | I | A | I |
| Conduct data quality audits | C | I | I | I | C | I | I | A | I |
| Manage data compliance | C | I | C | I | I | I | I | A | I |
| Handle data privacy requests | I | I | I | I | I | I | I | A | I |
| Maintain data documentation | I | I | I | C | I | I | I | A | C |

---

## Quality Assurance Activities

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Define quality criteria | C | R | I | C | A | I | I | I | C |
| Review quality gate requirements | C | C | I | C | A | I | I | C | C |
| Conduct quality reviews | C | C | I | R | A | I | I | I | R |
| Approve quality gate passage | C | C | I | C | A | I | I | I | I |
| Report quality metrics | C | I | I | I | A | I | I | I | I |
| Recommend go/no-go decision | C | C | C | C | A | I | I | I | I |

---

## Project Closure

| Activity | Project Manager | Product Manager | Sponsor | Execution Lead | QA Lead | Change Manager | Communications Lead | Data Steward | Developers |
|----------|----------------|-----------------|---------|----------------|---------|----------------|---------------------|--------------|-----------|
| Conduct retrospective | A | R | I | R | R | R | R | R | R |
| Document lessons learned | R | C | I | C | C | C | C | C | C |
| Archive project artifacts | A | I | I | I | I | I | I | I | I |
| Release project resources | A | I | C | I | I | I | I | I | I |
| Conduct handoff to operations | C | C | I | A | C | I | I | C | R |
| Create final project report | A | C | C | I | I | I | C | I | I |
| Obtain project sign-off | R | I | A | I | I | I | I | I | I |

---

## How to Use This Matrix

1. **Clarify Roles:** Use this matrix to understand who does what for each project activity
2. **Avoid Confusion:** When unclear about ownership, reference this matrix
3. **Onboard New Members:** Share this matrix with new team members to quickly orient them
4. **Resolve Conflicts:** When role conflicts arise, use this as the source of truth (escalate to PM if needed)
5. **Adapt as Needed:** Small projects may combine roles; large projects may add specialized roles

---

## Customization Notes

- **Small Projects:** Project Manager may assume Change Manager responsibilities
- **Large Programs:** Add Program Manager role as Accountable for multi-project coordination
- **Specialized Projects:** Add Security Lead, Compliance Officer, or other specialists as needed
- **External Teams:** Add Vendor Manager or Third-Party Coordinator roles when working with external partners

---

## Related Documents

- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) - Detailed role descriptions
- [Project Management Overview](octoacme-project-management-overview.md) - High-level framework
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)

---

**Last Updated:** 2026-02-17  
**Maintained By:** OctoAcme Project Management Team
