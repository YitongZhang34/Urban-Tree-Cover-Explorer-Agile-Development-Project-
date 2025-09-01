# Sprint Planning (Sprint 1) - Assignment 2

## Sprint Goal
To develop the MVP features for Urban Tree Explorer including:
- An interactive map displaying tree-rich meetup locations
- Recommended locations for PhD meetups with contextual data
- A secure login system using UniMelb credentials with 2FA


---

## Selected User Stories

### US01 – Explore Tree-Based Meetup Locations from teaching team end

**As a** member of the teaching team, **I want to** explore potential meetup locations on an interactive map using tree-based environmental data, **so that** I can evaluate and choose the most shaded, suitable spot for upcoming PhD meetups.

### Acceptance Criteria:
- The map loads the full environmental/tree dataset.
- Tree data is displayed as markers or clusters on the map.
- Users can zoom, pan, and interact with the map smoothly on both desktop and mobile.
- Clicking on a tree marker shows a pop-up with species, canopy size, and other relevant data.
- Filtering options are available for precinct and tree attributes.
- Map is implemented using Leaflet or Mapbox.


### Story Point Justification

| Estimation Factor | Consideration                                                         |
|-------------------|---------------------------------------------------------------|
| Complexity        | High – Spatial rendering and filtering on interactive map     |
| Uncertainty       | Medium – Dataset familiarity required                         |
| Dependencies      | Tree dataset, map rendering API                               |
| Risk              | Medium – Performance and responsiveness                       |
| Estimated SP      | **13**                                                         |

---

### US02 – Explore Tree-Based Meetup Locations from phd students end

**As a** PhD student attending an upcoming meetup, **I want to** view the chosen meetup location and its environmental details on a map, **so that** I can plan accordingly.

### Acceptance Criteria:

- Clicking a marker reveals the name, average tree shade, and suitability rating of that location （Other students’ preferred tree marker details are still TBD）.


### Story Point Justification

| Estimation Factor | Notes                                                                 |
|-------------------|-----------------------------------------------------------------------|
| Complexity        | Low – Similar structure and UI reuse from US01                       |
| Uncertainty       | Low – Locations and data are predefined                              |
| Dependencies      | Data and UI components shared with US01                              |
| Risk              | Low – Mostly UI rework and toggle options                            |
| Estimated SP      | **1**                                                                |

---

### US03 – Login with UniMelb Credentials + 2FA

**As a** UniMelb staff member or student, **I want to** log in using my credentials with 2FA **so that** I can securely access the Urban Tree Explorer.

### Acceptance Criteria:
- A "Login with UniMelb" button is clearly presented on the login page.
- On entering credentials, users are prompted for Two-Factor Authentication (2FA) via Okta.
- Upon successful 2FA, users are redirected to their appropriate role-based homepage.
- Autofill is supported for login fields (not visibly shown).
- All errors (invalid login, failed 2FA, session issues) are gracefully handled.
- Login session is securely stored using appropriate token mechanisms.


### Story Point Justification:

| Estimation Factor | Consideration                                                         |
|-------------------|---------------------------------------------------------------|
| Complexity        | High – SSO and 2FA integration with Okta                      |
| Uncertainty       | Medium – Depends on access to University identity resources   |
| Dependencies      | Okta, UniMelb SSO                                             |
| Risk              | High – Security and external system dependence                |
| Estimated SP      | **12**                                                         |

---

---

## Sprint Backlog Tasks

| User Story | Task ID               | Task Description | Owner | Estimated Hours |
|---------|----------------|------------------|-------|-----------------|
| US01/02 | US01/02_T1 | Import and parse urban tree dataset. | Yixiang | 3h |
|  | US01/02_T2 | Integrate and configure map library on WordPress. | Xin | 3h |
|  | US01/02_T3 | Plot tree locations on map using markers or clusters. | Yitong | 4h |
|  | US01/02_T4 | Implement heatmap or density visualization overlay for tree-rich areas. | Yuqi | 7h |
|  | US01/02_T5 | Enable interactive map behavior: zoom, pan, and responsive view. | Zixian | 4h |
|  | US01/02_T6 | Test map functionality with different dataset sizes for performance. | Yixiang | 7h |
|  | US01/02_T7 | Design UI + user interface. | Xin | 8h |
|  | US01/02_T8 | Design login UI. | Yitong | 8h |
| US03 | US03_T1 | Create 'Login with UniMelb' button on the login page. | Yitong | 4h |
|  | US03_T2 | Integrate UniMelb SSO with Okta (OAuth2/OpenID Connect). | Yuqi | 4h |
|  | US03_T3 | Implement Two-Factor Authentication (2FA) with Okta Verify. | Zixian | 5h |
|  | US03_T4 | Store and manage authenticated login sessions securely. | Yixiang | 4h |
|  | US03_T5 | Define user roles (Admin, Teaching Staff, Student). | Xin | 4h |
|  | US03_T6 | Implement role-based redirection after login. | Yitong | 5h |
|  | US03_T7 | Create placeholder/mock pages for each user role view. | Yuqi | 3h |
|  | US03_T8 | Test login flow across multiple browsers (Chrome, Firefox, Safari). | Zixian | 6h |
|  | US03_T9 | Handle error states: invalid credentials, rejected 2FA, session timeout. | Yixiang | 3h |
|  | US03_T10 | Coordinate with Uni IT to verify SSO/2FA access and callback setup. | Xin | 4h |

---


## Team Commitment
The team commits to delivering the selected stories within the 14-day Sprint window. The total story points committed for this Sprint is **26**. All user stories and tasks are documented in this Sprint Planning artefact.



