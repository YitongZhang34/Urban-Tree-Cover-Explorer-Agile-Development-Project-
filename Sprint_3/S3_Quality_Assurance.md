# Quality Assurance - Assignment 2

### 📌 **Acceptance Criteria for Park Explorer Map:**  
*"As a user, I want to view an interactive map with park locations, ratings, and user contributions so that I can explore and engage with nearby places of interest."*

✅ **Acceptance Criteria:**

- **[AC7-1]** Given the user opens the Park Explorer map page, When the map loads, Then it must show markers for parks around Melbourne Connect and the CBD, including highlighted markers for University Square, Lincoln Square, Argle Square, and Carlton Gardens with 3+ photos and a description.
- **[AC7-2]** Given the user clicks on a park marker, When they submit a rating from 1–10, Then they should see a rating input interface (e.g., 1–10 scale) for each listed tree.  
  *(Note: rating is implemented on frontend only due to server/backend limitations — deprioritised on 23rd May)*
- **[AC7-3]**  Given the map contains both default and user-submitted markers, When the user clicks the filter toggle for user-submitted content, Then only the selected type of markers (default/user-submitted) should be displayed.  
- **[AC7-4]** Given the user clicks “Add a New Place,” When they fill in category, upload image(s), and write a short description, Then the new marker should appear immediately on the map without requiring moderation.
- **[AC7-5]** Given the user clicks on a key location (e.g., Lincoln Square), When a video is available, Then an embedded YouTube video should be visible within the location's info popup.
- **[AC7-6]** Given the map is initialized using a dataset of parks in the City of Melbourne, When the map is displayed to the user, Then it must include parks and places of interest near Melbourne Connect and within the CBD.

---

### 📌 **Acceptance Criteria for Walking Itinerary Map:**  
*"As a user, I want to view a visualised walking route with park and landmark ratings and tree foliage density, so that I can plan a pleasant and green city walk."*

- **[AC8-1]** Given the user opens the Walking Itinerary page, When the map loads, Then it must display the 11 predefined locations in the correct order as a connected walking route with directional markers, starting from University of Melbourne Old Quad and ending at Melbourne Connect.
- **[AC8-2]** Given the user clicks on a waypoint marker along the walking itinerary map, When they plan to rate the location, Then they should see a rating input interface (e.g., 1–10 scale) for each location.  
  *(Note: Frontend only — average rating functionality deprioritised due to backend bug on 23rd May)*
- **[AC8-3]** Given the user views the walking itinerary map, When the tree dataset is loaded, Then a foliage density heatmap should be overlaid on the map, and it must be visually distinct from the walking itinerary path.

---

### 📌 **Test Case**

| Test ID  | User Story | Scenario (BDD Syntax) | Test Result | Tested By | Test Date | Comments |
| -------- | ---------- | ---------------------- | ----------- | --------- | --------- | -------- |
| TEST-701 | [US07] Park Explorer Map | Given the user opens the Park Explorer map page, When the map loads, Then it must show designated park markers with media. | ✅ Pass | QA Engineer: Haoxin | 05-25 | - |
| TEST-702 |  | **Amended on 23rd May:** Given the user clicks on a park marker, When they submit a rating, Then the rating interface should appear. *(Frontend only)* | ✅ Pass | QA Engineer: Haoxin | 05-25 | 23rd May: Backend functionality no need to be implemented |
| TEST-703 |  | Given the map contains both default and user-submitted markers, When the filter is toggled, Then only the selected type is shown. | ✅ Pass | QA Engineer: Haoxin | 05-25 | - |
| TEST-704 |  | Given the user adds a new location, When submission completes, Then a new marker appears on the map immediately. | ✅ Pass | QA Engineer:Haoxin | 05-25 | - |
| TEST-705 |  | Given the user clicks a key location, When video is available, Then an embedded YouTube video is visible. | ✅ Pass | QA Engineer: Haoxin | 05-25 | Responsive and non-autoplay verified |
| TEST-706 |  | Given the dataset is loaded, Then all relevant Melbourne parks must be shown. | ✅ Pass | QA Engineer: Haoxin | 05-25 | - |
| TEST-801 | [US08] Walking Itinerary Map | Given the user opens the itinerary page, When the map loads, Then 11 connected route markers must be visible. | ✅ Pass | QA Engineer: Haoxin | 05-20 | Route direction validated |
| TEST-802 |  |  **Amended on 23rd May:** Given the user selects a location, When rating, Then the interface appears for each waypoint. *(Frontend only)* | ✅ Pass | QA Engineer: Haoxin | 05-20 | 23rd May Backend functionality no need to be implemented  |
| TEST-803 |  | Given the map loads, Then a foliage heatmap is overlaid and visually distinct from route markers. | ✅ Pass | QA Engineer: Haoxin| 05-20 | - |

---

### 📌 **Ongoing QA Tracking**

| Test ID | Feature | Status | Last Updated |
|---------|---------|--------|---------------|
| TEST-701 | Park markers display with media | ✅ Pass | 05-25 |
| TEST-702 | Rate Parks and show average. <br> Updated on 23rd May: Park rating input interface (frontend only) | ✅ Pass | 05-25 |
| TEST-703 | Marker filter toggle | ✅ Pass | 05-25 |
| TEST-704 | User-submitted place markers | ✅ Pass | 05-25 |
| TEST-705 | Embedded videos in info popup | ✅ Pass | 05-25 |
| TEST-706 | Park dataset rendering | ✅ Pass | 05-25 |
| TEST-801 | 11-point walking itinerary with direction | ✅ Pass | 05-20 |
| TEST-802 | Rate waypoints and show average. <br> Updated on 23rd May: Rating interface for waypoints (frontend only) | ✅ Pass | 05-20 |
| TEST-803 | Foliage heatmap display | ✅ Pass | 05-20 |

---

### 📌 **Definition of Done (DoD)**

**Park Explorer Map:**

 - Map displays designated parks and places of interest.
 - Users can submit ratings (frontend) and new places with metadata.
 - Embedded video support and filter toggles are available. 

**Walking Itinerary Map:**

- Map loads the correct itinerary in order.
- Shows directional connections.
- Supports rating submissions (frontend) at each stop.
- Overlays a visually distinct foliage heatmap.
