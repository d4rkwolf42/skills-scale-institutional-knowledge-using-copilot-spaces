
# OctoAcme — Roles Overview & Interaction Matrix

## Purpose
Provide a quick reference for understanding role boundaries, key responsibilities, and how roles interact across the project lifecycle.

## Role Interaction Matrix

| Activity | Project Manager | Product Manager | Scrum Master | Developer | QA Lead | UX Designer | Release Manager | Business Analyst |
|----------|-----------------|-----------------|--------------|-----------|---------|-------------|-----------------|-----------------|
| **Define Requirements** | Supports | Owns | Facilitates | Advises | Defines test criteria | Defines UX specs | N/A | Owns |
| **Plan & Estimate** | Owns | Advises | Facilitates | Participates | Advises on test scope | Advises on design effort | N/A | Advises |
| **Design & Architecture** | Supports | Advises | N/A | Owns | Defines quality standards | Owns UX design | N/A | Documents requirements |
| **Development** | Tracks | N/A | Facilitates | Owns | Advises on testability | N/A | N/A | Clarifies requirements |
| **Testing & QA** | Tracks | N/A | Facilitates | Participates | Owns | Validates UX acceptance | Coordinates sign-off | N/A |
| **Release Planning** | Owns | Advises | N/A | Participates | Signs off | N/A | Owns | N/A |
| **Deployment** | Coordinates | N/A | N/A | Supports | Signs off | N/A | Owns | N/A |
| **Post-Deployment** | Reports | Measures | N/A | Monitors | Monitors | Gathers user feedback | Verifies success | N/A |

## Key Responsibility Zones (Ownership Model)

- **Owns:** Primary decision-maker and accountable party
- **Advises:** Provides input and recommendations
- **Participates:** Actively involved in execution
- **Facilitates:** Enables others to participate and collaborate
- **Supports:** Provides resources or information as needed
- **Tracks:** Monitors progress and flags issues
- **N/A:** Not typically involved

## Common Responsibility Handoffs

### Initiation → Planning
- **Product Manager** hands off: prioritized vision, business case, success metrics
- **Business Analyst** hands off: validated requirements and stakeholder alignment
- **Project Manager** receives and creates detailed project plan

### Planning → Execution
- **Project Manager** hands off: project plan, dependencies, timeline
- **Scrum Master** ensures: team understands sprint goals and acceptance criteria
- **Developers** begin: building and testing

### Execution → Release
- **QA Lead** conducts: final quality verification and sign-off
- **Release Manager** prepares: release plan, deployment checklist, rollback procedure
- **Project Manager** coordinates: stakeholder communication

### Release → Close
- **Release Manager** hands off: deployment verification and metrics
- **Project Manager** schedules: retrospective and captures lessons learned
- **Team** participates: reflects on what went well and what to improve

## Role Staffing Model

### Minimum Team
- Project Manager
- Product Manager
- Developers (at least 2)
- QA/Testing (can be combined with Developer role initially)

### Growing Teams (add roles in this order)
1. Business Analyst (support complex requirements and stakeholder management)
2. QA Lead (dedicated testing and quality coordination)
3. UX Designer (dedicated design and user research)
4. Scrum Master (for larger teams or complex ceremonies)
5. Release Manager (for frequent or complex releases)

## When Roles Overlap or Combine

In smaller teams, roles may be combined:
- **Developer + QA:** One person handles coding and testing (not ideal for quality)
- **PM + Scrum Master:** Project coordination and agile facilitation by one person
- **Business Analyst + Product Manager:** Requirements gathering and prioritization combined
- **Release Manager duties:** Often handled by Project Manager or DevOps engineer

*Note:* Monitor for signs of overload or gaps when combining roles, and plan to split them as the team grows.

## Escalation Path & Accountability
