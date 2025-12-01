# Role-Responsibility Matrix Template

## Purpose
Define clear accountability and responsibility for project activities using a RACI (Responsible, Accountable, Consulted, Informed) model.

## When to use
Use this template at project kickoff to clarify who does what, prevent gaps or overlaps, and ensure efficient collaboration.

## RACI Key
- **R** = Responsible: Does the work to complete the task
- **A** = Accountable: Ultimately answerable for the task's completion (only one A per activity)
- **C** = Consulted: Provides input and expertise before decisions are made
- **I** = Informed: Kept updated on progress or decisions

## Template

| Activity / Deliverable | Developer | Product Manager | Project Manager | Portfolio Manager | Change Manager | QA Lead | Stakeholder Liaison | Executive Sponsor |
|------------------------|-----------|-----------------|-----------------|-------------------|----------------|---------|---------------------|-------------------|
| **Initiation Phase** |
| Define problem statement | C | R | C | C | | | C | A |
| Create project charter | C | C | R | I | | | C | A |
| Identify stakeholders | I | C | R | | | | A | C |
| Initial risk assessment | C | C | R | | C | | | I |
| **Planning Phase** |
| Define acceptance criteria | R | A | C | | | C | | I |
| Create project plan | C | C | R/A | I | | | | I |
| Resource allocation | I | C | C | R/A | | | | C |
| Release planning | R | R | A | I | | C | I | I |
| **Execution Phase** |
| Feature implementation | R/A | C | I | | | C | | |
| Code review | R | | | | | C | | |
| Test execution | C | C | I | | | R/A | | |
| Change implementation | C | C | C | | R/A | | C | I |
| Status reporting | | C | R/A | I | | | C | I |
| **Quality & Risk** |
| Quality gate reviews | C | C | C | | | R/A | | I |
| Risk identification | R | C | C | | C | | C | A |
| Risk mitigation planning | C | C | R | | C | | | A |
| **Release Phase** |
| Release readiness review | C | C | R | | C | C | | A |
| Deployment execution | R | I | C | | C | C | | I |
| Post-deployment validation | R | C | C | | | R/A | | I |
| Release communication | | C | C | | C | | R/A | I |
| **Close & Retrospective** |
| Retrospective facilitation | C | C | R/A | | | | C | I |
| Lessons learned documentation | C | C | R | I | | | | I |
| Project closure report | | C | R/A | I | | | C | C |

## How to customize this template
1. Add or remove roles based on your project team
2. Add specific activities relevant to your project
3. Review with the team to ensure clarity and agreement
4. Update throughout the project as roles or activities change
5. Store completed matrix in project documentation (repo or wiki)

## Tips for using the matrix effectively
- Keep it simple: not every task needs a full RACI breakdown
- Ensure each activity has exactly one Accountable (A) person
- Avoid too many Consulted (C) — it can slow decisions
- Review and update quarterly or when team composition changes
- Use in onboarding to help new team members understand their role

## Example Use Case
When starting a new feature initiative:
1. Copy this template into your project docs
2. Customize activities to match your feature scope
3. Review in kickoff meeting with all team members
4. Get consensus and commitment from each role
5. Reference the matrix when questions arise about ownership

---

**Related**: See [Roles and Personas](octoacme-roles-and-personas.md) for detailed role definitions.
