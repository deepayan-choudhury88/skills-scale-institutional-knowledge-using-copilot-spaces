# OctoAcme Roles & Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Each persona brings unique expertise and perspective to ensure projects are well-planned, customer-focused, and successfully delivered.

## Role Overview

OctoAcme projects require clear ownership and cross-functional collaboration. The four primary personas work together throughout the project lifecycle:

- **Product Managers** shape *what* we build and *why*
- **Project Managers** coordinate *how* and *when* we deliver
- **Developers** implement the *technical solution*
- **QA/Testing** validates *quality* and *acceptance*

Each role has distinct responsibilities while maintaining shared accountability for project success.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards. Developers are responsible for technical excellence, code quality, and identifying risks early.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain unit tests, integration tests, and documentation
- Participate in design and code reviews
- Assist in estimating scope and planning work
- Help identify technical risks and propose mitigations
- Maintain CI/CD pipelines and automate quality checks
- Support production deployments and incident response

### Key Interactions
- **With Product Manager:** Clarify acceptance criteria, discuss trade-offs, validate technical approach
- **With Project Manager:** Provide status updates, flag blockers, adjust estimates as work progresses
- **With QA:** Ensure test coverage, work with QA to reproduce and fix issues
- **With Peer Developers:** Conduct code reviews, share knowledge, pair program when needed

### Goals
- Deliver reliable, maintainable code that meets acceptance criteria
- Reduce cycle time from idea to production
- Maintain high test coverage (target: >80%) and observability
- Build systems that scale and are resilient to failure
- Foster a culture of continuous improvement through learning and feedback

### Success Indicators
- Velocity is predictable and improving
- Code review cycle time is < 24 hours
- Defect rate is < 5% post-deployment
- Technical debt is actively managed
- Team members feel safe to take calculated risks and fail fast

### Typical Communication
- Daily standups (15 min) — progress, blockers, dependencies
- Sprint planning and retrospectives
- PR descriptions and code review comments
- Technical design docs for complex features
- Incident response and postmortems

---

## Product Managers

### Role Summary
Product Managers define *what* should be built to deliver customer and business value. They own the product vision, prioritize the backlog, measure outcomes, and advocate for customers. Product Managers balance stakeholder needs, market opportunities, and technical feasibility.

### Responsibilities
- Define problem statements, objectives (SMART goals), and success metrics
- Prioritize the roadmap and backlog based on impact and customer value
- Collaborate with stakeholders and engineering on trade-offs and feasibility
- Validate solutions through user research, data analysis, and customer feedback
- Create acceptance criteria and define "Definition of Done"
- Measure impact post-launch and iterate based on evidence

### Key Interactions
- **With Project Manager:** Align on scope, timeline, and release planning; provide context and priorities
- **With Developers:** Discuss feasibility, clarify requirements, validate technical approach
- **With Stakeholders:** Gather feedback, communicate roadmap, manage expectations
- **With Customers/Users:** Conduct research, gather feedback, validate assumptions

### Goals
- Maximize customer value and business impact
- Make clear, data-driven prioritization decisions using evidence
- Ensure product-market fit and exceptional usability
- Build products that delight customers and meet their needs
- Establish strong feedback loops to inform continuous iteration

### Success Indicators
- Success metrics are clearly defined and tracked for each release
- Feature adoption meets or exceeds targets
- Customer satisfaction scores are trending upward
- Time-to-value is minimized
- Team confidence in prioritization decisions is high

### Typical Communication
- Weekly alignment with Project Manager and engineering leads
- Roadmap reviews and stakeholder briefings
- Acceptance criteria and feature specifications
- Post-launch review meetings and metrics analysis
- Customer feedback sessions and user research

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently while maintaining transparency and psychological safety. Project Managers are the "quarterbacks" of projects, ensuring alignment across stakeholders and removing blockers.

### Responsibilities
- Create and maintain project plans, timelines, and milestone definitions
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, daily standups, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Escalate blockers and risks appropriately
- Track progress against plans and adjust as needed
- Organize retrospectives and capture action items

### Key Interactions
- **With Product Manager:** Confirm scope and priorities, coordinate roadmap updates
- **With Developers:** Understand technical progress, identify and resolve blockers, celebrate wins
- **With Stakeholders:** Provide regular status updates, manage expectations, escalate issues
- **With Sponsors:** Communicate business impact, resource needs, and critical decisions

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work, scope creep, and escalations
- Maintain transparency and alignment across all stakeholders
- Build trust through consistent, honest communication
- Foster psychological safety and continuous improvement

