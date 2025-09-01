### 📌 Acceptance Criteria for User Story: "As a user, I want to make an online parking reservation so that I can secure a parking spot in advance."  

✅ **Acceptance Criteria:**  
1. Users must be able to select a parking lot and reserve a spot.  
2. The system should prevent double booking of a reserved spot.  
3. A confirmation email should be sent after successful booking.  

### 📌 Test Case: Interactive Tree Map

| Test ID   | User Story                                             | Scenario (BDD Syntax)                                                                                                                                | Test Result    | Tested By   | Test Date   | Comments                                                               |
|:----------|:-------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------|:---------------|:------------|:------------|:-----------------------------------------------------------------------|
| TEST-201  | US01 - Teaching team: View tree-dense areas            | Given I am on the interactive map page, When I filter or browse tree-dense areas, Then I should see clusters or heatmaps showing ideal meetup spots. | ✅ Pass        | @team       | 2025-04-15  | Tree clustering and heatmap displayed correctly on desktop and mobile. |
| TEST-202  | US01 - Teaching team: View environmental data on click | Given I click on a marker, When the pop-up appears, Then I should see relevant environmental details like shade and tree age.                        | ✅ Pass        | @team       | 2025-04-15  | Pop-up shows formatted and complete data without overlap.              |
| TEST-203  | US02 - PhD student: View selected meetup location      | Given I view the highlighted meetup location, When I click on it, Then I should see summary details like tree type and shade score.                  | ✅ Pass        | @team       | 2025-04-15  | Student view loads correctly with minimal data displayed.              |
| TEST-204  | Login UI Sketch                                        | Given I open the login page, When I view the design, Then it should reflect the UniMelb brand and offer space for SSO button.                        | ✅ Pass        | @team       | 2025-04-14  | Design is ready but waiting on client feedback before implementation.  |

---

## 📌 **Ongoing QA Tracking**

| Test ID   | Feature                                  | Status         | Last Updated   |
|:----------|:-----------------------------------------|:---------------|:---------------|
| TEST-201  | Interactive Tree Map – Cluster & Heatmap | ✅ Pass        | 2025-04-15     |
| TEST-202  | Interactive Tree Map – Tree Pop-Up Info  | ✅ Pass        | 2025-04-15     |
| TEST-203  | Interactive Tree Map – Student View      | ✅ Pass        | 2025-04-15     |
| TEST-204  | Login UI Sketch                          | ✅ Pass    | 2025-04-14     |

---

## 📌 **Definition of Done (DoD) for Each Sprint**  

A feature is considered **Done** only when:  
1. All test cases for the feature pass successfully.  
2. The feature meets its **Acceptance Criteria**.  
3. Bugs identified in the sprint are **fixed and retested**.  
4. The deliverable is **approved in Sprint Review**.  

By following this structured **QA Strategy**, we ensure that each sprint delivers a **fully functional and thoroughly tested feature**, adhering to Scrum best practices. ✅  
