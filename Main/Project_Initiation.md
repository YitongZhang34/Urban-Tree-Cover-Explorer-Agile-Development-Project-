# Project_Initiation

## Project Assumptions & Constraints - Urban Tree Cover Explorer

## Project Background

**Project Name:** Urban Tree Cover Explorer

**Course:** SWEN90016 Software Programming Management

**Development Team:** SWEN90016 Student Team

**Project Duration:** 6 weeks (starting April 2025)

**Project Objective:** This project aims to develop an online platform using open datasets provided by the City of Melbourne to help SWEN90016 select suitable outdoor locations with tree cover for informal PhD students gatherings. The platform may be expanded for environmental sustainability awareness, urban green space research, or spatial data analysis applications in the future.

## Assumptions

### 1. Data Availability:

- The dataset provided by The City of Melbourne is open-sourced and available, with a syntax that is compatible with WordPress.
- The dataset includes enough detail information, such as tree species, plant date, age and location, to support the function of the application.

### 2. User Access:

- The platform is only open to the tutors, teachers and PhD students of SWEN90016 teaching team, without public access.
- The user needs to register for an account to use the application.

### 3. Technical support:

- The IT infrastructure provided by the University of Melbourne (like the server and the storage) is sufficient for the deployment of the project.
- The pre-installed WordPress can meet the development needs.

### 4. Requirement Adjustment:

- The requirement of the project may be adjusted during the development process, which will be specified in the following sprints.

## Constraints

### 1. Time Constraints:

- **Constraint:** The project must deliver a Minimum Viable Product (MVP) within 3 sprints in 6 weeks, the team can invest 100-150 hours in the project. The sprint outcomes are pre-determined and cannot be adjusted dynamically.
- **Justification:** Do sprint planning ahead in details. The team must focus on MVP and follow the timeboxing strictly to avoid scope creep and ensure on-time delivery of essential features.

### 2. Resource Constraints:

- **Constraint:**
  - The developing team consists of students enrolled in SWEN90016 class, with different levels of programming skills.
  - The teaching team and the tutor have limit consult sessions, thus cannot give feedback and discuss requirements frequently.
- **Justification:**
  - Students must seek feedback and clarification of requirements proactively to refine requirements. The backlog needs to be organized and refined frequently and regularly to ensure efficient communication during the consult sessions.
  - Knowledge-sharing and peer programming techniques, such as pair programming, should be implemented to increase efficiency and ensure progress.

### 3. Technical Constraints:

- **Constraint:** The project depends on the functionality of WordPress and its plugins. If the plugins have limitations, future function modification and expansion can be affected.
- **Justification:** The team members must evaluate the effectiveness of the used plugins and be prepared to adjust the way of implementation. Early testing and iterative development can reduce risk and save time for adjustments.

### 4. Budget Constraints:

- **Constraint:** The project does not require extra budget because all resources is provided by the university. No licensing costs or third-party dependencies. All functions must based on opensource tools or free resources.
- **Justification:** Follow the rules of Lean Development, and use as much available resources as possible without extra cost. It can promote the efficiency of development by taking advantage of open-source and free resources.

### 5. Regulatory Constraints:

- **Constraint:**
  - The project must follow the University of Melbourne's Data Privacy Policy. No personal information about any user is stored or disclosed. Two-factor authentication (2FA) needs to be implemented for secure user access.
  - The terms of use of Melbourne City Council Open Data must be followed. The data provided cannot be used for unauthorized commercial purposes.
- **Justification:** Reach a consensus on data usage and sign a confidentiality agreement agreed upon by all team members. Implement 2FA early and address it proactively to reduce potential rework.

## Minimum Viable Product (MVP)

### 1. Interactive Tree Map :

A visual map displaying Melbourne's tree coverage, utilizing open-source data. It allows users to see the distribution of trees across the city.

- A WordPress page displaying an interactive map with tree markers.
- Clicking on a marker shows tree details.
- Implementation of two-factor authentication (2FA) for secure user access.
- The system is ready for further enhancements in Sprints 2 & 3.
- Completed checklists in Git for the Scrum SDLC artefacts.

### 2. Login System （updated on 28th April when Sprint 2 requirements released）

Enables secure access to the platform using University of Melbourne credentials.

- Single Sign-On (SSO) authentication via UniMelb system.
- Ensures identity validation for user-specific features (e.g., marker submission, rating).
- User login session persists across pages.
- Error-handling and fallback behavior are implemented for login failures.

### 3. Search and Filter （updated on 28th April when Sprint 2 requirements released）

Allow users to locate trees using flexible search and filtering:

- Location-based search with adjustable radius.
- Filter by species, canopy size, and life expectancy.
- Debounced search/filter input for smoother experience.
- Optimized performance with large datasets and responsive design.
- Frontend-verified marker color and unit standards applied.

### 4. Park Explorer Map（updated on 12th May when Sprint 3 requirements released）

Enable users to explore key parks and contribute their own:

- Interactive map showing parks near Melbourne Connect and the CBD.
- Key locations (e.g., Lincoln Square, Carlton Gardens) have enhanced popups with photos and descriptions.
- Users can submit ratings (1–10 scale) and view average rating. **Amended on 23th May**: Only front-end rating submission interface required, average rating requirement was deprioritised.
- Support for uploading new markers with media and descriptions.
- Toggle to switch between default and user-submitted markers.
- Embedded YouTube video support for highlighted locations.

### 5. Walking Itinerary Map updated on 12th May when Sprint 3 requirements released）

Display a fixed walking route across 11 urban spots with natural highlights:

- Visualized route from UniMelb Old Quad to Melbourne Connect with directional indicators.
- Overlay foliage heatmap for environmental context.
- Waypoints accept user ratings and show average rating.**Amended on 23th May**: Only front-end rating submission interface required, average rating requirement was deprioritised.
- Ensures distinct visual layering between routes and heatmap.

---

## Potential Post-MVP Enhancements (if time permits)

- **UI/UX Optimization:** Improve animations, layout spacing, and interactivity cues.
- **Performance Scaling:** Add caching, API throttling, and large-data optimizations.
- **Accessibility Enhancements:** Introduce ARIA tags, keyboard navigation, and contrast settings.
