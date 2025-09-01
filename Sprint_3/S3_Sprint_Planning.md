# Sprint Planning (Sprint 3) - Assignment 2

- Document your Sprint Planning for Sprint 3 for Assignment 2.
- Refer to Sprint_Planning_Guide_and_Example_and_Guide.md under the Guides folder for guidance on how to document this section. An example is shown.
- You can reuse formatting and sections from the guidance for documenting this section

# Sprint Planning (Sprint 3) – Assignment 2

---

## Baseline User Story for Estimation

To guide our story point estimation, our team reused the following baseline story for consistency.

### Baseline Story

**User Story:** As a registered user, I want to log into the system using my email and password so that I can access my dashboard.

- **Estimated Story Points:** 5 (Fibonacci sequence)
- **Rationale:** This involves authentication logic, form validation, and database look-up. It is moderately complex and served as a comparison point for estimating new stories in Sprint 3.

---

## Sprint Goal

Enhance the platform’s value by allowing users to explore park locations and share their own ratings and insights, while also showcasing a green walking itinerary with foliage heatmaps and directional markers across Melbourne CBD.  

---

## Selected User Stories

---

### **[US 07] Park Explorer Map**

**As a** PhD student at Melbourne Connect,  
**I want to** explore nearby parks and places of interest using an interactive map,  
**so that** I can learn more about each park, view ratings, and contribute my own useful locations or opinions.

#### Acceptance Criteria

- [AC7-1] Show markers for parks around Melbourne Connect and the CBD, including highlighted markers for University Square, Lincoln Square, Argyle Square, and Carlton Gardens with 3+ photos and a description.
- [AC7-2] Enable user rating input from 1–10 per park. Users should see a scale input UI on each park marker, and the average rating should be displayed dynamically.
  **Amended on 23th May:** Enable user rating input from 1–10 per park. Show a frontend rating interface (updated dynamically).  
  **Note:** Backend average rating update is deprioritised due to server-side limitations. Only frontend rating interface will be shown.
- [AC7-3] Implement a filter toggle to switch between system-default markers and user-submitted markers.
- [AC7-4] Allow users to submit new markers with a category, image(s), and a short description. Marker appears immediately without moderation.
- [AC7-5] Show embedded YouTube videos in key location popups.  
- [AC7-6] Ensure map dataset includes parks and places of interest near Melbourne Connect and within the CBD.

#### Estimation using Fibonacci Sequence

| Factor         | Consideration                                                                 |
|----------------|------------------------------------------------------------------------------|
| Complexity      | Medium–High – Requires map UI, submission form, image handling, video embeds |
| Uncertainty     | Medium – User-submitted content and data consistency                         |
| Dependencies    | High – Dataset, media handling, toggles, custom marker logic                 |
| Risk            | Medium – Submission spam, map clutter, performance                           |
| Estimated SP    | **13 SP**                                                                    |

#### Rationale & Method

Compared to the 5 SP login baseline, this story involved multiple UI components and backend logic. Planning Poker yielded 13 SP based on the overall workload, media embedding, and frontend/backend coordination needs.

---

### **[US 08] Walking Itinerary Map**

**As a** PhD student interested in a refreshing city walk,  
**I want to** follow a visualised walking route with park/landmark ratings and tree foliage density,  
**so that** I can plan an enjoyable and green journey through the city.

#### Acceptance Criteria

- [AC8-1] Show the 11 predefined stops (from Melbourne Uni Old Quad to Melbourne Connect) in correct order, with directional connections on the map.
- [AC8-2] Each waypoint should allow users to submit a 1–10 rating and see the average rating for that location.
  **Amended on 23th May:** Each waypoint should allow users to submit a 1–10 rating (frontend component only).
  **Note:** Backend average logic is deprioritised. Only frontend UI is implemented.
- [AC8-3] Overlay a foliage heatmap that is visually distinct from the walking route.

#### Estimation using Fibonacci Sequence

| Factor         | Consideration                                                                 |
|----------------|------------------------------------------------------------------------------|
| Complexity      | Medium – Includes routing, visual overlays, and minor interactivity          |
| Uncertainty     | Low – Predefined route and static dataset                                    |
| Dependencies    | Medium – Route data, heatmap, rating interface                               |
| Risk            | Low – Frontend-focused, limited backend dependency                           |
| Estimated SP    | **8 SP**                                                                    |

#### Rationale & Method

Although this feature appears less interactive than US 07, it requires structured display logic, visual overlays, and accuracy in routing and foliage representation. As a result, it was estimated at **13 SP**.

---

## Sprint Backlog Tasks

| User Story ID | Task ID  | Task Description                                                                                                                                                                                                                     | Owner      | Status       |
|---------------|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------------|
| US 07         | US7_T1   | Import a dataset which includes parks and places of interest near Melbourne Connect and around the CBD.                                                                                                                              | Xin        | Completed     |
|               | US7_T2   | Enable users to submit their own rating of any park on a 1-10 point scale.                                                                                                                                                           | Xin/Zixian | Deprioritised |
|               | US7_T3   | Enable users to see the average rating.                                                                                                                                                                                              | Zixian     | Deprioritised |
|               | US7_T4   | Enable users to submit new markers for locations, including new Parks or Places of Interest they think would be useful. Includes tagging category, image upload, and free-text description. Markers appear without moderation.      | Xin/Zixian | Completed     |
|               | US7_T5   | Enable users to filter the markers on the map to either show or not show the user-submitted markers.                                                                                                                                  | Zixian     | Completed     |
|               | US7_T6   | Enable users to view detailed information (3+ photos and description) for specific locations: University Square, Lincoln Square, Argyle Square, Carlton Gardens. Locations must stand out clearly on the map.                         | Zixian     | Completed     |
|               | US7_T7   | Embed YouTube videos demonstrating at least two of the key locations above.                                                                                                                                                          | Xin        | Completed     |
|               | US7_T8   | Design the UI of the Park Explorer webpage.                                                                                                                                                                                           | Yitong     | Completed     |
| US 08         | US8_T1   | Implement an interactive map on a separate new page to visualise a pre-determined walking itinerary through 11 locations from University of Melbourne Old Quad to Melbourne Connect.                                                | Yixiang    | Completed     |
|               | US8_T2   | When the map loads there should be directional arrows showing the walking itinerary.                                                                                                                                                  | Yuqi       | Completed     |
|               | US8_T3   | Enable users to rate each stop along the itinerary.                                                                                                                                                                                   | Yixiang    | Deprioritised |
|               | US8_T4   | Use a dataset of 3000 tree records.                                                                                                                                                                                                   | Yixiang    | Completed     |
|               | US8_T5   | Show the tree locations around the walking itinerary path as a foliage heatmap.                                                                                                                                                      | Yixiang    | Completed     |
|               | US8_T6   | Show the walking itinerary path and its 11 stops as map markers.                                                                                                                                                                     | Yuqi       | Completed     |
|               | US8_T7   | Design the UI of the Walking Itinerary webpage.                                                                                                                                                                                       | Yitong     | Completed     |

---

## Commitment

The team commits to:

- Finalizing the Park Explorer interface, including marker data, rating system (frontend), and user submissions.
- Building the complete Walking Itinerary Map with correct route layout, foliage heatmap, and waypoint ratings (frontend).
- Delivering a polished, responsive, and accessible experience across both pages using available urban data.
- Producing a basic prototype early in the sprint (by Day 2) to establish shared visual and functional expectations.

