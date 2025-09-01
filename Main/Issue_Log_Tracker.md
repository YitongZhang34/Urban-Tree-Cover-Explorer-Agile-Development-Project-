# Project Issue Tracker - Assignment 2

This document tracks reported bugs, their fixes, and the resolution status. Maintaining a Defect Log ensures that issues are identified, addressed, and verified in a timely manner, supporting the overall quality of the project.

---

## **Defect Log Guidelines**

Each defect should be logged with the following details:
- **Date Reported**: When the defect was reported.
- **Defect ID**: Unique identifier for the defect.
- **Description**: A short description of the bug.
- **Severity**: Critical 🔴, High 🟠, Medium 🟡, Low 🟢
- **Reported By**: The person who reported the defect.
- **Status**: Open, In Progress, Resolved, Closed, etc.
- **Assigned To**: Developer responsible for fixing the defect.
- **Fix Implemented**: Description of the fix or solution.
- **Tested By**: Tester who verified the fix.
- **Test Date**: Date when the fix was tested.
- **Comments**: Any additional notes or issues related to the defect.

---

###  Defect Log

| Defect ID   | Date Reported   | Description                                                                                   | Severity   | Reported By       | Status                | Assigned To       | Fix Implemented                                                                                       | Tested By   | Test Date   | Comments                                                                                              |
|:------------|:----------------|:----------------------------------------------------------------------------------------------|:-----------|:------------------|:-----------------------|:------------------|:-----------------------------------------------------------------------------------------------------|:------------|:------------|:------------------------------------------------------------------------------------------------------|
| DEF-001     | 2025-04-10      | Dataset size too large; caused multiple import failures.                                      | Critical   | @xin              | ✅ Solved              | @xin              | Filtered and reduced data points for initial import.                                                  | @team       | 2025-04-11  | Import now works with reduced dataset.                                                                |
| DEF-002     | 2025-04-11      | 2FA plugin encountered compatibility issues in university's multi-site WordPress environment. | High       | @yuqi             | ⚠️  Deprioritised       | @team             | Client deprioritized the 2FA requirement due to plugin limitations.                                   | N/A         | 2025-04-15  | Requirement dropped for Sprint 1; no further action needed.                                           |
| DEF-003     | 2025-04-12      | 2FA Email Authentication Failure (Page Not Found)                                             | Medium     | @zixian           | Closed                 | @zixian           | Attempted to authenticate using 2FA via email but redirected to a missing page (404 error).           | @team       | 2025-04-15  | Requirement dropped for Project; no further action needed.                                            |
| DEF-004     | 2025-05-06      | Website performance dropped significantly after switching map API; pages load slowly.         | Medium     | @team             | ✅ Solved              | @team             | Deleted redundant uploaded datasets and oversized maps after consulting with IT services.             | @team       | 2025-05-08  | Performance issues caused by server overload resolved through data cleanup.                          |
| DEF-005     | 2025-05-07      | Category coloring caused dataset to overload and crash server when data size increased.       | High       | @yixiang/@zixian  | ✅ Solved              | @yixiang/@zixian  | Deleted redundant uploaded datasets and oversized maps after consulting with IT services.             | @team       | 2025-05-08  | Server now runs normally; issue traced to excessive file storage.                                     |
| DEF-006     | 2025-05-07      | Ambiguity in client requirement: whether to strictly limit display to 10 nearest trees.       | Low        | @team             | ✅ Solved              | N/A               | Confirmed requirement with client during Showcase; current implementation satisfies display rule.     | @team       | 2025-05-09  | No changes required; client happy with current implementation.                                        |
| DEF-007     | 2025-05-14      | Sprint 3 internal meeting delayed due to slow development progress.                           | Low        | @team             | Closed                 | @Scrum Master     | Meeting rescheduled from May 14 to May 16 to give developers more time.                               | N/A         | 2025-05-16  | Meeting completed successfully on May 16.                                                             |
| DEF-008     | 2025-05-15      | Redundant legacy code found in "Add Location" feature from Sprint 2.                          | Medium     | @haoxin           | ✅ Solved              | @haoxin / @zixian | Haoxin consulted Zixian, the original developer, and removed unnecessary code after discussion.        | @haoxin     | 2025-05-15  | Code now clean; progress resumed.                                                                     |
| DEF-009     | 2025-05-16      | Rating plugin only supports 1–5 scale; desired scale is 1–10.                                 | Low        | @haoxin           | ✅ Solved             | @haoxin           | Rating plugin works but lacks 1–10 support; further research ongoing to customize plugin settings.     | N/A         | N/A         | Fixed on 21st May                                                  |
| DEF-010     | 2025-05-16      | Path overlap makes direction unclear; map API lacks arrow rendering.                          | Medium     | @yixiang          | ✅ Solved              | @team             | Proposed two solutions: added step numbers to stops, and inserted invisible intermediate points.       | @team       | 2025-05-17  | Both strategies help distinguish direction; user test results pending.                                |
| DEF-011     | 2025-05-21      | Rating plugin failed to upload user-submitted data; caused blocking of US7_T3 and US8_T3.    | Medium     | @team             | ⚠️ Deprioritised | @xin / @zixian / @yixiang | After consulting Ed, rating-related backend features were deprioritised; only frontend retained.     | N/A         | N/A         | Deprioritisation occurred on May 23; Acceptance Criteria amended by PO; Story Points unchanged.     |
| DEF-012     | 2025-05-23      | Unable to turn on filtering function in WP Go Maps Pro plugin.                               | Medium     | @yixiang          | ✅ Solved              | @yixiang          | Identified plugin setting misconfiguration; adjusted layer control visibility settings in the plugin backend. | @team       | 2025-05-25  | Filtering now works as expected; feature verified during final testing.                               |
| DEF-013     | 2025-05-23      | User-submitted markers indistinguishable; server could not update new data fields properly.  | Medium     | @zixian           | ✅ Solved              | @zixian           | Adjust settings | @team       | 2025-05-25  | Fixed on 25th May |

