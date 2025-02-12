#### Software Requirement Specification

# 1. Introduction

The Mentor-Mentee Management System aims to facilitate structured mentorship by connecting mentors and mentees, enabling communication,
automating matching process, session scheduling, progress tracking, and administrative oversight for the program.

# 2. Scope

## 2.1. Scope of the project

- Admin Site: Saigonchildren staff (Admin) can manage users, mentors, mentees, sessions, and program settings.
- Portal for mentors and mentees: Users can view their profile, mentor/mentee profile, and session history.

## 2.2. Overview of the system

We have three main user roles in the system are `Admin`, `Mentor`, and `Mentee`.

Admin can manage users, mentors, mentees, sessions, and program settings. The Admin can make `CRUD` operations on the following entities: `Users` (Mentors and Mentees), `Matches` includes `Mentor-Mentee` pairs or `Group`, `Documents`.

Admin can create matching rules for mentors and mentees. Then admin can run the matching algorithm to match mentors and mentees based on the rules.

### 2.2.1 Matching in the system

The program is seasonal, and each season has a start date and an end date. After the season end, the account of mentors and mentees will be prevented from matching system (the user will be notified). The Admin can create a new season and continue the program. If the user wants to join the program, they need to register for the new season by updating their profile to make a request to join the program.

In one program season, `One mentor can be matched with many mentees`. `One mentee can be matched with one mentor`. We call a `Group` is a collection of one mentor and many mentees.
![A group collection of one mentor and many mentees](./assets/diagrams/group.png)

A `Match` is a collection of many groups.
![A match collection of many groups](./assets/diagrams/match.png)

# 3. Functional requirements

## 3.1 Core features

Below are the core features of the system:

![Feature breakdown](./assets/diagrams/feature_breakdown.png)

## 3.2 User interaction & System workflow

We have three main user roles in the system are `Admin`, `Mentor`, and `Mentee`.

Below is the use case diagram for the system:


# 4. System architecture & Design

# 4.1 High-Level architecture

# 4.2 Database Design

# 4.3 Component Diagram

# 4.4. Matching algorithm design

# 5. Non-functional requirements

# 6. Testing Requirements

# 7. Project timeline

| Phase | Start date | End date (Expect) |
| --- | --- | --- |
| Requirement gathering | 08/08/2024 | 30/11/2024 |
| Design and prototyping | 30/11/2024 | 10/02/2025 |
| Development | 08/02/2025 | 08/05/2025 |
| Testing | 10/05/2025 | 10/05/2025 |
| Deployment | 11/05/2025 | 11/06/2025 |


# 8. Revisions

| Version | Date | Description |
| --- | --- | --- |
| 0.0.1 | 12/02/2025 | Init documentation |
|  |  |  |

# 9. Appendices

# 9.1 Glossary

- Admin: Saigonchildren staff who manages the system.
- CRUD: Create, Read, Update, Delete operations.

# 10. Signatures

- Project owner: Saigonchildren

- Author: Tran Cong Toan - tctoan1024@gmail.com