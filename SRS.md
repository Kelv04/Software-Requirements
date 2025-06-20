# 3.8 Supporting Information

## 3.8.1 Validation Session

| Session ID | Date and Time     | Technique  | Section Reviewed | Participant & Role | No. of Defects |
|------------|-------------------|------------|------------------|-------------------|----------------|
| VS01 | 17/6/2025 5:00pm  | Inspection | 3.1-3.8 | Kelven (Author), Koh Xuan Lin (Inspector), Ow Ka Sheng (Inspector), Shazreen (Moderator) | 11 |
| VS02 | 19/6/2025 11:00pm | Inspection | 3.2, 3.4, 3.5 | Kelven (Moderator), Koh Xuan Lin (Author)  Ow Ka Sheng (Presenter), Shazreen (Inspector) | 4 |

> **Note:** Compulsory to conduct Inspection technique. Students may conduct additional technique(s).

## 3.8.2 Defect Summary

### A. Content Defect

| Req ID | Validation and Defect Description | Detected By | Comment/Suggested Fix | Session ID | Severity (1–5) |
|--------|-----------------------------------|-------------|----------------------|------------|----------------|
| REQ_R1 | No MFA requirement for admin login | Kelven | Add 2FA for admin login | VS01 | 5 |
| REQ_C3 | Duplicate of REQ_C1 | Koh Xuan Lin | Remove REQ_C3 | VS01 | 3 |
| REQ_GUI | Color codes not accessible | Ow Ka Sheng  | Add WCAG-compliant contrast options | VS02 | 2 |
| REQ_S1 | SQLite unsuitable for high concurrency; may crash during peak hour | Kelven | Migrate to PostgreSQL with connection pooling | VS02| 5 | 

### B. Documentation Defect

| Page No. | Validation and Defect Description | Detected By | Comment/Suggested Fix | Session ID | Severity (1–5) |
|----------|-----------------------------------|-------------|----------------------|------------|----------------|
| 2 & 3 | Outdated Table of Content | Ow Ka Sheng | Update Table of Content | VS01 | 5 |
| 16 | Missing user accessibility notes | Koh Xuan Lin | Add WCAG 2.1 compliance section | VS02 | 2 |
| 31 | Word "matching" spelled wrong | Kelven | Correct the word | VS01 | 1 |
| 39 | Inconsistent capitalization | Kelven | Capitalize the word | VS01 | 1 |
| 55 | Word "incomplete" Spelled Wrong| Koh Xuan Lin | Correct the word | VS02 | 1 |
| 56 | Sequence Diagram without label | Shazreen | Added label | VS01 | 2 |
| 57 | Inconsistent punctuation | Ow Ka Sheng | Fix the punctuation | VS01 | 1 |
| 71 | Word "departure" spelled wrong | Kelven | Correct the word | VS01 | 1 |
| 76 | Word "labelled" spelled wrong | Shazreen | Correct the word | VS01 | 1 |

### C. Agreement Defect

| Req ID | Validation Description/Stakeholder Concern | Mismatch | Detected By | Session ID | Severity (1–5) |
|--------|---------------------------------------------|----------|-------------|------------|----------------|
| REQ_S3 | Social login not aligned with campus security policy | OAUTH vs SSO requirement | Kelven | VS01 | 5 |
| REQ_P4 | Staff can change parking anytime | Over-flexibility | Koh Xuan Lin | VS01 | 4 |

## 3.8.3 Conflict Analysis

| Conflict ID | Conflict Description | Conflict Analysis | Stakeholders Involved | Session ID |
|-------------|---------------------|-------------------|----------------------|------------|
| C01 | OAuth login vs campus SSO-only policy | Campus policy prohibits OAuth; needs secure SSO | Dev Team, IT Admin | VS01 |
| C02 | Staff can change parking anytime | System abuse | Staff | VS01 |
| C03 | Performance vs Accessibility | Developers want speed; UX team wants full WCAG compliance | Dev Team, UX, QA | VS02 |

## 3.8.4 Conflict Resolution

| Conflict ID | Conflict Resolution Strategy | Resolved (Y/N) | Outcome (If Resolved) | Justification |
|-------------|------------------------------|----------------|----------------------|---------------|
| C01 | Replace OAuth with campus SSO login | Y | Compliant with campus policy | IT standards enforced |
| C02 | Add 1 change-per-day | Y | Fair control policy | Balance user need |
| C03 | Prioritized accessibility for core features | Y | WCAG compliance added to login and dashboard | Balanced usability with performance trade-offs |

## 3.8.5 Change Log

*Summarized from the full change log maintained in changelog.md on GitHub*

| Change ID | Req ID | Summary of Change | Proposed By | Date | Session ID |
|-----------|--------|-------------------|-------------|------|------------|
| CH01 | REQ_R1 | Added 2FA for admin login | Kelven | 17/6/2025 | VS01 |
| CH02 | REQ_GUI1 | Added WCAG contrast compliance | Koh Xuan Lin | 19/6/2025 | VS02 |
| CH03 | REQ_S1 | Migrate from SQLite to PostgreSQL database | Kelven | 19/6/2025 | VS02

## 3.8.6 Requirements Traceability Matrix

| Req ID | Requirement Description | Linked Goal(s) | Feature(s) | Use Case(s) | Traceability Score (1-4) |
|--------|------------------------|----------------|------------|-------------|-------------------------|
| REQ_GUI2 | Dashboard layout | G2 | F1 | UC-02 | 3 |

## 3.8.7 Role in Requirements Validation, Negotiation & Management

| Student Name | Primary Responsibility | No. of Session Participated |
|--------------|------------------------|----------------------------|
| Kelven Kai Wen | *To be completed* | *To be completed* |
| Koh Xuan Lin | *To be completed* | *To be completed* |
| Ow Ka Sheng | *To be completed* | *To be completed* |
| Shazreen Binti Sheridan | *To be completed* | *To be completed* |

> **Note:** Students may participate in multiple roles across sessions.

## 3.8.8 Version Control & Configuration Summary

> **Note:** Provide the summary here.

### Commit Summary by Team Member

- **Commits Made by Kelven:** *To be completed*
- **Commits Made by Koh Xuan Lin:** *To be completed*
- **Commits Made by Ow Ka Sheng:** *To be completed*
- **Commits Made by Shazreen:** *To be completed*

### Additional Metrics

- **Pull Requests Merged by StudentX:** *To be completed*
- **Change Log Entries Made by StudentX:** *To be completed*
