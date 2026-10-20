# Tech Stack Evaluation

## Project
Cafeteria Ordering System – A web-based system that allows customers to browse and order food while cafeteria staff manage food items, orders and reports.

## Requirements that drive the decision
List 3 to 5 requirements from your own docs/requirements.md. Include at
least 2 non-functional requirements.
- [FR1]: The system shall authenticate customers and cafeteria staff by verifying their registered usernames and passwords during login.
- [FR2]: The system shall recommend food items to customers during the ordering process based on their selected preferences.
- [NFR3]: The system shall display the food-ordering page within 5 seconds after a user requests it.
- [NFR4]: The system shall allow customers to complete a food order within 5 minutes after logging in during usability testing.
- [NFR5]: The system shall preserve all confirmed order and payment records if the system is interrupted unexpectedly.

## Options
- Option A: Static website using HTML, CSS and JavaScript hosted on GitHub Pages.
- Option B: Java web application using JSP, Servlets and MySQL, developed with NetBeans and deployed on a compatible server.
- Option C: [your own idea]

## Decision matrix
Weight: how important the criterion is for YOUR project (1 = low, 5 = high).
Score: how well each option does (1 = poor, 5 = excellent).
Weighted score = weight x score. Add them up for each option.

| Criterion                          | Weight | A score | B score | C score |
|------------------------------------|--------|---------|---------|---------|
| Fits my requirements               |   5    |    2    |   5     |    5    |
| Skills I already have              |   4    |    5    |   5     |    2    |
| Time to build before my deadline   |   5    |    5    |   4     |    3    |
| Free hosting and tools             |   4    |    5    |   3     |    2    |
| Performance and security needs     |   5    |    3    |   4     |    2    |
| Room to grow later                 |   3    |    2    |   4     |    1    |
| **Total (weighted)**               |        |   96    |  109    |   69    |

## Decision record
- **Context:** The Cafeteria Ordering System needs to support food ordering and staff management. I have limited time and budget, so I need a technology that is affordable and easy to use.
- **Decision:** Option B – Java web application using JSP, Servlets and MySQL.
- **Reasons:**  It supports the main functional requirements and it matches my existing experience with Java, NetBeans, JSP and Servlets which can reduce development time.
- **Consequences:** Easy: Authentication, food ordering, database storage and order management.
Harder: Server configuration, debugging and AI chatbot integration.
- **Risks and next review:** The system may have bugs or database connection problems. I will review the technology after completing the main functions and testing the system.