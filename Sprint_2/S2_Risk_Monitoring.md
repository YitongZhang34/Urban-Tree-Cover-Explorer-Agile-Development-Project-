# Project Risk Monitoring - Assignment 2

- Document your Risk Monitoring in Sprint 2 for Assignment 2.
- Project Risk Monitoring is a continuous activity and done throughout the project execution cycle (Sprints)  
- Refer to Risk_Monitoring_Guide_and_Example_and_Guide.md under the Guides folder for guidance on how to document this section. An example is shown.
- You can reuse formatting and sections from the guidance for documenting this section


# Sprint 2 Risk Monitoring – Urban Tree Explorer

## 1. Risk Monitoring Approach

| Scrum Ceremony         | Risk Monitoring Strategy |
|------------------------|-------------------------|
| **Sprint Planning**    | Identified risks related to map performance, server overload from large files, ambiguity in requirements, team motivation issues, and design misalignment. Discussed early mitigation strategies and fallback plans. |
| **Daily Stand-Ups**    | Monitored live server performance, logged issues, tracked team integration progress, and reassessed requirement alignment mid-sprint. |
| **Sprint Reviews**     | Verified that performance was restored and client expectations were met despite late requirement discoveries. |
| **Sprint Retrospective** | Identified the need for requirement confirmation checkpoints and clearer team alignment before mid-sprint. Planned better file management and spec-freeze practices. |

---

## 2. Risk Stories in Sprint 2 Backlog

### 🔸 Risk Story 1 – Technical Performance Risk 

**Risk:** The switch to a new map API and addition of category coloring caused server performance to degrade and eventually crash due to data overload.

**Risk Story:**  
_As a development team, we want to reduce map-related data load and remove redundant uploads so that the website remains responsive and doesn't crash after switching APIs or adding new filters._

**Acceptance Criteria:**
- Redundant datasets and oversized files are identified and deleted.
- The site loads within acceptable performance range (<2s delay) under typical filter use.
- Server no longer crashes when category coloring is active.

**Backlog Details:**
| Field          | Description |
|----------------|-------------|
| **Priority**   | High |
| **Estimation** | 5 Story Points |
| **Owner**      | @yixiang / @zixian |
| **Dependencies** | IT Services access to server file system; category coloring logic |
| **Notes**      | Solved by deleting large failed uploads and oversized maps. Future mitigation could include upload limits or file-size validation. |

---

### 🔸 Risk Story 2 – Stakeholder Requirement Ambiguity (DEF-006)

**Risk:** Unclear whether the client expected *exactly* 10 nearest trees or a flexible display.

**Risk Story:**  
_As a development team, we want to clarify display requirements with the client early so that we do not overbuild or misinterpret design expectations._

**Acceptance Criteria:**
- Client confirms display logic (e.g., fixed 10 items vs. paginated or adaptive list).
- Team documents and aligns on requirement in Sprint Planning.
- Feature scope is frozen post-confirmation to avoid rework.

**Backlog Details:**
| Field          | Description |
|----------------|-------------|
| **Priority**   | Low |
| **Estimation** | 2 Story Points |
| **Owner**      | @team |
| **Dependencies** | Client availability for clarification |
| **Notes**      | Solved in Sprint Showcase; reinforced need for early confirmation. |

---

### 🔸 Risk Story 3 – Infrastructure Overload from Team Behavior

**Risk:** Unintended re-upload of failed or oversized files caused server overload, reducing performance across the whole platform.

**Risk Story:**  
_As a development team, we want to validate file uploads and avoid repeated submission of oversized content so that we don’t accidentally crash the server during development._

**Acceptance Criteria:**
- File size checks are introduced before upload.
- Team aligns on a shared policy for data submission hygiene.
- IT confirms server performance stability after changes.

**Backlog Details:**
| Field          | Description |
|----------------|-------------|
| **Priority**   | Medium |
| **Estimation** | 3 Story Points |
| **Owner**      | @team |
| **Dependencies** | WP Upload config / plugin behavior |
| **Notes**      | Caused by multiple large file uploads. Future improvement: add upload limit or automatic clean-up script. |

---

### 🔸 Risk Story 4 – Unclear Priority Causing Low Motivation

**Risk:** Early in Sprint 2, the development team lacked clarity on which basic requirements to focus on, and conflicting views between the Scrum Master and Product Owner on priorities affected team morale and motivation.

**Risk Story:**  
_As a Scrum team, we want to clearly define and communicate requirement priorities early in the sprint so that the development team stays focused and motivated._

**Acceptance Criteria:**
- Functional requirements are grouped into priority levels.
- Developers understand what to deliver first.
- Sprint backlog reflects clearly tiered priorities.

**Backlog Details:**
| Field          | Description |
|----------------|-------------|
| **Priority**   | Medium |
| **Estimation** | 2 Story Points |
| **Owner**      | Scrum Master / Product Owner |
| **Dependencies** | Agreement between leadership roles |
| **Notes**      | Solved by collaborative reclassification and less micromanagement. Developers regained autonomy. |

---

### 🔸 Risk Story 5 – Team Misalignment on Design Decisions

**Risk:** During mid-sprint, disagreement over whether all categories should be color-coded led to confusion and integration failure between two developers, halting development for two days.

**Risk Story:**  
_As a development team, we want to reach early alignment on feature constraints and design scope so that multiple developers can integrate their work without conflict._

**Acceptance Criteria:**
- Design expectations for shared features are confirmed before implementation.
- Agreement is reached on category display limits.
- Integration tasks resume smoothly post-alignment.

**Backlog Details:**
| Field          | Description |
|----------------|-------------|
| **Priority**   | High |
| **Estimation** | 3 Story Points |
| **Owner**      | Product Owner |
| **Dependencies** | Developer sync on feature design |
| **Notes**      | Solved after short discussion. Future: freeze shared logic early. |

---

### 🔸 Risk Story 6 – Misinterpreted Requirements Near Sprint End

**Risk:** On the night before the Sprint Showcase, the team realized too late that the client requirement was to split filter and search into separate pages.

**Risk Story:**  
_As a development team, we want to confirm critical design decisions early and continuously verify requirement interpretations so that we don’t risk last-minute delivery surprises._

**Acceptance Criteria:**
- Feature structure is confirmed with the client before implementation.
- Sprint planning includes requirement check checkpoints.
- Shared interpretation documentation is visible to all team members.

**Backlog Details:**
| Field          | Description |
|----------------|-------------|
| **Priority**   | Medium |
| **Estimation** | 2 Story Points |
| **Owner**      | Scrum Master / Product Owner |
| **Dependencies** | Client communication access |
| **Notes**      | No change needed thanks to client feedback, but highlighted a risk in late-stage discovery. |
