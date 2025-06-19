# 3.8 Supporting Information

## 3.8.1 Validation Session

| Session ID | Date and Time | Technique | Section Reviewed | Participant & Role | No. of Defects |
|------------|---------------|-----------|------------------|-------------------|----------------|
| VS01 | 17/6/2025 5:00pm | Inspection | Section 3.1-3.8 | Kelven (Inspector), Koh Xuan Lin (Inspector), Ow Ka Sheng (Author), Shazreen (Moderator) | 11 |

> **Note:** Compulsory to conduct Inspection technique. Students may conduct additional technique(s).

## 3.8.2 Defect Summary

### A. Content Defect

| Req ID | Validation and Defect Description | Detected By | Comment/Suggested Fix | Session ID | Severity (1–5) |
|--------|-----------------------------------|-------------|----------------------|------------|----------------|
| REQ_R1 | No MFA requirement for admin login | Kelven | Add 2FA for admin login | VS01 | 5 |
| REQ_C3 | Duplicate of REQ_C1 | Koh Xuan Lin | Remove REQ_C3 | VS01 | 3 |

### B. Documentation Defect

| Page No. | Validation and Defect Description | Detected By | Comment/Suggested Fix | Session ID | Severity (1–5) |
|----------|-----------------------------------|-------------|----------------------|------------|----------------|
| 2 & 3 | Outdated Table of Content | Ow Ka Sheng | Update Table of Content | VS01 | 5 |
| 31 | Word matching Spelled Wrong | Kelven | Correct the word | VS01 | 1 |
| 39 | Inconsistent Capitalization | Kelven | Capitalize the word | VS01 | 1 |
| 56 | Sequence Diagram Without Label | Shazreen | Added label | VS01 | 2 |
| 57 | Inconsistent Punctuation | Ow Ka Shen | Fix the punctuation | VS01 | 1 |
| 71 | Word Departure Spelled Wrong | Kelven | Correct the word | VS01 | 1 |
| 76 | Word labelled Spelled Wrong | Shazreen | Correct the word | VS01 | 1 |

### C. Agreement Defect

| Req ID | Validation Description/Stakeholder Concern | Mismatch | Detected By | Session ID | Severity (1–5) |
|--------|---------------------------------------------|----------|-------------|------------|----------------|
| REQ_S3 | Social login not aligned with campus security policy | OAUTH vs SSO requirement | Kelven | VS01 | 5 |
| REQ_P4 | Staff can change parking anytime | Over-flexibility | Xuan Lin | VS01 | 4 |

## 3.8.3 Conflict Analysis

| Conflict ID | Conflict Description | Conflict Analysis | Stakeholders Involved | Session ID |
|-------------|---------------------|-------------------|----------------------|------------|
| C01 | OAuth login vs campus SSO-only policy | Campus policy prohibits OAuth; needs secure SSO | Dev Team, IT Admin | VS01 |
| C02 | Staff can change parking anytime | System abuse | Staff | VS01 |

## 3.8.4 Conflict Resolution

| Conflict ID | Conflict Resolution Strategy | Resolved (Y/N) | Outcome (If Resolved) | Justification |
|-------------|------------------------------|----------------|----------------------|---------------|
| C01 | Replace OAuth with campus SSO login | Y | Compliant with campus policy | IT standards enforced |
| C02 | Add 1 change-per-day | Y | Fair control policy | Balance user need |

## 3.8.5 Change Log

*Summarized from the full change log maintained in changelog.md on GitHub*

| Change ID | Req ID | Summary of Change | Proposed By | Date | Session ID |
|-----------|--------|-------------------|-------------|------|------------|
| CH01 | REQ_R1 | Added 2FA for admin login | Kelven | 17/6/2025 | VS01 |

## 3.8.6 Requirements Traceability Matrix

| Req ID | Requirement Description | Linked Goal(s) | Feature(s) | Use Case(s) | Traceability Score (1-4) |
|--------|------------------------|----------------|------------|-------------|-------------------------|
| *To be completed* | | | | | |

## 3.8.7 Role in Requirements Validation, Negotiation & Management

| Student Name | Primary Responsibility | No. of Session Participated |
|--------------|------------------------|----------------------------|
| Kelven Yee Kai Wen | *To be completed* | *To be completed* |
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
