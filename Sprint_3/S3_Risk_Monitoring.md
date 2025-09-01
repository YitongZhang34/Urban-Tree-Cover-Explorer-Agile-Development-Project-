# Project Risk Monitoring - Assignment 2

- Document your Risk Monitoring in Sprint 3 for Assignment 2.
- Project Risk Monitoring is a continuous activity and done throughout the project execution cycle (Sprints)  
- Refer to Risk_Monitoring_Guide_and_Example_and_Guide.md under the Guides folder for guidance on how to document this section. An example is shown.
- You can reuse formatting and sections from the guidance for documenting this section


# 📋 Sprint 3 Risk Monitoring – Urban Tree Explorer


## 🛠️ Note on Format Change

This Sprint 3 Risk Monitoring file adopts a revised structure based on the updated instructor feedback provided during Week 11:

![image](https://github.com/user-attachments/assets/4aa8708c-df7d-4345-813c-217a9ce7dfae)


In response, we replaced the previous user-story-style risk descriptions with a formal **risk register** and **incident log**. This new format aligns with the lecture and tutorial content and improves traceability of each risk throughout Sprint 3.

🗓️ **Sprint 3 Duration:** 12 May 2025 – 25 May 2025

---

## Section 1: Risk Register Summary

| ID  | Risk Description                                      | Likelihood (%) | Impact (1–5) | Risk Exposure | Status                  | Owner          |
|-----|-------------------------------------------------------|----------------|--------------|----------------|--------------------------|----------------|
| R1  | Sprint 2 overlap compressed Sprint 3 schedule         | 85%            | 3            | 2.55           | Occurred and Controlled | Scrum Master   |
| R2  | Exams reduced dev time                                | 75%            | 3            | 2.25           | Occurred and Controlled | Product Owner  |
| R3  | Role transition delays codebase progress              | 60%            | 3            | 1.80           | Occurred and Controlled | Scrum Master   |
| R4  | API/Plugin integration issues                         | 80%            | 5            | 4.00           | Occurred and Controlled | Dev Lead       |
| R5  | Module integration conflict                           | 65%            | 5            | 3.25           | Occurred and Controlled | Dev Team       |
| R6  | Server instability (upload failures)                  | 55%            | 3            | 1.65           | Occurred and Controlled | Backend Lead   |
| R7  | Plugin limitations restrict UI                        | 70%            | 3            | 2.10           | Occurred and Controlled | Frontend Dev   |
| R8  | Mid-sprint scope changes may impact goals             | 90%            | 4            | 3.60           | Not Occurred            | Product Owner  |
| R9  | Unclear requirements may cause misalignment           | 90%            | 4            | 3.60           | Not Occurred            | Product Owner  |
| R10 | Lack of map integration experience                    | 60%            | 3            | 1.80           | Not Occurred            | Dev Team       |
| R11 | Map plugin may lag with large datasets                | 40%            | 4            | 1.60           | Not Occurred            | Dev Team       |
| R12 | Git merge conflicts before deadline                   | 50%            | 3            | 1.50           | Not Occurred            | Dev Lead       |
| R13 | Inexperience with Scrum and documentation             | 60%            | 3            | 1.80           | Not Occurred            | Scrum Master   |
| R14 | Stakeholder unavailability delays feedback            | 40%            | 4            | 1.60           | Not Occurred            | Product Owner  |
| R15 | Browser compatibility issues                          | 40%            | 4            | 1.60           | Not Occurred            | Frontend Dev   |
| R16 | Unexpected team member absence                        | 30%            | 4            | 1.20           | Not Occurred            | Scrum Master   |
| R17 | Poor mobile performance in outdoor areas              | 30%            | 4            | 1.20           | Not Occurred            | Dev Team       |
| R18 | Inadequate test coverage                              | 40%            | 3            | 1.20           | Not Occurred            | Dev Team       |
| R19 | Uneven workload distribution                          | 60%            | 2            | 1.20           | Not Occurred            | Scrum Master   |
| R20 | Incomplete validation causes bugs in hidden pages     | 50%            | 3            | 1.50           |  Not Occurred           | QA Lead        |

---

## Section 2: Monitored Risk Incidents

### 🟠 R1 – Sprint 2 Overlap Compressed Sprint 3 Schedule
- **When:** Identified during Sprint Planning on 12 May 2025  
- **Who:** Scrum Master (Yitong)  
- **Action:** Reprioritised backlog, frontloaded critical tasks, and shortened story list for Sprint 3  
- **Impact:** Reduced total story points in Sprint 3; focused delivery on Park Explorer and Walking Itinerary Map  
- **Monitoring:** Reviewed remaining capacity during Stand-ups on 13 and 16 May  

---

### 🟠 R2 – Exam Period Reduced Dev Time
- **When:** Observed mid-sprint during Stand-up on 16 May 2025  
- **Who:** Scrum Master and Product Owner  
- **Action:** Encouraged modularised task division and flexible collaboration based on personal availability  
- **Impact:** Lower overall task velocity during weekdays; more progress made closer to Sprint end  
- **Monitoring:** Workload and task updates tracked across daily Stand-ups  

---

### 🟠 R3 – Role Transition Delayed Codebase Progress
- **When:** Reported during Sprint Planning on 12 May 2025  
- **Who:** Xin 
- **Action:** Previous contributors provided walkthroughs; reassigned tasks earlier in Sprint  
- **Impact:** Slight ramp-up delay for new contributors; mitigated by pair programming in early week  
- **Monitoring:** Scrum Master reviewed onboarding progress during Stand-ups  

---

### 🟠 R4 – API/Plugin Integration Issue
- **When:** Encountered 16–23 May 2025  
- **Who:** Xin  
- **Action:** Added fallback UI states and static mock display for failed API cases; deprioritised feature on 23 May  
- **Impact:** Incomplete rating average; visible reduction in feature completeness  
- **Monitoring:** Monitored plugin/API behaviour with backup scenarios  

---

### 🟠 R5 – Module Integration Conflict
- **When:** Occurred during testing on 22 May 2025  
- **Who:** Zixian and Xin  
- **Action:** Filter logic rewritten; integration testing repeated; backup map version prepared  
- **Impact:** Minor display bug fixed; final build stable for showcase  
- **Monitoring:** Testing checklist enforced before demo  

---

### 🟠 R6 – Server Instability (Upload Failures)
- **When:** Observed intermittently between 18–23 May 2025  
- **Who:** Zixian
- **Action:** Monitored server logs; attempted re-upload logic and simplified submission forms  
- **Impact:** Upload failed in 1 demo case; users notified to refresh and retry  
- **Monitoring:** Team tested submission endpoints daily on staging  

---

### 🟠 R7 – Plugin Limitations Restrict UI
- **When:** Discovered during rating and marker filter implementation on 17 May 2025  
- **Who:** Xin and Zixian  
- **Action:** Custom logic used to bypass plugin limitations; fallback filter toggle designed manually  
- **Impact:** Filtering feature less dynamic than planned; feedback noted in demo  
- **Monitoring:** Discussed during Sprint Review with supervisor on 21 May  

---

