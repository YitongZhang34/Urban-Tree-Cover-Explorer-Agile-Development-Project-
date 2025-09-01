### 📌 **Acceptance Criteria for Interactive Map:** *"As a member of the teaching team, I want to explore potential meetup locations on an interactive map using tree-based environmental data."*

### 📌 **Acceptance Criteria for Login:** *"As a University of Melbourne staff member or student, I want to log in to the Urban Tree Explorer using my UniMelb credentials."*

### 📌 **Acceptance Criteria for Search & Filter:** *"As a user (teaching staff or student) browsing the interactive map, I want to search and filter trees based on attributes like species, location, canopy size, and useful life expectancy."*

✅ Acceptance Criteria:

1. The application uses Open Street Map instead of other mapping APIs.
2. The map interface follows a high-fidelity UI design based on visual standards. Elements such as legends, buttons, and filters are visually aligned and consistent and without confusion.
3. The map is implemented with the spirit of UI design and easy to use.
4. The map should occupy a larger area of the page (minimum width: 80% of screen or as per UI design).
5. The login page is modified to include: (1) authentication logic, (2) error prompts for incorrect login.
6. Code added to `functions.php` detects whether a user is logged in. If not logged in, the user is redirected to the login page when trying to access restricted pages.
7. A search function: (1) allows input of a location, (2) allows distance input (default to Melbourne Connect, 1km), (3) correctly returns results within the radius.
8. After a search, the 10 nearest results are listed below the map, including relevant details (e.g., species, age, location). The list is dynamic and updates based on the search.
9. The map loads data for 3000 trees and places category-based markers on the map.
10. A filter is available to select 1, 2, or 3 categories (e.g., tree age, species, location). Trees with missing “tree age description” are excluded when this filter is active.
11. Markers are colored by species: same species = same color; different species = different color, for 10 most frequent genuses.
12. When the search starts: (1) default location is Lincoln Square, (2) default distance is 1km, (3) default category is “Park + Ficus species.” These defaults are reflected in search/filter forms.

### **📌 Test Case**

| Test ID  | User Story                                                   | Scenario (BDD Syntax)                                        | Test Result | Tested By | Test Date  | Comments                                                     |
| -------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------- | --------- | ---------- | ------------------------------------------------------------ |
| TEST-205 | As a member of the teaching team, I want to explore potential meetup locations on an interactive map using tree-based environmental data, so that I can evaluate and choose the most shaded, suitable spot for upcoming PhD meetups. | Given I am logged in and viewing the interactive map page,   When I click on a tree marker,   Then I should see detailed environmental data and location information to help me select a suitable meetup spot. | In Progress | Team      | 2025-05-01 | Tree markers are clickable and show environmental data, but trees are not correctly colored. |
| TEST-206 | As a University of Melbourne staff member or student, I want to log in to the Urban Tree Explorer using my UniMelb credentials with Okta-based 2-Factor Authentication, so that I can securely access the platform using a familiar and trusted login method. | Given I am on the login page,   When I enter my UniMelb credentials,   Then I should be redirected to the homepage with access to all protected features of the Urban Tree Explorer. | Pass        | Team      | 2025-05-08 | Login redirects correctly after UniMelb credentials verification. No errors encountered during authentication. |
| TEST-207 | As a user (teaching staff or student) browsing the interactive map, I want to search and filter trees based on attributes like species, location, canopy size, and useful life expectancy, so that I can refine my exploration options and find shaded meetup areas. | Given I am viewing the map interface with filter options available,   When I select specific attributes such as tree species, canopy size, and useful life expectancy,   Then the map should update to display only trees that match my selected criteria and exclude those that don't. | Pass        | Team      | 2025-05-09 | Filtering options display correct results based on multiple attributes. Trees without age data are excluded as expected. Performance is stable under filter combinations. |

### **📌 Ongoing QA Tracking**  

| **Test ID** | **Feature**          | **Status**    | **Last Updated** |
| ----------- | -------------------- | ------------- | ---------------- |
| TEST-205    | Interactive Tree Map | ✅ Pass        | 2025-05-01       |
| TEST-206    | Login                | ✅ Pass        | 2025-05-08       |
| TEST-207    | Search and Filtering | 🔄 In Progress | 2025-05-09       |

### **📌 Definition of Done (DoD)** 

**Interactive Map:**

1. OpenStreetMap is integrated and functional as the base layer.
2. A finalized, high-fidelity map design is available in the UI.
3. UI design is implemented to match approved visual mockups.
4. The interactive map is larger by default and enhances usability.
5. Features pass accessibility, performance, and usability checks.
6. Tested across screen sizes and devices for layout stability.

**Login:**

1. UniMelb SSO login is integrated and functional.
2. Error handling and validation for failed login attempts are implemented.
3. Successful login redirects the user to the intended page.
4. Login session is securely managed.
5. Functionality is tested with both valid and invalid credentials.
6. Login detection is handled in backend logic (e.g., functions.php).
7. Login/logout flow is consistent with user expectations.

**Search & Filter:**

1. Location-based search is implemented with adjustable distance radius.
2. Nearby results display correctly and responsively.
3. Up to 3000 categorized markers load smoothly.
4. Filtering supports multiple category combinations.
5. Marker color and units follow standards.
6. Default settings match spec.
7. UI performs well with large datasets.
8. Final behavior is verified with user testing.