### Success Indicators
- Projects deliver on or ahead of schedule
- Scope changes are managed through formal processes
- Risk register is actively maintained and reviewed weekly
- Stakeholder satisfaction is high
- Team morale and engagement are positive
- Action items from retrospectives are completed or actively tracked

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Project board updates and milestone tracking
- Coordination via project boards, meetings, and asynchronous updates
- Escalation paths for blockers and critical issues

---

## QA/Testing

### Role Summary
QA and testing professionals validate that solutions meet acceptance criteria and quality standards before deployment. They partner with developers to design and execute test strategies, identify defects, and ensure reliable, performant releases.

### Responsibilities
- Create and maintain test plans aligned with acceptance criteria
- Design test cases and execute manual and automated testing
- Identify and document defects with clear reproduction steps
- Validate acceptance criteria are met before marking work as complete
- Perform end-to-end and smoke testing before releases
- Advocate for quality and raise concerns about risk
- Support production issues and post-deployment verification

### Key Interactions
- **With Product Manager:** Clarify acceptance criteria, validate feature behavior
- **With Developers:** Collaborate on test coverage, debug issues, optimize test efficiency
- **With Project Manager:** Report quality metrics, communicate blockers
- **With Users/Stakeholders:** Gather feedback on usability and behavior

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce post-launch defects and production incidents
- Maintain fast feedback loops to developers
- Build confidence in releases through comprehensive testing
- Continuously improve test coverage and automation

### Success Indicators
- Defect escape rate (bugs found post-launch) is < 5%
- Test coverage for critical paths is > 90%
- Testing cycle time is predictable and efficient
- Automated tests provide quick feedback (< 30 min)
- Team confidence in release quality is high

### Typical Communication
- Test plan reviews and acceptance criteria walkthroughs
- Daily standup updates on test progress
- Defect reports and severity assessment
- Pre-release quality gates and sign-off
- Post-launch verification and incident support

---

## Role Interactions & Collaboration Model

### Project Initiation
- **Product Manager** defines problem statement and success metrics
- **Project Manager** gathers requirements and creates high-level plan
- **Developers** assess technical feasibility and highlight risks
- **QA** outlines testing strategy and resource needs

### Project Planning
- **Product Manager** prioritizes backlog and defines acceptance criteria
- **Project Manager** creates detailed timeline and identifies dependencies
- **Developers** estimate work and refine technical approach
- **QA** designs test plan and validates acceptance criteria clarity

### Execution
- **Developers** implement features and write tests
- **QA** validates work meets acceptance criteria
- **Project Manager** tracks progress, manages risks, and escalates blockers
- **Product Manager** provides context, answers questions, validates approach

### Release & Deployment
- **Developers** prepare release notes and rollback procedures
- **QA** performs smoke tests and validates production behavior
- **Project Manager** coordinates deployment window and stakeholder communication
- **Product Manager** announces release and monitors user adoption

### Retrospective
- **Project Manager** facilitates discussion and captures action items
- All roles contribute insights on what went well and what could improve
- **Developers** highlight technical learnings and improvements
- **QA** shares insights on quality and testing effectiveness
- **Product Manager** captures customer feedback and lessons learned

---

## How to Use These Personas in OctoAcme

### For Project Planning
Use these personas to:
- Identify the right people for each role on your project
- Clarify role responsibilities and prevent gaps
- Understand communication needs and cadence
- Set expectations for what each role will contribute

### For Copilot Spaces
Use persona prompts to get role-specific guidance:
- "As a Developer, what should I include in my PR description?"
- "As a Product Manager, how do I define success metrics?"
- "As a Project Manager, what risks should I watch for?"

### For Team Onboarding
Use this document to help new team members understand:
- Their role and how it contributes to project success
- Who they need to collaborate with and how
- What success looks like in their role
- Communication expectations and cadence

### For Retrospectives
Reference these personas when discussing:
- What collaboration worked well
- Where communication broke down
- How to strengthen cross-functional teamwork
- Role-specific improvements and learnings

---

## Adapting Roles to Team Size

**Small teams (3-5 people):**
- One person may hold multiple roles (e.g., PM + QA)
- Simplify communication cadence
- Focus on core responsibilities for each role
- Use pair programming and shared code review responsibility

**Medium teams (6-10 people):**
- Each role typically has one dedicated person
- Establish clear communication protocols
- Create role-specific checklists and templates
- Consider tech leads or senior developers for mentoring

**Large teams (10+ people):**
- Multiple people per role with specialization
- Establish role leads and working groups
- Create detailed communication and escalation protocols
- Invest in tools and automation (CI/CD, project boards, etc.)

---

**Questions about roles?** Reference the [Project Management Overview](./octoacme-project-management-overview.md) for how these roles fit into the overall project lifecycle, or [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation paths.
