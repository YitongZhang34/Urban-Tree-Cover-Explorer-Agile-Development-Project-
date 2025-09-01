## 📅 Date: 2025-05-25  
🕒 **Time:** 3:00pm–3:30pm  
📍 **Location:** Melbourne Connect, Level 6

| **Team Member** | **Yesterday’s Work**                                                                                      | **Today’s Plan**                                                                                     | **Blockers**                                                                                                                | **Next Steps / Action Items**                                                                                             |
|----------------|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| Whole Team     | All team members have completed their assigned tasks. | Conduct Sprint 3 retrospective and confirm QA completion.                                             | Rating system upload failed (resolved by deprioritising)   | Finalize project reflection and documentation.                                                                             |
| @haoxin (PO)   | Investigated rating issue, consulted Ed; amended Acceptance Criteria.                                      | Officially deprioritised rating backend integration tasks.                                            | None (rating issue resolved by PO decision).                                                                               | Update backlog and artefacts to reflect revised scope.                                                                    |

## 🧾 **Retrospective Highlights**
- Final Sprint 3 retrospective was held in person.
- The **rating upload issue** was confirmed on **May 23** via **Ed Discussion** to be caused by a **server-side problem**.
- Under the advice of the instructor, the team **deprioritised rating-related backend features** (`US7_T2`, `US7_T3`, `US8_T3`) and retained only the frontend components.
- **Haoxin**, acting as Product Owner, **amended the Acceptance Criteria** and formally **deprioritised** the affected tasks.
- **Story Points remained unchanged**, as deprioritisation occurred late and frontend display logic was preserved.
- The team successfully passed **Quality Assurance** for all completed user stories.

---

## 📌 Final Action Items & Deprioritised Tasks

| **User Story** | **Task ID** | **Task Description** | **Assigned To** | **Status** | **Due Date** |
|----------------|-------------|-----------------------|------------------|------------|--------------|
| US07           | US7_T1      | Import a dataset of parks/places of interest near Melbourne Connect & CBD. | @xin | ✅ Completed | 2025-05-14 |
|                | US7_T2      | Allow users to submit 1–10 point ratings for any park. | @xin | ⚠️ Deprioritised (frontend only) | 2025-05-23 |
|                | US7_T3      | Show average park rating. | @zixian | ⚠️ Deprioritised (frontend only) | 2025-05-23 |
|                | US7_T4      | User-submitted markers with tags, images, and descriptions. | @xin | ✅ Completed | 2025-05-21 |
|                | US7_T5      | Filter map to show/hide user-submitted markers. | @zixian | ✅ Completed | 2025-05-25 |
|                | US7_T6      | Display detail for key locations with 3+ photos and descriptions. | @zixian | ✅ Completed | 2025-05-21 |
|                | US7_T7      | Embed YouTube videos for selected locations. | @xin | ✅ Completed | 2025-05-25 |
|                | US7_T8      | UI design for the new feature page. | @yitong | ✅ Completed | 2025-05-25 |
| US08           | US8_T1      | Interactive itinerary map implementation. | @yixiang | ✅ Completed | 2025-05-16 |
|                | US8_T2      | Show directions for the walking itinerary. | @yuqi | ✅ Completed | 2025-05-20 |
|                | US8_T3      | Allow rating of each itinerary stop. | @yixiang | ⚠️ Deprioritised (frontend only) | 2025-05-23 |
|                | US8_T4      | Use dataset of 3000 trees. | @yixiang | ✅ Completed | 2025-05-20 |
|                | US8_T5      | Display tree heatmap near itinerary. | @yuqi | ✅ Completed | 2025-05-20 |
|                | US8_T6      | Show itinerary as map markers. | @yixiang | ✅ Completed | 2025-05-16 |
|                | US8_T7      | UI design for itinerary map page. | @yitong | ✅ Completed | 2025-05-20 |



---

## 📅 Date: 2025-05-21  
🕟 **Time:** 4:30pm–5:00pm  
📍 **Location:** Melbourne Connect, Level 6

| **Team Member** | **Yesterday’s Work**                                                                                      | **Today’s Plan**                                                                                     | **Blockers**                                                                                                                | **Next Steps / Action Items**                                                                                             |
|----------------|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| @yitong        | Updated UI components and key artefacts as Scrum Master.                                                   | Continue artefact updates and begin drafting the final project report.                              | None                                                                                                                       | Finalize report structure; upload latest artefact revisions to GitHub.                                                   |
| @xin & @zixian | Completed US7_T2 (rating), US7_T4 (user markers), and US7_T6 (key location info); US7_T3, T5, and T7 in progress. | Continue developing pending tasks and debugging rating display logic.                               | Rating data fails to upload properly, blocking US7_T3 progress.                                                            | Resolve plugin or API issues with rating upload; polish map filtering and detail sections.                               |
| @yixiang & @yuqi | All features except for rating integration completed and tested.                                           | Support others with remaining tasks and finalize their own components.                              | Same rating system upload issue affecting team integration.                                                                | Assist in identifying root cause of rating issue; support final integration and polish.                                   |

