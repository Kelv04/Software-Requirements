## Change Log

| Change ID | Description of Change                                                    | Date      | Author       | Reason                                                            |
| --------- | ------------------------------------------------------------------------ | --------- | ------------ | ----------------------------------------------------------------- |
| CH-01     | Added 2FA for admin login                                                | 15/6/2025 | Kelven Yee   | Security concern: No MFA requirement detected during validation   |
| CH-02     | Replaced SQLite with PostgreSQL or justified prototype use               | 15/6/2025 | Kelven Yee   | Scalability issue: SQLite not suitable for production scale       |
| CH-03     | Removed or merged duplicate communication requirement                    | 15/6/2025 | Shazreen     | Documentation defect: REQ_C1 & REQ_C3 were identical              |
| CH-04     | Replaced OAuth with campus SSO login                                     | 15/6/2025 | Kelven Yee   | Agreement defect: OAuth violated campus security policy           |
| CH-05     | Listed explicit OS versions (iOS 17–14, Android 14–11)                   | 16/6/2025 | Ow Ka Sheng  | Content defect: Requirement was vague and lacked specificity      |
| CH-06     | Specified device width ranges for responsive design                      | 16/6/2025 | Ow Ka Sheng  | Content defect: “Responsive design” lacked breakpoint definitions |
| CH-07     | Added WCAG contrast compliance                                           | 19/6/2025 | Koh Xuan Lin | Accessibility issue: Color codes not accessible                   |
| CH-08     | Reduced refresh rate to 10s for feasibility                              | 20/6/2025 | Koh Xuan Lin | Agreement defect: 5s refresh rate was technically infeasible      |
| CH-09     | Backend optimization for faster reservation                              | 20/6/2025 | Koh Xuan Lin | Performance defect: Reservation delay > 2s                        |
| CH-10     | Added Register Vehicle in Use Case Diagram                               | 21/6/2025 | Ow Ka Sheng  | Content defect: Missing functionality in UML                      |
| CH-11     | Standardized to “university student information system (SIS)” throughout | 21/6/2025 | Ow Ka Sheng  | Documentation defect: Inconsistent terminology                    |
| CH-12     | Defined “Notification” in Use Case Diagram and DB Schema                 | 22/6/2025 | Ow Ka Sheng  | Content enhancement: Modeled user reminders for profile updates   |
