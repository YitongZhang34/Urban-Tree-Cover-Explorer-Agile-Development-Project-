

# Risk Management and Risk Register

### Risk ID: 101

**Risk Statement:**  
_"Client has not finalized all feature specifications (e.g., location sharing) → Requirements change mid-development → Delivered features may not align with expectations."_

- **Probability:** 90.0% – Client has already provided evolving requirements during Sprint 1.
- **Impact:** 7 – If the wrong feature is implemented, this could waste a full sprint cycle.
- **Justification:** The client provided new details post-planning. This creates a strong likelihood of scope drift if not well-managed.
- **Exposure:** 6.3 
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Document all unclear requirements in a shared backlog.
  - Schedule regular check-ins with client to clarify evolving needs.
  - Use placeholder implementations for ambiguous features.
- **Contingency Plan:**
  If requirements change mid-sprint, schedule an emergency team meeting to reassess priorities. De-scope lower-priority items and update backlog to reflect client’s new direction.
---

### Risk ID: 102

**Risk Statement:**  
_"Stakeholders may request new features mid-sprint → Scope increases unexpectedly → Sprint goals may not be met."_

- **Probability:** 90.0% – Stakeholders often suggest additions when viewing working software.
- **Impact:** 8 – Mid-sprint changes could derail core sprint goals.
- **Justification:** Based on past communication with stakeholders, scope expansion pressure is common once partial features are visible.
- **Exposure:** 7.2 
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Freeze requirements at sprint planning.
  - Track scope change requests for future sprints.
  - Clearly communicate impacts of new requests to stakeholders.
- **Contingency Plan:**
  If new feature requests emerge mid-sprint, log them in a separate backlog and notify stakeholders that they’ll be considered for the next sprint. Continue current sprint as planned to avoid disruption.
---

### Risk ID: 103

**Risk Statement:**  
_"WordPress may restrict advanced UI/UX features (e.g., real-time filtering or marker clustering) → User experience is compromised → Client may be dissatisfied."_

- **Probability:** 30.0% – Core features can still be implemented using standard plugins.
- **Impact:** 7 – Some advanced UX may not be supported natively.
- **Justification:** WordPress limits some real-time interactions, but most core functionality is still achievable.
- **Exposure:** 2.1 
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Prioritize user-critical features within WordPress limits.
  - Explore alternate plugin configurations or scripts.
  - Discuss limitations with the client early.
- **Contingency Plan:**
  If WordPress limits a required feature, inform the client immediately, present alternative solutions (e.g., external tools or reduced functionality), and document the decision.
---

### Risk ID: 104

**Risk Statement:**  
_"Large dataset causes performance issues in map plugin → Map crashes or becomes unresponsive → Application is unusable."_

- **Probability:** 40.0% – Performance issues occurred during internal testing.
- **Impact:** 8 – If the map crashes, the entire platform loses usability.
- **Justification:** Dataset scale is large (~3000 trees); browser strain is probable but not consistent. 
- **Exposure:** 3.2  
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Optimize dataset before loading (e.g., pagination, clustering).
  - Use sample data during development to simulate scale.
  - Test performance early across devices.
- **Contingency Plan:**
  If performance issues arise, switch to simplified dataset display (e.g., pagination or selective loading). Disable optional features temporarily to maintain usability.
---

### Risk ID: 105

**Risk Statement:**  
_"Team lacks experience in handling geo-data and map APIs → Integration takes longer than planned → Sprint deliverables delayed."_

- **Probability:** 60.0% – Some team members had not worked with geoJSON or mapping tools.
- **Impact:** 6 – Might delay integration but is recoverable with research/support.
- **Justification:** New tech stack and limited documentation for WordPress mapping plugins increases learning time.  
- **Exposure:** 3.6  
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Allocate extra research hours for map integration tasks.
  - Use online tutorials and examples from plugin documentation.
  - Pair experienced and less-experienced members on technical tasks.
- **Contingency Plan:**
  If integration tasks stall due to inexperience, escalate to a senior member or tutor, split the task into simpler subtasks, and assign more support to struggling members.
---

### Risk ID: 106

**Risk Statement:**  
_"Uneven task distribution among team members → Some members overworked while others are idle → Reduced team efficiency."_