## 🧾 **Stand-Up Highlights**
- Meeting held in-person at Melbourne Connect, Level 6.
- Yitong has updated UI layouts and artefacts, and will start on the final report writing.
- Xin and Zixian have completed three key features (**US7_T2**, **US7_T4**, **US7_T6**) and are working on remaining tasks (**US7_T3**, **US7_T5**, **US7_T7**); blocked by rating upload issue.
- Yixiang and Yuqi have finalized and tested all their assigned **US8** features, except for rating integration due to the same blocker.

---

## 📌 **Pending Action Items**

| **ID** | **Task** | **Assigned To** | **Status** | **Due Date** |
|--------|----------|------------------|------------|--------------|
| US7_T2 | Allow users to submit 1–10 point ratings for any park. | @xin | ✅ Completed | 2025-05-16 |
| US7_T3 | Show average park rating. | @zixian | 🚧 In Progress (blocked by rating upload bug) | TBC |
| US7_T4 | User-submitted markers with tags, images, and descriptions. | @xin | ✅ Completed | 2025-05-16 |
| US7_T5 | Filter map to show/hide user-submitted markers. | @zixian | 🚧 In Progress | TBC |
| US7_T6 | Display detail for key locations with 3+ photos and descriptions. | @zixian | ✅ Completed | 2025-05-16 |
| US7_T7 | Embed YouTube videos for selected locations. | @xin | 🚧 In Progress | TBC |
| US7_T8 | UI design for the new feature page. | @yitong | ✅ Completed | 2025-05-20 |
| US8_T2 | Show directions for the walking itinerary. | @yuqi | ✅ Completed | 2025-05-20 |
| US8_T3 | Allow rating of each itinerary stop. | @yixiang | 🚧 In Progress (blocked by rating upload bug) | TBC |
| US8_T4 | Use dataset of 3000 trees. | @yixiang | ✅ Completed | 2025-05-20 |
| US8_T5 | Display tree heatmap near itinerary. | @yuqi | ✅ Completed | 2025-05-20 |
| US8_T7 | UI design for itinerary map page. | @yitong | ✅ Completed | 2025-05-20 |

## 📅 Date: 2025-05-16  
🕗 **Time:** 8:00pm–8:30pm  
📍 **Location:** Zoom Meeting

| **Team Member** | **Yesterday’s Work**                                                                                      | **Today’s Plan**                                                                                     | **Blockers**                                                                                                                | **Next Steps / Action Items**                                                                                             |
|----------------|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| @xin           | Completed rating system (US7_T2) and user-submitted marker feature (US7_T4); worked with Zixian on Web Page 4. | Continue refining submission form and explore extending plugin to 10-point rating.                    | Rating plugin only supports 1–5 scale; unsure how to delete legacy components (resolved after discussing with Zixian).     | Finalize form cleanup; test user-submitted marker flow; modify rating system if possible.                                |
| @zixian        | Collaborated with Xin on Web Page 4; fixed legacy input issue; continued work on US7_T3 and US7_T5.         | Add logic for toggling user-submitted markers; style average rating section.                          | None                                                                                                                       | Ensure marker filtering works as expected; align visual styling with UI design.                                           |
| @yixiang       | Completed itinerary path and marked all stops on map (US8_T1, US8_T6).                                     | Find solution to show directionality for overlapping paths.                                           | Path overlaps with no directional support from current map API.                                                            | Propose using numbered stops or invisible detour points to resolve visual ambiguity.                                      |
| @yuqi          | Worked on heatmap development; reviewed Ed Discussion for examples.                                       | Test Ed-provided heatmap snippet in current tree map setup.                                           | None                                                                                                                       | Integrate heatmap rendering into itinerary view.                                                                          |
| @yitong        | Began UI design for both new webpages (US7_T8, US8_T7); updated Sprint artefacts as Scrum Master.          | Continue developing UI structure in Figma and support documentation.                                  | None                                                                                                                       | Upload updated UI files to GitHub; coordinate design feedback with dev team.                                              |

