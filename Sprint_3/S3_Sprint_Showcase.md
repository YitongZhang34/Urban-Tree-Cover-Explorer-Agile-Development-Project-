# Sprint Showcase - Assignment 2

- Document your Sprint Showcase for Assignment 2.  
- Refer to Showcase_Example_and_Guide.md under the Guides folder for guidance on how to document this section. An example is shown.
- You can reuse formatting and sections from the guidance for documenting this section
---
# Sprint Showcase – Urban Tree Explorer (Park Explorer Map + Walking Itinerary)

## Industry Practices
| Step                            | Common in Industry? | Notes                                                                 |
|---------------------------------|---------------------|-----------------------------------------------------------------------|
| Team Check-in                   | ✅ Yes              | Team briefly aligned progress before showcasing to Rajesh.           |
| Overview of Accomplished & Postponed Items | ✅ Yes              | Shared completed features and explained delays on partial items.      |
| Demo & Q&A                      | ✅ Yes              | Demo conducted during Dr. Rajesh’s consultation hour on 21 May.       |
| Product Backlog & Future Tasks | ✅ Yes              | Discussed pending features and feedback-driven revisions.             |
| Capacity, Budget & Roadblocks  | ⚠️ Sometimes        | Progress delays due to rating upload bug and academic workload.       |
| Energy Check & Wrap-Up         | ❌ Rare             | Not formally conducted.                                               |

---

## Sprint Showcase Outcomes for Urban Tree Explorer 

| **Category**           | **Details** |
|------------------------|-------------|
| **Sprint Goal**        | Enhance the platform’s value by allowing users to explore park locations and share their own ratings and insights, while also showcasing a green walking itinerary with foliage heatmaps and directional markers across Melbourne CBD. |
| **Completed Features** | - Allowed users to rate parks from 1–10. <br> - Enabled users to add custom markers with tags, images, and descriptions. <br> - Displayed detailed information (3+ photos and descriptions) for key parks. <br> - Designed UI for both Park Explorer and Walking Itinerary pages.  <br> - Showed walking itinerary directions. <br> - Displayed tree heatmap around the walking route using dataset. <br> - Full integration of 3000-tree dataset for itinerary heatmap.|
| **Postponed Features** | - Displaying average park rating (US7_T3) delayed due to a backend bug in the rating upload logic. <br> - Toggling visibility of user-submitted markers (US7_T5) in progress. <br> - Embedding YouTube videos for selected parks (US7_T7) not completed due to integration issues.<br> - Enabled rating for each stopdue to a backend bug in the rating upload logic.  |
| **Demo Summary**       | - Conducted during Dr. Rajesh’s consultation hour on **21 May 2025**. <br> - Demonstrated all completed features listed above. <br> - Postponed features were explained with clear reasons. |
| **Stakeholder Feedback** | - Add names to itinerary points (currently numbered only). <br> - Enlarge the walking itinerary map display area. <br> - Avoid using test files during demos. |
| **Action Items**       | - Replace numeric-only itinerary stops with labeled names. <br> - Adjust page layout to highlight itinerary map more prominently. <br> - Remove test content and demo using final datasets. <br> - Fix rating upload bug to enable average rating and dataset display. <br> - Continue integrating video content and toggle filters for user-submitted content. |

---
## Sprint Showcase Demon Screenshots for Urban Tree Explorer – At the end of the sprint (on 25th May) - All features completed

1. Implement an interactive map on a separate new page that allows users to visualize park locations in the City of Melbourne near Melbourne Connect. This will help PhD students to know information about the park locations nearby.
* You can use a dataset which includes parks in the City of Melbourne. It should include parks and places of interest near Melbourne Connect and around the CBD. It doesn't matter if not every single park/place is included.
<img width="1769" alt="c8aed931c7996076f1aea47755a086d" src="https://github.com/user-attachments/assets/1bb693df-2693-47d6-9ed1-16b5ec7f3550" />
<img width="1747" alt="ccf29a6dc074bdf02524631fdcdc08d" src="https://github.com/user-attachments/assets/9f2cc6d1-8811-4ce4-84b4-07534755673a" />
<img width="1748" alt="dddf78ec67f521210d7e34afcca718b" src="https://github.com/user-attachments/assets/7276c571-2cdb-4d04-8c60-6500214ce423" />