- **Probability:** 60.0% – Previous sprints showed some team imbalance.
- **Impact:** 4 – Delays may occur, but short-term redistributions are feasible.
- **Justification:** Task tracking revealed uneven load mid-sprint, causing small drops in output from some members.
- **Exposure:**  2.4
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Assign tasks during sprint planning with effort estimation.
  - Rotate responsibilities across sprints.
  - Use burndown charts to track individual contributions.
- **Contingency Plan:**
  If workload becomes uneven, immediately redistribute tasks and adjust sprint board. Hold a mid-sprint check-in to catch imbalances early.
---

### Risk ID: 107

**Risk Statement:**  
_"Team is unfamiliar with Scrum ceremonies and Git documentation → SDLC artefacts may be incomplete or incorrect → Submission quality suffers."_

- **Probability:** 60.0% – Teams new to Scrum often miss artefact detail in early sprints.
- **Impact:** 5 – Final grade/report clarity may suffer.
- **Justification:** Past experience shows new teams forget to link tasks to deliverables or omit sections under pressure. 
- **Exposure:** 3
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Review examples from the Guides folder before each artefact.
  - Assign roles like 'Scrum Master' or 'Document Lead.'
  - Conduct internal review of each artefact before final commit.
- **Contingency Plan:**
  If artefacts are incorrect or incomplete, conduct a focused internal review session to fix issues before submission. Ask tutor for quick guidance if unclear.
---

### Risk ID: 108

**Risk Statement:**  
_"Tight 6-week timeline with fixed sprint deadlines → Delays in Sprint 1 affect future sprints → Final project delivery is at risk."_

- **Probability:** 50.0% – Timeline pressure was acknowledged in planning meetings.
- **Impact:** 9 – Project scope or quality may degrade if recovery buffers are exhausted.
- **Justification:** Tight 6-week delivery window with inter-sprint dependencies; even one delay causes ripple effects.  
- **Exposure:** 4.5  
- **Mitigation Strategy:** **Avoid**  
- **Mitigation Plan:**  
  - Deliver minimum viable features early in each sprint.
  - Allocate buffer time in each sprint plan.
  - Review sprint backlog weekly to stay on track.
 **Contingency Plan:**
  If Sprint 1 falls behind, reduce scope for the next sprint and refocus on MVP. Re-prioritize backlog based on what's feasible in remaining weeks.
---

### Risk ID: 109

**Risk Statement:**  
_"Team member becomes unavailable due to illness or personal reasons → Task reassignment delays progress → Sprint deliverables are incomplete."_

- **Probability:** 30.0% – No one has reported issues, but illness or burnout can’t be ruled out.
- **Impact:** 8 – If one developer drops mid-sprint, the remaining team must absorb their tasks.
- **Justification:** Human factors are unpredictable; past teams have encountered this mid-delivery. 
- **Exposure:** 2.4  
- **Mitigation Strategy:** **Accept**  
- **Mitigation Plan:**  
  - Cross-train team members on critical tasks.
  - Maintain clear documentation for task handovers.
  - Redistribute tasks early if warning signs appear.
**Contingency Plan:**
  If a member becomes unavailable, immediately reassign their tasks to others based on documentation. Use a backup plan to delay non-critical features if needed.
---

### Risk ID: 110

**Risk Statement:**  
_"Client or teaching staff unavailable during feedback periods → Questions go unanswered → Misaligned development outcomes."_

- **Probability:** 40.0% – Teaching team has other commitments; not always responsive.
- **Impact:** 7 – Unanswered questions may lead to incorrect assumptions.
- **Justification:** Response delays were seen during clarification requests in Sprint 1. 
- **Exposure:** 2.8  
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Submit questions asynchronously and document them.
  - Request feedback in advance of sprint deadlines.
  - Proceed with fallback assumptions after deadline.
**Contingency Plan:**
  If feedback is unavailable, proceed using fallback assumptions and document all decisions clearly for future review. Share outcomes with the client post-sprint for validation.
---

### Risk ID: 111

**Risk Statement:**  
_"The web-based platform may load slowly or fail on mobile devices in low-bandwidth outdoor locations → Frustrates users during field meetups → Limits adoption."_