## 🧾 **Stand-Up Highlights**
- Team met on Zoom to share progress on Sprint 3.
- Xin (also known as Haoxin) has completed core features including rating and submission systems; resolved legacy code issue with Zixian.
- Plugin limits rating to 5 stars; still investigating how to extend this to 10.
- Yixiang finished itinerary route and markers but highlighted overlapping paths lacking directionality.
- Yuqi is progressing on heatmap with help from Ed's example.
- Yitong started UI layout and continues to maintain Scrum artefacts (Sprint Backlog, Burn Down Chart).

---

## 📌 **Pending Action Items**

| **ID** | **Task** | **Assigned To** | **Status** | **Due Date** |
|--------|----------|------------------|------------|--------------|
| US7_T1 | Import a dataset of parks/places of interest near Melbourne Connect & CBD. | @xin | ✅ Completed | 2025-05-14 |
| US7_T2 | Allow users to submit 1–10 point ratings for any park. | @xin | 🚧 Plugin limited to 5 pts | TBC |
| US7_T3 | Show average park rating. | @zixian | 🚧 In Progress | TBC |
| US7_T4 | User-submitted markers with tags, images, and descriptions. | @xin | 🚧 In Progress | TBC |
| US7_T5 | Filter map to show/hide user-submitted markers. | @zixian | 🚧 In Progress | TBC |
| US7_T6 | Display detail for key locations with 3+ photos and descriptions. | @zixian | 🚧 In Progress | TBC |
| US7_T7 | Embed YouTube videos for selected locations. | @xin | 🔜 Not Started | TBC |
| US7_T8 | UI design for the new feature page. | @yitong | 🚧 In Progress | TBC |
| US8_T1 | Interactive itinerary map implementation. | @yixiang | ✅ Completed | 2025-05-16 |
| US8_T2 | Show directions for the walking itinerary. | @yuqi | 🚧 In Progress | TBC |
| US8_T3 | Allow rating of each itinerary stop. | @yixiang | 🚧 In Progress | TBC |
| US8_T4 | Use dataset of 3000 trees. | @yixiang | 🚧 In Progress | TBC |
| US8_T5 | Display tree heatmap near itinerary. | @yuqi | 🚧 In Progress | TBC |
| US8_T6 | Show itinerary as map markers. | @yixiang | ✅ Completed | 2025-05-16 |
| US8_T7 | UI design for itinerary map page. | @yitong | 🚧 In Progress | TBC |

---

## 📅 Date: 2025-05-12  
🕗 **Time:** 8:30pm–9:00pm  
📍 **Location:** Zoom Meeting

| **Team Member** | **Yesterday’s Work**                                                                                      | **Today’s Plan**                                                                                     | **Blockers**                                                                                                                | **Next Steps / Action Items**                                                                                             |
|----------------|-----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| @xin           | Facilitated Sprint 3 kickoff meeting; presented sprint goals and task breakdown.                          | Begin dataset import (US7_T1), rating system (US7_T2), new marker submission (US7_T4), and video embedding (US7_T7). | None                                                                                                                       | Start implementing development tasks while continuing Product Owner and QA responsibilities.                              |
| @zixian        | Participated in sprint planning; reviewed new rating and marker filtering features.                        | Begin implementation of average rating display (US7_T3), filter toggle (US7_T5), and location detail display (US7_T6). | None                                                                                                                       | Coordinate with Xin on dataset structure; begin feature implementation.                                                   |
| @yixiang       | Participated in sprint planning; discussed walking itinerary requirements.                                 | Start development of the itinerary map (US8_T1), rating per stop (US8_T3), 3000 tree dataset (US8_T4), and heatmap (US8_T5). | None                                                                                                                       | Begin visual and data integration on new itinerary map.                                                                   |
| @yuqi          | Joined sprint planning; confirmed role in itinerary implementation.                                        | Implement itinerary directions (US8_T2) and itinerary markers (US8_T6).                             | None                                                                                                                       | Coordinate with Yixiang to sync directions and markers visually.                                                          |
| @yitong        | Participated in sprint planning; confirmed UI tasks.                                                       | Start designing UI for both new pages (US7_T8, US8_T7).                                               | None                                                                                                                       | Work on wireframes and Figma designs, then update GitHub once approved.                                                   |

## 🧾 **Stand-Up Highlights**
- Sprint 3 commenced with a planning session led by Product Owner Xin via Zoom.
- Xin introduced sprint goals and walked through all user stories.
- Tasks were divided and assigned based on functionality and workload balancing.
- Notably, Xin will take on development duties in addition to PO and QA roles due to the sprint's tight timeline.
- Each team member agreed to begin work immediately on their assigned user stories.
- No blockers were reported during this planning phase.
