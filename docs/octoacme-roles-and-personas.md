# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers
[... existing content ...]

## Engineering Lead

### Role Summary
The Engineering Lead is the technical owner for the engineering delivery of a project or large feature area. They provide architectural guidance, mentor engineers, and make critical technical trade-off decisions.

### Responsibilities
- Own and validate the technical architecture and design approach
- Mentor and support Developers on complex technical challenges
- Make or facilitate major technical trade-off decisions
- Coordinate cross-team technical dependencies and integration points
- Identify and escalate technical risks and blockers
- Conduct technical design reviews and code quality oversight

### Goals
- Ensure architectural consistency and maintainability
- Reduce technical debt and mitigate engineering risks
- Foster a culture of quality and continuous improvement
- Enable team velocity through clear technical direction

### Interactions
- **With PM/PdM**: Aligns scope and timeline; provides technical feasibility input on requirements
- **With Developers**: Partners on implementation details; provides design guidance and mentorship
- **With QA**: Informs of integration points and testing strategies
- **With Product Lead**: Escalates technical risks and major architectural decisions

### Typical Communication
- Technical design docs and architecture reviews
- Weekly sync with PM on technical blockers
- Code review comments and technical guidance
- Escalation of architectural risks to Product Lead

---

## Design Lead

### Role Summary
The Design Lead owns all UX and design decisions for the project. They validate usability, ensure accessibility standards, and maintain consistency with the design system.

### Responsibilities
- Create and deliver design specifications and wireframes
- Conduct usability research and validate design solutions
- Ensure accessibility compliance (WCAG, etc.)
- Maintain consistency with established design system and patterns
- Participate in design reviews and acceptance criteria definition
- Hand off designs to Developers with clear specifications

### Goals
- Deliver user-centric, intuitive interfaces
- Maintain design system consistency across products
- Reduce rework and ensure designs are implementable
- Build user empathy across the team

### Interactions
- **With Product Manager**: Collaborates on user goals, success criteria, and use cases
- **With Developers**: Provides design specs; participates in design-to-implementation reviews
- **With QA**: Validates that implementations match design intent
- **With Stakeholders**: Presents design decisions and rationale

### Typical Communication
- Design specs, wireframes, and prototypes
- Design review meetings
- Acceptance criteria related to UX/UI
- User research findings and validation results

---

## Release Manager

### Role Summary
The Release Manager coordinates all release activities and ensures deployments follow established checklists and best practices. They own the release schedule and post-deployment verification.

### Responsibilities
- Plan and schedule release windows (coordinating with Ops and on-call teams)
- Verify pre-release checklist (all acceptance criteria met, tests passing, rollback plan ready, release notes complete)
- Coordinate with Ops/SRE for deployment execution
- Run post-deployment verification and smoke tests
- Monitor for issues and coordinate rollback if necessary
- Communicate release status to stakeholders and support teams
- Document release outcomes and lessons learned

### Goals
- Execute zero-defect releases with minimal risk
- Reduce time-to-production and deployment cycle time
- Maintain system stability and user trust
- Enable rapid iteration with confidence

### Interactions
- **With PM/Engineering Lead**: Coordinates release window and verifies readiness
- **With Developers**: Ensures all PRs are merged and tests passing
- **With Ops/SRE**: Executes deployment; coordinates rollback if needed
- **With Stakeholders**: Announces releases and communicates status
- **With Support**: Ensures they are prepared for new features and known issues

### Typical Communication
- Release checklists and deployment logs
- Pre-release readiness reviews
- Release notes and announcement communications
- Post-incident retrospectives and remediation tracking

---

## Program Manager

### Role Summary
The Program Manager coordinates across multiple related projects to manage dependencies, roadmap alignment, and resource constraints. They maintain visibility into program-level risks and milestones.

### Responsibilities
- Track cross-project milestones and dependencies
- Resolve resource conflicts and prioritize work across projects
- Synthesize stakeholder updates and provide program-level status
- Maintain program-level risk register and escalation paths
- Facilitate alignment meetings between project teams
- Identify and communicate program-level impacts and trade-offs

### Goals
- Deliver program outcomes on time and within scope
- Minimize cross-project conflicts and delays
- Maintain stakeholder confidence through transparency
- Enable efficient resource utilization across projects

### Interactions
- **With Project Managers**: Aligns timelines and resolves dependencies
- **With Product Leads**: Collaborates on roadmap prioritization
- **With Sponsors**: Escalates unresolved blockers and program-level risks
- **With Stakeholders**: Provides program-level status and trade-off communication

### Typical Communication
- Program roadmap and milestone tracking
- Cross-project dependency logs
- Program-level risk registers and escalations
- Stakeholder briefings and status reports

---

## Security Liaison

### Role Summary
The Security Liaison is the primary contact for security reviews, vulnerability triage, and incident coordination within the project. They ensure security best practices are embedded in the development process.

### Responsibilities
- Conduct threat modeling for significant changes or new features
- Coordinate security reviews and ensure findings are addressed
- Triage security vulnerabilities and prioritize remediation
- Coordinate with Security team on incidents affecting the project
- Ensure security scanning and SAST tools are configured and passing
- Advise the team on security best practices and compliance requirements

### Goals
- Reduce security risk and vulnerabilities in production
- Ensure compliance with security policies and standards
- Build security awareness across the delivery team
- Enable secure-by-default development practices

### Interactions
- **With Developers**: Advises on secure coding; coordinates remediation of findings
- **With PM**: Informs of security-related scope changes or timeline impacts
- **With Security On-call**: Escalates critical vulnerabilities and incidents
- **With QA**: Coordinates security testing and validation

### Typical Communication
- Threat models and security design reviews
- Vulnerability triage and remediation tracking
- Security incident coordination and post-mortems
- Compliance and policy guidance

---

## Data Analyst

### Role Summary
The Data Analyst owns the measurement plan and success metrics instrumentation for the project. They analyze outcomes against success criteria and provide data-driven insights to inform decisions.

### Responsibilities
- Define measurement plan and success metrics with Product Manager
- Implement and validate metric collection and dashboards
- Analyze project outcomes against defined success criteria
- Provide data-driven insights to support decision-making
- Create dashboards and reports for stakeholders and the team
- Identify trends, anomalies, and opportunities for optimization

### Goals
- Ensure the project is delivering on defined success metrics
- Provide transparency into project impact and outcomes
- Enable data-driven decisions and continuous improvement
- Reduce guesswork through rigorous measurement and analysis

### Interactions
- **With Product Manager**: Partners on success metrics definition; provides outcome analysis
- **With PM**: Delivers dashboards and status metrics for stakeholder reporting
- **With Developers**: Advises on instrumentation and logging requirements
- **With Stakeholders**: Presents data findings and impact analysis

### Typical Communication
- Measurement plans and success criteria documentation
- Dashboards and regular metric reports
- Data analysis and outcome presentations
- Recommendations for optimization based on data

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