- **Probability:** 30.0% – Basic app loads on mobile, but performance tests were limited.
- **Impact:** 8 – Poor outdoor usability makes the platform impractical for field use.
- **Justification:** Shaded outdoor areas often have weak signal; mobile tests showed slower loads.  
- **Exposure:** 2.4 
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Optimize map rendering and asset loading.  
  - Use lazy loading for trees outside the viewport.  
  - Test app performance under throttled network conditions.
**Contingency Plan:**
  If mobile performance fails, deploy a fallback lightweight version of the site with essential functionality only. Notify users of limitations in the UI.
---

### Risk ID: 112

**Risk Statement:**  
_"Limited time for formal testing → Bugs go unnoticed until deployment → Reduces platform reliability."_

- **Probability:** 40.0% – Testing was deprioritized in Sprint 1 due to time constraints.
- **Impact:** 6 – Uncaught bugs may persist into Showcase.
- **Justification:** Backlog grooming shows low test-point allocation relative to features delivered.
- **Exposure:** 2.4 
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Allocate story points for testing in each sprint.  
  - Define test cases early (especially for filters and login).  
  - Peer-review all features before merging.
**Contingency Plan:**
  If bugs are discovered post-deployment, assign a hotfix team to patch them immediately. Notify the client of known issues and provide an ETA for fixes.
---

### Risk ID: 113

**Risk Statement:**  
_"Plugin or custom code may behave differently on Chrome, Safari, Firefox → User experience breaks across devices."_

- **Probability:** 40.0% – Some browser-specific CSS issues have already been found.
- **Impact:** 7 – If left unresolved, creates a fragmented user experience.
- **Justification:** Styling and plugin behavior differs slightly across Chrome/Safari/Firefox already.  
- **Exposure:** 2.8  
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Test UI across major browsers weekly.  
  - Use responsive design and standard HTML/CSS.  
  - Prioritize Chrome-first support based on expected usage.
**Contingency Plan:**
  If browser issues are reported, isolate problematic code, apply quick style fixes or polyfills, and issue a patch update. Recommend supported browsers to users temporarily.
---

### Risk ID: 114

**Risk Statement:**  
_"Multiple changes to artefacts or features near deadline → Merge conflicts delay final commits → Risk of submitting outdated or broken files."_

- **Probability:** 50.0% – Merge conflicts occurred near Sprint 1 demo.
- **Impact:** 6 – Could delay final commit or break important features.
- **Justification:** Git coordination was inconsistent; multiple branches touched shared files close to deadline.  
- **Exposure:** 3.0  
- **Mitigation Strategy:** **Mitigate**  
- **Mitigation Plan:**  
  - Define a Git merge protocol and branching policy.  
  - Freeze major feature work 2 days before submission.  
  - Assign a final commit owner to validate the repository state.
**Contingency Plan:**
  If merge conflicts occur near deadline, freeze all new changes. Have a designated member resolve conflicts while others validate functionality. Submit the most stable build available.
---
### Risk ID: 115 （updated after sprint 2）
**Risk Statement:**  
*End-of-semester deadlines and multiple coursework clashes → Reduced team availability → Delays in final Sprint tasks.*

- **Probability:** 80.0% - Many team members said they had other final assignments during Sprint 3. Because of this, progress was slower and some tasks were delayed. This makes it very likely that team members won’t always be available.
- **Impact:** 7 - If team members are too busy, it could delay key tasks like finishing the UI or preparing for submission. The final result may be incomplete or feel rushed.
- **Exposure:** 5.6
- **Justification:** Final assignments from other units constrained available time for development and testing.
- **Mitigation Strategy:** Mitigate 🟡
- **Mitigation Plan:**
  - Coordinate individual schedules early in Sprint 3.
  - Prioritize core deliverables for early completion.
  - Schedule additional late-night or weekend syncs if needed.
- **Contingency Plan:**
  If delivery falls behind, focus efforts on completing MVP functionality only. Non-essential UI polish or enhancements can be deprioritized.

---

### Risk ID: 116 （updated after sprint 2）
**Risk Statement:**  
*Loss of backend plugin functionality or API bugs → Blockers for frontend tasks (e.g., rating, filtering) → Feature remains incomplete at submission.*

