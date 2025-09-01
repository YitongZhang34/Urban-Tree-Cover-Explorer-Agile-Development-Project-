# Sprint Showcase - Assignment 2

- Document your Sprint Showcase for Assignment 2.  
- Refer to Showcase_Example_and_Guide.md under the Guides folder for guidance on how to document this section. An example is shown.
- You can reuse formatting and sections from the guidance for documenting this section

# Sprint Showcase – Urban Tree Explorer (Search & Filter Map + Login)

## Industry Practices
| Step                            | Common in Industry? | Notes                                                                 |
|---------------------------------|---------------------|-----------------------------------------------------------------------|
| Team Check-in                   | ✅ Yes              | Regular alignment before presenting progress.                         |
| Overview of Accomplished & Postponed Items | ✅ Yes              | Key to tracking progress and setting up next sprint.                  |
| Demo & Q&A                      | ✅ Yes              | Conducted successfully with Dr. Rajesh.                              |
| Product Backlog & Future Tasks | ✅ Yes              | Future colour coding features and polish tasks discussed.             |
| Capacity, Budget & Roadblocks  | ⚠️ Sometimes        | Technical constraints around filtering logic and category display.     |
| Energy Check & Wrap-Up         | ❌ Rare             | Not formally conducted.                                               |

---

## Sprint Showcase Outcomes for Urban Tree Explorer – Search & Filter Map + Login

| **Category**           | **Details** |
|------------------------|-------------|
| **Sprint Goal**        | Enable secure platform access via UniMelb SSO and empower users to explore and filter tree-based meetup locations through an interactive, accessible map interface. |
| **Completed Features** | - Implemented location-based interactive tree map with distance filter (default: Melbourne Connect, 1km). <br> - Displayed 10 nearest trees below map after search, with basic info. <br> - Implemented category-based filtering using "Located In", "Genus", and "Age Description" (default: Lincoln Square, Park + Ficus, no default Age). <br> - Enabled combined filter logic (1–3 categories). <br> - Built login page with credential validation and redirection logic for unauthenticated access.  |
| **Postponed Features** |【Due to the extension of the sprint duration, all prosponed features recorded on 10th May have already completed on 13th May】<br> - Colour differentiation by Genus (distinct colour per Genus; same Genus = same colour) postponed due to time constraints. |
| **Demo Summary**       | - Sprint 2 showcase conducted with Dr. Rajesh on 10 May 2025. <br> - Demonstrated tree location search, category filtering, and nearest tree list. <br> - Walked through login workflow and redirection behavior. |
| **Stakeholder Feedback** | - Single-page implementation (two features combined) is acceptable. <br> - Suggested using ColorBrewer2 for category colour palette (color-blind friendly). <br> - Trees outside top 10 categories should share one unified colour. <br> - All tree icons should be visually consistent (use same icon for all). <br> - Suggested making the current map center point visible after search or on load. <br> - Optional enhancements: Add search autocomplete, case-insensitivity, and spelling correction. <br> - Confirmed: 10 nearest trees and login redirection logic fully meet expectations. |
| **Action Items**       | 【Due to the extension of the sprint duration, all action items have already completed on 13th May】- Integrate Genus-based colour coding (next sprint). <br> - Adjust map icons to use a consistent symbol for all trees. <br> - Add visual indicator for current map center. <br> - Explore enhancements for location search UX (autocomplete, case tolerance, typo correction). <br> - Apply ColorBrewer2 palette to category colours for better accessibility. |

---

## Screenshots 
**We combined web page 1 and web page 2 as listed in the requirement, after the showcase, our clients agreed that we don't need to seperate those two pages.**
- Overview of the default page: ![image](https://github.com/user-attachments/assets/f5e98e8c-a627-49f5-8185-38407aaec4de)![image](https://github.com/user-attachments/assets/4585f65e-6d38-44c0-9304-97ea151556d2)![image](https://github.com/user-attachments/assets/23ec1f1a-1306-4759-8102-3bbb101ec16a)![image](https://github.com/user-attachments/assets/da34106f-6b6a-4862-8e54-5780af2d1c75)
---
**1. Implement an interactive map on a separate new page that allows users to visualize urban tree data within a given distance of a location provided by the user. Clicking on a marker shows tree details.**
A.The map recorded around 3000 entries of trees.![image](https://github.com/user-attachments/assets/d2c8c6fb-ea33-4bbb-9e55-6071fe148780)
B.The map use kilometer units, the default location is Melbourne Connect, and the default distance is 1 km![image](https://github.com/user-attachments/assets/bed879a6-9daf-4a21-918a-00e58dc758fc)
C. After a search, the page show a list of nearby results![image](https://github.com/user-attachments/assets/76f94bbd-011b-49d9-8f20-f3b875e24e06)
D. Including some details about each result (choose suitable data to show). This can be limited to show the nearest 10 closest results.![image](https://github.com/user-attachments/assets/d1f86ccc-b5b1-4003-a63f-0aa02a43e644)

---
**2. Implement an interactive map on a separate new page that allows users to visualize data based on specific, defined categories. Clicking on a marker shows tree details.**
A.The map recorded around 3000 entries of trees.![image](https://github.com/user-attachments/assets/d2c8c6fb-ea33-4bbb-9e55-6071fe148780)
B.The categories must be (i) 'Located in' e.g. Park or Street, (ii) 'Genus' e.g. Acacia, (iii) 'Age Description' e.g. Semi-Mature. ![image](https://github.com/user-attachments/assets/3cf3096a-a4c2-4996-b985-bd8b4c91b9c0)![image](https://github.com/user-attachments/assets/964d9316-a3a1-4dd5-9fcd-62f0a63eff5d)![image](https://github.com/user-attachments/assets/26daadfd-8a21-47cf-9a74-f2781143fef1)
C.The user must be able to visualize trees based on any combination of any one, two, or three categories.![image](https://github.com/user-attachments/assets/d3c9c909-8b90-4eae-942f-7f9528a47b10)

D.The default location must be Lincoln Square (near Melbourne University), and the default distance must be 1km. Other default values must be Park and Ficus. There is no default Age Description.![image](https://github.com/user-attachments/assets/b6d806af-8df0-4903-8522-10360b2a4216)![image](https://github.com/user-attachments/assets/da198db6-45ce-435b-9267-bbd68079f444)
E.Trees of different Genus must be different colours, trees of the same Genus must be the same colour. The map must use kilometer units.![image](https://github.com/user-attachments/assets/be7bdc32-f945-422d-ab19-0893efd520fa)

---
**3.Implement a login page, in a manner that redirects the user to login when trying to access any part of the website when not logged in.**
A. Login Page_Default (compulsaory redirect when not logged in)![image](https://github.com/user-attachments/assets/24ca21ff-9bb2-4532-9de7-78b0d623d900)
(When test on different browser)![image](https://github.com/user-attachments/assets/906275ce-f3d7-4609-9f0b-e8a22f3fe410)
B. Login Page_Wrong Password![image](https://github.com/user-attachments/assets/242253cb-ca0b-4818-a3c7-ed864f4bada1)
---





