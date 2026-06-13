# OctoAcme Project Management Docs

This README provides a concise overview of OctoAcme’s project management processes and direct links to the detailed process documents stored in this docs/ folder. It is intended as a single-entry index to help new contributors and teams find the right guidance quickly.

OctoAcme follows a lightweight, iterative approach that starts with a Project One-pager to capture the problem, objective, measurable success criteria, stakeholders, and a high-level timeline. Approved initiatives move into planning where the team runs a kickoff, creates a prioritized backlog with acceptance criteria, estimates scope (T-shirt sizing or story points), and documents a Definition of Done. Core artifacts include the Project One-pager, roadmap/milestones, backlog with acceptance criteria, and a maintained risk register.

Execution emphasizes small, testable increments and predictable delivery. The team uses a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a PR workflow that encourages small changes, links to issues and acceptance criteria, and requires CI checks and at least one approval before merging. Regular ceremonies — daily standups, weekly delivery syncs, sprint demos, and retrospectives — surface progress, blockers, and action items. Escalation paths are defined so issues are raised to the appropriate level (team, PM, product lead, sponsor) when needed.

Quality assurance and release practices are integrated into the pipeline. Developers add unit and integration tests, CI runs automated tests and security scans, and critical flows have smoke tests before release. Manual QA is used where appropriate to validate acceptance criteria. Releases follow a checklist (release notes, rollback plan, staging verification, production smoke tests) and incidents trigger a blameless post-incident retrospective with captured action items.

## Process documents
- Project Management Overview — docs/octoacme-project-management-overview.md  
- Project Initiation Guide — docs/octoacme-project-initiation.md  
- Project Planning — docs/octoacme-project-planning.md  
- Execution & Tracking — docs/octoacme-execution-and-tracking.md  
- Risks & Communication — docs/octoacme-risks-and-communication.md  
- Release & Deployment — docs/octoacme-release-and-deployment.md  
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md  
- Roles & Personas — docs/octoacme-roles-and-personas.md

## How to use
1. Start with the Project Management Overview for a concise introduction.  
2. Use the Project Initiation Guide and the One-pager template to scope new initiatives.  
3. Keep the Risk Register, acceptance criteria, and release checklists up to date in planning and execution.  
4. Propose updates via the repository’s "Add Content to Project Management Process Docs" issue template when you want changes or new content added.

## Contributing
If you have updates or additions, open an issue using the "Add Content to Project Management Process Docs" template (see .github/ISSUE_TEMPLATE/) and include the suggested content and rationale so it can be reviewed and merged.
