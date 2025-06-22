## Change Log

| Change ID | Description of Change                                                    | Date      | Author       | Reason                                                            |
| --------- | ------------------------------------------------------------------------ | --------- | ------------ | ----------------------------------------------------------------- |
| CH-01     | Added 2FA for admin login                                                | 15/6/2025 | Kelven Yee   | Security concern: No MFA requirement detected during validation   |
| CH-02     | Replaced SQLite with PostgreSQL or justified prototype use               | 15/6/2025 | Kelven Yee   | Scalability issue: SQLite not suitable for production scale       |
| CH-03     | Removed or merged duplicate communication requirement                    | 15/6/2025 | Shazreen     | Documentation defect: REQ_C1 & REQ_C3 were identical              |
| CH-04     | Replaced OAuth with campus SSO login                                     | 15/6/2025 | Kelven Yee   | Agreement defect: OAuth violated campus security policy           |
| CH-05     | Listed explicit OS versions (iOS 17–14, Android 14–11)                   | 16/6/2025 | Ow Ka Sheng  | Content defect: Requirement was vague and lacked specificity      |
| CH-06     | Specified device width ranges for responsive design                      | 16/6/2025 | Ow Ka Sheng  | Content defect: "Responsive design" lacked breakpoint definitions |
| CH-07     | Added WCAG contrast compliance                                           | 19/6/2025 | Koh Xuan Lin | Accessibility issue: Color codes not accessible                   |
| CH-08     | Reduced refresh rate to 10s for feasibility                              | 20/6/2025 | Koh Xuan Lin | Agreement defect: 5s refresh rate was technically infeasible      |
| CH-09     | Backend optimization for faster reservation                              | 20/6/2025 | Koh Xuan Lin | Performance defect: Reservation delay > 2s                        |
| CH-10     | Replaced OAuth with campus SSO login                                     | 15/6/2025 | Kelven Yee   | Agreement defect: Social login not aligned with campus security policy |
| CH-11     | Reduced refresh rate to 10s for feasibility                             | 20/6/2025 | Koh Xuan Lin | Agreement defect: 5s refresh rate not feasible                    |
| CH-12     | Added one-change-per-day rule with admin override for staff parking     | 15/6/2025 | Ow Ka Sheng  | Agreement defect: Staff parking changes vs admin control preference |
| CH-13     | Added Register Vehicle in Use Case Diagram                               | 18/6/2025 | Ow Ka Sheng  | Content defect: Missing functionality in UML diagram              |
| CH-14     | Added scalability requirement for 500+ concurrent users                 | 18/6/2025 | Shazreen     | Content defect: Scalability not mentioned for peak traffic        |
| CH-15     | Defined notification system in use cases, sequence diagrams, and ERD    | 18/6/2025 | Ow Ka Sheng  | Content defect: Notification system not defined                   |
| CH-16     | Added vehicle_type column to Vehicle table in DB schema                  | 18/6/2025 | Kelven Yee   | Content defect: Vehicle table lacks vehicle type field            |
| CH-17     | Fixed manual spacing and inconsistent paragraph formatting (pages 1-89)  | 15/6/2025 | Kelven Yee   | Documentation defect: Layout instability from manual line breaks  |
| CH-18     | Updated outdated Table of Content with latest information               | 15/6/2025 | Shazreen     | Documentation defect: TOC contained outdated page references       |
| CH-19     | Standardized paragraph and heading spacing throughout document           | 15/6/2025 | Ow Ka Sheng  | Documentation defect: Inconsistent content spacing                |
| CH-20     | Corrected "staffs" to "staff" throughout document                       | 17/6/2025 | Shazreen     | Documentation defect: Incorrect plural form usage                 |
| CH-21     | Fixed heading spacing for Table 1.3.3 User Characteristics              | 15/6/2025 | Ow Ka Sheng  | Documentation defect: Inconsistent heading indentation            |
| CH-22     | Added WCAG 2.1 compliance notes for user accessibility                  | 19/6/2025 | Koh Xuan Lin | Documentation defect: Missing user accessibility requirements      |
| CH-23     | Fixed typo "mathing" to "matching" in Route and Time Selection          | 17/6/2025 | Kelven Yee   | Documentation defect: Spelling error in Effect of Parameter       |
| CH-24     | Fixed inconsistent capitalization in functional requirements             | 17/6/2025 | Shazreen     | Documentation defect: Mixed case usage throughout document         |
| CH-25     | Fixed duplicate Figure 3.1.8 numbering                                  | 19/6/2025 | Ow Ka Sheng  | Documentation defect: Figure numbered twice causing confusion      |
| CH-26     | Fixed typo "Imcomplete" to "Incomplete" in Profile Completeness         | 17/6/2025 | Kelven Yee   | Documentation defect: Spelling error in Effect of Parameter       |
| CH-27     | Added label "Figure 3.1.13 Sequence Diagram for Admin Manage Users"     | 17/6/2025 | Shazreen     | Documentation defect: Sequence diagram missing proper label        |
| CH-28     | Fixed inconsistent punctuation in Response Abnormal Situation           | 17/6/2025 | Shazreen     | Documentation defect: Punctuation errors in system monitoring     |
| CH-29     | Updated performance metrics to current benchmarks                       | 20/6/2025 | Koh Xuan Lin | Documentation defect: Outdated performance metric values          |
| CH-30     | Fixed typo "Deaparture_Time" to "Departure_Time" in Carpool table       | 20/6/2025 | Koh Xuan Lin | Documentation defect: Spelling error in database schema           |
| CH-31     | Standardized heading formatting across subsections 3.6.1-3.6.3          | 15/6/2025 | Ow Ka Sheng  | Documentation defect: Inconsistent spacing in design constraints  |
| CH-32     | Standardized to "university student information system (SIS)" throughout | 19/6/2025 | Ow Ka Sheng  | Documentation defect: Inconsistent terminology usage              |
| CH-33     | Replaced OAuth with campus SSO login                                    | 15/6/2025 | Kelven Yee   | Conflict resolution CF_01: OAuth login vs campus SSO-only policy  |
| CH-34     | Added one-change-per-day rule with admin override for staff parking     | 15/6/2025 | Multiple     | Conflict resolution CF_02: Staff parking changes vs admin restrictions |
| CH-35     | Created UI wireframes for desktop dashboard & mobile interface          | 16/6/2025 | Multiple     | Conflict resolution CF_03: UI lacks mobile mockups               |
| CH-36     | Required insurance upload for drivers                                    | 17/6/2025 | Multiple     | Conflict resolution CF_04: Missing insurance validation           |
| CH-37     | Added user account deletion feature for PDPA/GDPR compliance             | 18/6/2025 | Multiple     | Conflict resolution CF_05: Account deletion not possible          |
| CH-38     | Added opt-out toggle for GPS tracking with consent model                | 18/6/2025 | Multiple     | Conflict resolution CF_06: GPS tracking without opt-out          |
| CH-39     | Specified scalability requirement (support 500+ concurrent users)       | 18/6/2025 | Multiple     | Conflict resolution CF_07: Scalability unclear                   |
| CH-40     | Included notification system in SRS                                     | 18/6/2025 | Multiple     | Conflict resolution CF_08: Notification system missing           |
| CH-41     | Added vehicle_type field in registration & DB schema                    | 18/6/2025 | Multiple     | Conflict resolution CF_09: Vehicle info lacks vehicle type       |
| CH-42     | Implemented parking availability check & reservation control             | 19/6/2025 | Multiple     | Conflict resolution CF_10: Staff parking without availability check |
| CH-43     | Implemented daily reservation quotas for staff (2 slots/day)             | 19/6/2025 | Multiple     | Conflict resolution CF_11: Parking reservation limits unclear     |
| CH-44     | Prioritized accessibility for core features with WCAG compliance        | 19/6/2025 | Multiple     | Conflict resolution CF_12: Performance vs Accessibility balance   |
| CH-45     | Backend optimization + caching, reduced refresh rate to 10s             | 20/6/2025 | Multiple     | Conflict resolution CF_13: Real-time vs system load              |