---

### **Updates**

- **2025-05-08 Update**: After investigating DEF-004 and DEF-005 with the teaching team (on behalf of WordPress IT), we discovered our server was crashing due to oversized unused data (failed uploads and large map assets). We have now cleaned the server, and performance has returned to normal.

- **2025-05-09 Update**: After our Sprint Showcase with Rajesh, DEF-006 has been confirmed resolved. The implementation meets the requirement of displaying the 10 nearest trees with no further action needed.

- **2025-05-23 Update**: Following the 5/23 Ed discussion response, all rating-related backend integration tasks (DEF-011) were deprioritised due to plugin/server issues. Only frontend logic was retained, and Acceptance Criteria were amended by the PO.

## Defect Log Best Practices

Maintaining a high-quality defect log relies on consistently following these key practices:

### Immediate Documentation
Report defects as soon as they are discovered to ensure accurate, real-time tracking and avoid missing critical issues.

### Clear Severity Levels
Classify each defect based on its **impact on the system**, using consistent levels include:

- **Critical 🔴**: A defect that causes the system to crash or results in a complete failure of a critical feature, blocking the functionality entirely.
- **High 🟠**: A significant defect that affects core functionality but can be worked around temporarily, requiring a quick fix.
- **Medium 🟡**: A moderate defect that impacts non-critical functionality and may be deferred without immediate consequences.
- **Low 🟢**: A minor defect that has little to no impact on functionality, typically cosmetic or related to user interface improvements.

### Timely Resolution
Assign each defect to a responsible developer quickly, and monitor progress to ensure that fixes are implemented within reasonable timeframes.

### Testing and Verification
All fixes must be **verified by testers** before the issue is marked as resolved. Proper testing ensures the solution addresses the defect without introducing new bugs. Always document:

- The tester's name  
- The test date  
- Confirmation that the defect is no longer reproducible

