---
name: User Story 🕺🏻
about: Write an excellent user story via this standard template
title: '[Feature Name] - [User Story Title]'
labels: user story
type: Story
assignees: ''
---
# [User Story Title]

**As a** [type of user],
**I want** [an action],
**so that** [a benefit/a value].

## Acceptance Criteria

1. [First criterion]
2. [Second criterion]
3. [Third criterion]

## Designs

- Link to Figma design 1
- Link to Figma design 2

## ERD

- Link to ERD

- Relevant tables: [enter cropped image]
- Table Name - [TABLE NAME]

| Column Name | Data Type   | Constraints                 | Description                     |
| ----------- | ----------- | --------------------------- | ------------------------------- |
| user_id     | INT         | PRIMARY KEY, AUTO_INCREMENT | Unique identifier for each user |
| username    | VARCHAR(50) | NOT NULL, UNIQUE            | Username chosen by the user     |
| created_at  | TIMESTAMP   | DEFAULT CURRENT_TIMESTAMP   | Timestamp of account creation   |

## Permissions

- [Check user roles attribute 'screen' has value = "applicant_profile" with Authorization level=1, if not then show message: "אין הרשאה למסך" ]
- [Create role attribute 'action' ]

## Quantitative Metrics

- [Metric 1: e.g., Registration completion rate should be at least 90%]
- [Metric 2: e.g., Average time to complete registration should be less than 2 minutes]
- [Metric 3: e.g., Email verification rate should be at least 85%]

## Notes

- [Any additional notes or context]
