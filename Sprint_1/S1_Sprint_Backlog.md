# Sprint 1 Backlog - Assignment 2

## Overview  

A **Sprint Backlog** is a subset of the Product Backlog that contains user stories selected for a sprint. It includes detailed tasks, owners, effort estimates, and daily tracking to monitor progress toward the sprint goal.

### Key Elements of a Sprint Backlog

- **User Story ID (US#):** Cross-links to the User Story ID in the Product Backlog for traceability.  
- **User Story:** A structured feature description selected for the sprint.  
- **Tasks:** Subtasks needed to complete the user story. Each task has a unique ID (e.g., `US1_T1`).  
- **Owner:** Team member responsible for completing the task.  
- **Status:** Task progress (e.g., *Not Started, In Progress, Completed*).  
- **Estimated Effort (SP):** Total story points assigned to the user story.  
- **Daily Progress Tracking (Day 1 - Day 14):** The remaining effort for the user story as tasks are completed.

## Example: Sprint Backlog for Smart Parking System (Sprint 1)  

| User Story ID | User Story                                                   | Task ID    | Task Description                                             | Owner       | Status      | Est. Effort (SP) | Day 1 | Day 2 | Day 3 | Day 4 | Day 5 | Day 6 | Day 7 | Day 8 | Day 9 | Day 10 | Day 11 | Day 12 | Day 13 | Day 14 |
| ------------- | ------------------------------------------------------------ | ---------- | ------------------------------------------------------------ | ----------- | ----------- | ---------------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ------ | ------ | ------ | ------ | ------ |
| US01/02       | As a member of the teaching team, I want to explore potential meetup locations on an interactive map using tree-based environmental data, so that I can evaluate and choose the most shaded, suitable spot for upcoming PhD meetups. | US01/02_T1 | Import and parse urban tree datasets                         | Xin         | In Progress | 3                |  2.5     |   2    |   1.5    |    1   | 0      |       |       |       |       |        |        |        |        |        |
|               |                                                              | US01/02_T2 | Integrate and configure map library on WordPress             | Yuqi        | Not Started | 2                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US01/02_T3 | Plot tree locations on map using markers or clusters         | Xin,Yixiang | In Progress | 5                |     4  |   4    |   3    |    0   |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US01/02_T4 | Implement heatmap or density visualization overlay           | Yixiang     | Not Started | 2                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US01/02_T5 | Enable interactive map behavior: zoom, pan, and responsive view | Yixiang     | Not Started | 8                |   6    |   4    |    0   |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US01/02_T6 | Test map functionality with different dataset sizes for performance | All         | Not Started | 5                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US01/02_T7 | Design UI + user interface                                   | Yitong      | In Progress | 5                |     4  |   3    |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US01/02_T8 | Design login UI                                              | Yitong      | In Progress | 3                |     1  |    1   |       |       |       |       |       |       |       |        |        |        |        |        |
| US03          | As a University of Melbourne staff member or student, I want to log in to the Urban Tree Explorer using my UniMelb credentials with Okta-based 2-Factor Authentication, so that I can securely access the platform using a familiar and trusted login method. | US03_T1    | Create 'Login with UniMelb' button on the login page         | Yuqi        | Not Started | 5                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US03_T2    | Integrate UniMelb SSO with Okta (OAuth2/OpenID Connect)      |             |             | 1                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US03_T3    | Implement Two-Factor Authentication email and text message   | Zixian      | Not Started | 8                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US03_T4    | Store and manage authenticated login sessions securely       | Zixian      | Not Started | 5                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US03_T5    | Define user roles (Admin, Teaching Staff, Student)           | Yuqi        | Not Started | 2                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US03_T6    | Implement role-based redirection after login                 | Zixian      | Not Started | 3                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US03_T7    | Create placeholder/mock pages for each user role view        | Yitong      | Not Started | 3                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US03_T8    | Test login flow across multiple browsers (Chrome, Firefox, Safari) | All         | Not Started | 5                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US03_T9    | Handle error states: invalid credentials, rejected 2FA, session timeout | Yuqi        | Not Started | 5                |       |       |       |       |       |       |       |       |       |        |        |        |        |        |
|               |                                                              | US03_T10   | Coordinate with Uni IT to verify SSO/2FA access and callback setup |             |             |                 |       |       |       |       |       |       |       |       |       |        |        |        |        |        |

**Note:** The effort burns down collectively per **user story** across the sprint, ensuring all related tasks are completed before the story reaches complete.

## Guidelines for Updating the Sprint Backlog

1. **Effort Burn-Down:** Story points **burn down collectively** per user story.
2. **Tracking Progress:** The burn-down chart should reflect decreasing effort over time.
3. **Definition of Done:** A user story is only complete when all tasks meet the **Definition of Done (DoD)**.

## Final Notes

- Keep updates consistent for accurate tracking.
- Ensure dependencies are managed to avoid bottlenecks.
- The **burn-down chart should reflect actual progress** and guide sprint planning.
