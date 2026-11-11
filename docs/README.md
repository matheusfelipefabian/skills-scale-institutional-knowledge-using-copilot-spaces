# OctoAcme Project Management Docs

A central index to OctoAcme's project management guidance. These documents describe how teams initiate, plan, deliver, release, and improve cross-functional projects.

## Project Management Process Summary

OctoAcme manages work through an iterative lifecycle: initiate projects by validating the business need, aligning stakeholders, and defining measurable success; plan approved work into prioritized, estimated increments with acceptance criteria, milestones, and documented risks and dependencies; execute through a project board, regular team and stakeholder communication, small reviewed pull requests, automated checks, and ongoing quality tracking; release with readiness checks, smoke tests, stakeholder announcements, and rollback plans; then close the loop through retrospectives that turn lessons into owned, trackable improvements. Risks and blockers are monitored and escalated through the defined team, PM, Product Lead, and sponsor paths.

The Project Manager (PM) coordinates delivery, schedules, risks, and communications. The Product Manager (PdM) defines outcomes, priorities, and success measures; developers build and test increments; QA validates quality and acceptance criteria; and stakeholders provide input and approvals. The team tracks work on a project board from Backlog through Ready, In Progress, In Review, QA, and Done, using clear ownership and a documented Definition of Done.

Communication is designed to keep delivery and stakeholders aligned: PM and PdM meet weekly, delivery-team standups and syncs surface progress, blockers, dependencies, and risks, and stakeholders receive regular updates. A shared source of truth supports status reporting. Risks are recorded with impact, likelihood, owner, mitigation, and status; blockers escalate from the team to the PM, Product Lead, and sponsor as appropriate.

Quality is integrated throughout delivery and release. New logic should have unit tests, integration tests are added where applicable, and critical flows receive end-to-end smoke tests before release. CI runs automated tests and linting, security scanning is included, and manual QA is used when needed to confirm acceptance. Releases require acceptance criteria and checks to pass, release notes, smoke tests, and a rollback or mitigation plan, followed by post-deployment verification. Retrospectives after sprints, releases, milestones, or incidents produce a small set of owned, trackable improvements.

## Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
