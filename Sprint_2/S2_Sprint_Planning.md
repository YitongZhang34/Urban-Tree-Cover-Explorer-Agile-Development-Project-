# Sprint Planning (Sprint 2) - Assignment 2


##  Baseline User Story for Estimation

To guide our story point estimation, our team first agreed on a **baseline user story** with well-understood complexity.

### Baseline Story

**User Story:** As a registered user, I want to log into the system using my email and password so that I can access my dashboard.

- **Estimated Story Points:** 5 (Fibonacci sequence)
- **Rationale:** This involves authentication logic, form validation, and database look-up. We collectively judged it moderately complex and representative of an average story. It serves as a comparison point for all subsequent estimations.

---

##  Sprint Goal

Enable secure platform access via UniMelb SSO and empower users to explore and filter tree-based meetup locations through an interactive, accessible map interface.

---

##  Selected User Stories

### **[US 01] Exploring Meetup Locations**

**As a** member of the teaching team,**I want to** explore potential meetup locations on an interactive map using tree-based environmental data,**so that** I can evaluate and choose the most shaded, suitable spot for upcoming PhD meetups.

####  Acceptance Criteria

- [AC1-1] View and switch between different map layers.
- [AC1-2] High-quality, intuitive interaction with the map.
- [AC1-3] Expanded default map view for easier exploration.

#### 🧾 Estimation using Fibonacci Sequence

| Factor                 | Consideration                                                       |
| ---------------------- | ------------------------------------------------------------------- |
| Complexity             | Medium – UI integration, design fidelity, map API.                  |
| Uncertainty            | Medium – Layout responsiveness, accessibility.                      |
| Dependencies           | High – Relies on OSM integration and finalized mockups.             |
| Risk                   | Medium – Screen size compatibility and user feedback incorporation. |
| Estimated Story Points | **8**                                                               |

####  Rationale & Method

We estimated this story as **8 SP** by comparing it to our baseline story of “UniMelb Login (5 SP)” and recognizing the additional complexity in frontend design implementation, larger visual scope, and responsive layout testing.Estimation was conducted via **Planning Poker**, where each member anonymously submitted a point value. After discussion, we reached a consensus on 8 SP, especially due to the high UI demands and performance requirements across devices.

---

### **[US 03] User Login via SSO**

**As a** UniMelb staff or student,**I want to** log in using my UniMelb credentials,**so that** I can securely access the platform.

####  Acceptance Criteria

- [AC2-1] Login interface shows clear error messages.
- [AC2-2] Redirects to homepage and maintains session after successful login.

####  Estimation using Fibonacci Sequence

| Factor                 | Consideration                                                 |
| ---------------------- | ------------------------------------------------------------- |
| Complexity             | High – Integration with UniMelb SSO and session handling.     |
| Uncertainty            | Medium – Depends on access to correct APIs and backend logic. |
| Dependencies           | High – Requires backend support and session management logic. |
| Risk                   | Medium – Security and data handling considerations.           |
| Estimated Story Points | **13**                                                        |

####  Rationale & Method

We used the “email/password login” as a **baseline story (5 SP)**. UniMelb SSO was assessed as significantly more complex due to unfamiliarity with third-party integration, security handling, and redirect/session persistence.We used **consensus-based discussion** with reference to documentation and prior examples. The member with prior backend experience explained the technical effort, and after group discussion, we collectively agreed on **13 SP**.

---

### **[US 04] Search and Filtering Capabilities**

**As a** user,**I want to** search and filter trees based on attributes like species, location, canopy size, and useful life expectancy,**so that** I can refine options and find shaded meetup areas.

####  Acceptance Criteria

- [AC3-1] Display nearby trees by location and radius.
- [AC3-2] Show filtered trees with useful details.
- [AC3-3] Visual consistency with colors and units.

####  Estimation using Fibonacci Sequence

| Factor                 | Consideration                                            |
| ---------------------- | -------------------------------------------------------- |
| Complexity             | High – Complex UI interactions and large dataset.        |
| Uncertainty            | High – Performance with 3000+ markers, multiple filters. |
| Dependencies           | High – Clean dataset, map component, filter logic.       |
| Risk                   | High – Performance and UX issues under load.             |
| Estimated Story Points | **21**                                                   |

####  Rationale & Method

This was judged the most complex story. We compared it to the 13 SP login story and concluded it involves much more effort due to data parsing, filter UI, performance tuning, and logic for debounced search/filtering.We conducted a **relative estimation** using team discussion. A spike was done to evaluate the load time of 3000+ tree entries. Based on that, we **voted via Planning Poker** and converged on **21 SP**.

---

##  Sprint Backlog Tasks

| User Story ID | Task ID  | Task Description                                                                                                                                              | Owner   | Status      | Est. Effort (SP) |
| ------------- | -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------- | ----------- | ---------------- |
| US 01         | US1_T9  | Use Open Street Map.                                                                                                                                          | Yixiang | Not Started | 8                |
|               | US1_T10 | High-fidelity UI design for the map interface.                                                                                                                | Yitong  | Not Started |                  |
|               | US1_T11 | Implement high-fidelity UI design for the map interface.                                                                                                      | Xin     | Not Started |                  |
|               | US1_T12 | Change the small map to a bigger map.                                                                                                                         | Yixiang | Not Started |                  |
| US 03         | US3_T11 | Create or modify the login page to ensure access control and error prompt functionality.                                                                      | Yuqi    | Completed   | 13               |
|               | US3_T12 | Implement login detection and redirection logic (add simple code in functions.php).                                                                           | Yuqi    | Completed   |                  |
| US 04         | US4_T1  | Implement search function based on input location and distance (default Melbourne Connect, 1km).                                                              | Yixiang | Not Started | 21               |
|               | US4_T2  | Implement a feature to list the 10 nearest results below the map after a search. The page should display a list of nearby search results and include details. | Yixiang | Not Started |                  |
|               | US4_T3  | Load data for 3000 trees on a new page and display markers based on categories.                                                                               | Zixian  | Not Started |                  |
|               | US4_T4  | Implement category filtering functionality supporting up to three filters. Exclude trees with missing "tree age description".                                 | Yixiang | Not Started |                  |
|               | US4_T5  | Color markers based on species category using consistent color schemes. Map must use kilometers as unit.                                                      | Zixian  | Not Started |                  |
|               | US4_T6  | Set default location to Lincoln Square, 1km distance, default category to "Park + Ficus species."                                                             | Yixiang | Not Started |                  |

---

##  Commitment

The team commits to:

- Completing the SSO login and session system.
- Finalizing and testing the interactive map interface.
- Implementing search and filter features that allow users to locate suitable meetup locations based on detailed environmental data.