- **Probability:** 50.0%
- **Impact:** 8 - The backend depends on plugins we can’t fully control, so there's a fair chance that more bugs could happen.
- **Exposure:** 4.0 - If the backend breaks, users might not see important features like ratings or filters. This would make the website feel broken and hurt the overall experience.
- **Justification:** A bug in the plugin delayed rating average display; future regressions are possible due to limited plugin control.
- **Mitigation Strategy:** Mitigate 🟡
- **Mitigation Plan:**
  - Assign early backend testing and dummy data mocking.
  - Create fallback frontend UI states (e.g., loading, “no data”) to avoid complete failure.
- **Contingency Plan:**
  If the backend fails near submission, display static mock data or hide the component with a placeholder message (e.g., “coming soon”).

---

### Risk ID: 117 （updated after sprint 2）
**Risk Statement:**  
*Team may not fully validate functionality across entire web application → Bugs persist in overlooked pages (e.g., Park Explorer, Walking Itinerary) → Poor user impression during showcase.*

- **Probability:** 50.0% - Because we focused mostly on the main map page, other pages didn’t get much testing. It’s quite possible that small bugs were missed.
- **Impact:** 6 -Bugs on these pages won’t stop the whole site, but they might make the project look unpolished during the demo or to users.
- **Exposure:** 3.0
- **Justification:** Focus on high-priority tasks led to potential neglect of integrated testing across all user stories.
- **Mitigation Strategy:** Mitigate 🟡
- **Mitigation Plan:**
  - Perform final end-to-end walkthroughs with different team members.
  - Allocate 1–2 hours as a “QA freeze window” before final submission.
- **Contingency Plan:**
  If issues surface during demo, pre-select stable user flows for presentation and note fixes in README or video narration.

---

## 📋 Ongoing Risk Register (Updated for Sprint 3)

| **Risk ID** | **Risk Statement (Summary)**                                      | **Probability (%)** | **Impact** | **Exposure** | **Mitigation Strategy** | **Justification** |
|-------------|--------------------------------------------------------------------|----------------------|------------|--------------|--------------------------|-------------------|
| 102         | Mid-sprint scope changes may impact goals                          | 90.0%               | 8          | 7.2          | Mitigate 🟡              | Stakeholders tend to propose new ideas mid-sprint. |
| 101         | Unclear requirements may cause misalignment                        | 90.0%               | 7          | 6.3          | Mitigate 🟡              | Client revised scope in each sprint. |
| 115         | End-of-semester schedule clashes reduce team availability          | 80.0%               | 7          | 5.6          | Mitigate 🟡              | Students reported conflicts with other final units. |
| 108         | Tight schedule impacts recovery                                    | 50.0%               | 9          | 4.5          | Avoid 🔴                 | 6-week hard deadline with no sprint buffer. |
| 116         | Backend bugs block frontend completion                             | 50.0%               | 8          | 4.0          | Mitigate 🟡              | Rating average display failed due to plugin. |
| 105         | Lack of map integration experience                                 | 60.0%               | 6          | 3.6          | Mitigate 🟡              | GeoJSON/map stack was new to team. |
| 114         | Git merge conflicts before deadline                                | 50.0%               | 6          | 3.0          | Mitigate 🟡              | Last-minute merges caused conflicts in Sprint 1. |
| 117         | Missed bugs on less-tested pages                                   | 50.0%               | 6          | 3.0          | Mitigate 🟡              | Final sprint divided focus across pages. |
| 107         | Inexperience with Scrum and documentation                          | 60.0%               | 5          | 3.0          | Mitigate 🟡              | Document QA varied by team member. |
| 110         | Stakeholder unavailability delays feedback                         | 40.0%               | 7          | 2.8          | Mitigate 🟡              | Feedback delay in Sprint 1 confirmed pattern. |
| 113         | Browser compatibility issues                                       | 40.0%               | 7          | 2.8          | Mitigate 🟡              | Style issues observed in Safari and Firefox. |
| 109         | Unexpected team member absence                                     | 30.0%               | 8          | 2.4          | Mitigate 🟡              | Illness event occurred during Sprint 1. |
| 111         | Poor mobile performance in outdoor areas                           | 30.0%               | 8          | 2.4          | Mitigate 🟡              | Mobile load test showed performance issues outdoors. |
| 112         | Inadequate test coverage                                           | 40.0%               | 6          | 2.4          | Mitigate 🟡              | Time pressure reduced test allocation. |
| 103         | WordPress limits may affect UX                                     | 30.0%               | 7          | 2.1          | Mitigate 🟡              | Plugin/JS workarounds needed for some features. |