* Users should be able to submit their own rating of any park on a 1-10 point scale. They should be able to see the average rating as well.  Written reviews aren't needed.
![447327854-f1e08954-2df5-41f8-9ec2-f35dc2fd5953](https://github.com/user-attachments/assets/3d28da60-45c9-4a1d-8136-6fa95a8e0c16)

* Users should be able to submit new markers for locations, including new Parks, or Places of Interest they think would be useful information to other users. The user should be able to tag the category, upload a photo/image of the location, and provide a written description of the location. User should be able to add markers directly without moderation.
<img width="732" alt="333218046dbbf40c42f03de6304b0e8" src="https://github.com/user-attachments/assets/892aa10f-ea9f-41bc-adb0-3cdb2437a190" />
<img width="1680" alt="ae225e6f25203b11bb63f5f8ca2f967" src="https://github.com/user-attachments/assets/d25faf2e-2b7e-485d-8698-0e69bf6ad014" />
* It should be possible to filter the markers on the map to either show or not show the user submitted markers.

![447329176-12a290fa-f0b5-4d7f-a651-59811eba28fd](https://github.com/user-attachments/assets/94c7aab3-1b4a-4607-b4ac-249d6c0e00ed)
![447329165-31434985-0486-410c-8e86-50f7e7c1b1d0](https://github.com/user-attachments/assets/5ff40d48-1365-4d1c-bf93-c139f6f38fae)

* There should be detailed information available for the following specific locations, including at least 3 photos for each location and a description of each location. These places should be readily identifiable on the map compared to other parks.(University Square；Lincoln Square；Argyle Square；Carlton Gardens)
<img width="1698" alt="d3edda09e6d0f25bd06f6e1cd9379e1" src="https://github.com/user-attachments/assets/9841e695-662f-4ed5-8dce-f022754825da" />
<img width="1702" alt="bd4ca35f352f28d4d45a065ed81c9fc" src="https://github.com/user-attachments/assets/e9582976-b076-464f-b899-35a91a1b0e0e" />
<img width="1703" alt="c23598e58f9890e7577d4d0cbaf7c8a" src="https://github.com/user-attachments/assets/037cc0cc-68f8-4905-a983-c76f1c049425" />
<img width="1698" alt="e21222d7b6016d8da6a339764c3d7cc" src="https://github.com/user-attachments/assets/51fbab5c-5b12-400f-8ac6-21e8f68ce4e4" />
* The client also wants embedded YouTube videos demonstrating at least two of the locations (not all are needed). Any public video on YouTube that shows the location appropriately is ok.
<img width="1703" alt="c23598e58f9890e7577d4d0cbaf7c8a" src="https://github.com/user-attachments/assets/5e2b4431-aed3-42ee-88d6-ecc75cf3784d" />
<img width="1702" alt="bd4ca35f352f28d4d45a065ed81c9fc" src="https://github.com/user-attachments/assets/7fb97068-6610-4a74-a56e-5eb425d58a1c" />
2.  Implement an interactive map on a separate new page that allows users to visualise a pre-determined walking itinerary where PhD students will be able to enjoy different aspects around Melbourne CBD and learn about the city. 

![447328334-11869367-67d7-415b-a774-11d09e2f4a49](https://github.com/user-attachments/assets/1f1bec45-6ec7-43fd-82a6-e7e4bbac6b7f)
![447328347-ef7b463b-c3d9-4c12-a98c-1d1d5af07269](https://github.com/user-attachments/assets/4034c9e7-7d5d-4a23-91b0-9ae3b7ef5f1c)


* The locations in order are University of Melbourne Old Quad, Lincoln Square, State Library of Victoria, Melbourne Central, Federation Square, State Parliament Building, Treasury Gardens, Cook's Cottage, Model Tudor Village, Carlton Gardens, Melbourne Connect.
* When the map loads there should be directions showing the itinerary.
* The walking itinerary must be shown as markers, not a heatmap.
* use a dataset of 3000 tree data
* The map must show tree locations. The tree locations around the walking itinerary path must be shown as a heatmap (instead of individual markers) to allow the user to see how much foliage they will encounter during their walk.
* The heatmap should be something like this around the walking area.
![447328421-0b0dc4a2-9010-497e-a462-70ee2419fafa](https://github.com/user-attachments/assets/1e98aa85-5fb4-4ab1-9964-d1c5816b90a0)

* Users must be able to rate each stop along the way.
![447329214-5c7e6582-3462-4a0d-913b-e4ae9038f8f1](https://github.com/user-attachments/assets/ce526aaf-cefd-4326-826a-6a678588a794)


  
