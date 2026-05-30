# OctoAcme Role Interaction Matrix

## Purpose
This matrix clarifies how different roles interact, collaborate, and hand off work during project delivery. It helps teams understand dependencies, communication points, and decision-making ownership.

---

## Role Interaction Map

### Planning & Requirements Phase

| From → To | Developer | Product Manager | Project Manager | Scrum Master | UX Designer | Business Analyst | System Architect |
|-----------|-----------|-----------------|-----------------|--------------|-------------|------------------|------------------|
| **Developer** | Code review | Clarify acceptance criteria | Report blockers | Report blockers | Implement designs, ask feasibility questions | Clarify specs | Ask feasibility & scalability |
| **Product Manager** | Assign work, define AC | Align roadmap | Prioritize backlog, set milestones | Inform of priority changes | Share product vision, user needs | Validate business needs | Validate technical feasibility |
| **Project Manager** | Manage capacity, remove blockers | Align on timelines, risks | Coordinate across teams | Escalate impediments | Schedule design reviews | Validate scope | Advise on timelines |
| **Scrum Master** | Facilitate standups, remove blockers | Ensure backlog clarity | Escalate team risks | Facilitate ceremonies | Review design readiness | Clarify requirement clarity | Validate architecture readiness |
| **UX Designer** | Deliver specs, iterate on feedback | Validate designs align with product | Share design timelines | Include in sprint planning | Conduct research, iterate | Validate user needs | Advise on technical constraints |
| **Business Analyst** | Validate implementation | Ensure requirements align | Provide scope clarity | Clarify requirements in standup | Support user testing | Refine business requirements | Validate technical approach |
| **System Architect** | Advise on design, mentor | Advise on technical feasibility | Advise on complexity & timelines | Identify technical impediments | Share technical constraints | Validate technical feasibility | Review major decisions |

---

## Key Handoff Points by Phase

### Phase 1: Initiation
- **Product Manager** → **Business Analyst**: Business requirements and problem statement
- **Business Analyst** → **Project Manager**: Scope summary and resource needs
- **Project Manager** → **Scrum Master**: Project timeline and delivery approach

### Phase 2: Planning
- **Product Manager** → **UX Designer**: Product vision and user personas
- **Business Analyst** → **Developers & System Architect**: Detailed specifications and requirements
- **System Architect** → **Project Manager**: Technical complexity assessment and timeline impact
- **Project Manager** → **Scrum Master**: Sprint planning, team capacity, and milestones

### Phase 3: Execution
- **UX Designer** → **Developers**: Design specs, wireframes, and component documentation
- **Developers** → **Scrum Master**: Daily blockers and progress updates
- **Scrum Master** → **Project Manager**: Team impediments and velocity trends
- **Business Analyst** → **QA**: Test scenarios and acceptance criteria validation

### Phase 4: Release & Validation
- **Developers** → **Business Analyst/QA**: Code ready for testing
- **UX Designer** → **Product Manager**: User testing insights
- **System Architect** → **Project Manager**: Release readiness and rollback procedures
- **Project Manager** → **Stakeholders**: Release readiness and communications

### Phase 5: Retrospective & Improvement
- **Scrum Master** → **All Roles**: Facilitates retrospective discussion
- **All Roles** → **Project Manager**: Process improvement action items
- **Project Manager** → **Product Manager**: Lessons learned and backlog updates

---

## Communication Frequency by Role Pair

| Role Pair | Frequency | Format |
|-----------|-----------|--------|
| Developer ↔ Scrum Master | Daily | Standup + ad-hoc |
| Developer ↔ UX Designer | 2-3x per week | Design review, feedback loops |
| Developer ↔ System Architect | Weekly + as-needed | Design review, office hours |
| Product Manager ↔ Project Manager | Weekly | Sync meeting |
| Project Manager ↔ Scrum Master | Weekly + daily blockers | Sync + standup |
| Business Analyst ↔ Product Manager | Weekly | Backlog refinement |
| Business Analyst ↔ QA/Testing | Per sprint | Test planning, UAT |
| System Architect ↔ Product Manager | Bi-weekly | Technical feasibility reviews |

---

## Decision-Making Authority by Domain

| Domain | Owner | Advisor | Approver |
|--------|-------|---------|----------|
| **Product Prioritization** | Product Manager | Business Analyst, Developers | Sponsor |
| **Technical Design** | System Architect | Developers, Project Manager | CTO (if applicable) |
| **User Experience** | UX Designer | Product Manager, Developers | Product Manager |
| **Project Schedule** | Project Manager | Scrum Master, System Architect, Developers | Sponsor |
| **Requirements Clarity** | Business Analyst | Product Manager, Developers | Product Manager |
| **Team Capacity & Burndown** | Scrum Master | Project Manager, Developers | Project Manager |
| **Release Readiness** | System Architect | QA, Developers, Product Manager | Release Manager |

---

## How to Use This Matrix

1. **Identify your role** and trace interactions with other roles
2. **Plan handoffs** by checking the "Key Handoff Points" section
3. **Clarify communication frequency** using the Communication Frequency table
4. **Resolve decision conflicts** by referring to the Decision-Making Authority section
5. **Onboard new team members** by walking them through their row in the interaction map