---


## **Legend for Mitigation Strategies**

- **Accept** 🟢 → Acknowledge the risk but take no preventive action.  
- **Ignore** 🔵 → Considered low priority with minimal impact.  
- **Mitigate** 🟡 → Take action to reduce probability or impact.  
- **Avoid** 🔴 → Change project approach to eliminate the risk.
---


## 📅 Sprint 1 Risk Monitoring Summary

### New Risks Materialized:
- Risk 101 (Unclear requirements): Affected UI fidelity decisions → resolved after client clarification meeting.
- Risk 103 (WordPress limitations): Caused delay in tree data visualization → mitigated via consultation and data cleanup.
- Risk 109 (Team member illness): One member unavailable → workload redistributed mid-sprint.

### Adjusted Strategies:
- Risk 109 was handled reactively; although initially unmanaged, a mitigation plan was introduced to avoid timeline impact.

### Removed or Resolved Risks:
- Risk 105 (Lack of map API experience): Addressed early via documentation and pairing, no longer a major concern.

### Lessons Learned:
- Define MVP features early and postpone non-essentials to prevent over-scoping.
- Reduce unnecessary meeting frequency—async check-ins improved morale and efficiency.
- Early platform testing avoids rework; constraints should be validated in Sprint 1.
- Client feedback should be gathered before implementing high-fidelity designs.

---

## 📅 Sprint 2 Risk Monitoring Summary

### New Risks Materialized:
- Risk 104 (Performance crash due to dataset): Triggered → mitigated via data cleanup.
- Risk 101 (Unclear requirements): Affected map structure (search + filter) → resolved by client approval.
- Risk 105 (Lack of map integration experience): Some delays in tree rendering integration.

### Adjusted Strategies:
- Risk 109 updated from **Accept** → **Mitigate** (cross-training and backup plans added).
- Risk 106 (Uneven task load) monitored closely—Scrum Master adjusted task allocations in mid-sprint check-in.
- Risk 102 (Scope creep) was closely managed by freezing new features after Sprint Planning.

### Removed or Resolved Risks:
- Risk 106 (Task imbalance): No longer critical after Sprint 2 redistribution.
- Risk 103 (UX limitations): Workaround solutions adopted, not a blocker anymore.

### Lessons Learned:
- Clarify requirements *early in sprint* to prevent last-minute pivots.
- Limit design freedom without coordination—caused dev halt (May 5–7).
- Use priority labels in backlog to support developer motivation and clarity.
- Shared assumptions must be verified with client to avoid wasteful implementation.

---

## 📅 Sprint 3 Risk Monitoring Summary

### New Risks Materialized:
- **Risk 115 (End-of-semester conflicts):** Team availability dropped significantly from May 15 onward. Critical tasks were pushed to late-night or weekend hours. Mitigated via prioritisation and flexible scheduling.
- **Risk 116 (Backend bugs blocking frontend):** Rating average display was blocked by plugin/API failure. Mitigated via fallback UI and deprioritisation during demo.
- **Risk 117 (Missed bugs in less-tested pages):** Park Explorer and Itinerary pages received minimal final testing. Known bugs were hidden during demo or documented post-submission.

### Adjusted Strategies:
- **Risk 101 (Unclear requirements):** Remained a concern, but had no major Sprint 3 impact due to reduced client interaction. Monitoring continued.
- **Risk 107 (Inexperience with documentation):** Addressed via peer review of QA artefacts before submission.
- **Risk 102 (Scope creep):** Proactively managed—rating system was deprioritised before Week 2 to avoid missed deadlines.

### Removed or Resolved Risks:
- **Risk 108 (Tight schedule):** Still present, but managed successfully via early planning. Team delivered all planned features despite deadline pressure.
- **Risk 114 (Git merge conflicts):** Did not occur in Sprint 3 due to careful task boundaries and sync-ups—no merge issues near demo date.

### Lessons Learned:
- Protect MVP scope early. Feature cuts (e.g., ratings) ensured submission quality and reduced stress.
- Maintain redundancy—handover between frontend/back devs improved continuity during crunch time.
- Postpone high-effort UI polish unless core functionality is stable.
- Consider an end-of-sprint QA freeze period earlier next time (not just final day).


