# Requirements

## Purpose

This document defines the business, functional and non-functional requirements identified for the Student Support Management System case study.

The requirements have been derived from the business problem, business objectives, stakeholder analysis and simulated elicitation findings.

## Requirement Priorities

The following priority levels are used:

- **Must Have** – Essential for the solution to address the main business problem.
- **Should Have** – Important and provides significant business value, but the solution could operate without it initially.
- **Could Have** – Useful additional functionality that can be considered if time and resources allow.

---

## Business Requirements

| ID | Business Requirement | Priority |
|---|---|---|
| BR-001 | CLI must have a consistent process for capturing and managing student support requests. | Must Have |
| BR-002 | CLI must be able to assign support requests to the appropriate staff member. | Must Have |
| BR-003 | CLI must be able to monitor the status and progress of student support requests. | Must Have |
| BR-004 | CLI must be able to identify outstanding and overdue support requests. | Must Have |
| BR-005 | CLI must improve management visibility of support activity and workload. | Should Have |
| BR-006 | CLI must reduce unnecessary manual administration associated with managing support requests. | Should Have |
| BR-007 | CLI must provide reliable information that can support management reporting and decision-making. | Should Have |

---

## Functional Requirements

Functional requirements describe what the proposed system or process must be able to do.

### Request Capture

| ID | Functional Requirement | Priority |
|---|---|---|
| FR-001 | The system must allow an authorised user to create a student support request. | Must Have |
| FR-002 | The system must generate a unique reference number for each support request. | Must Have |
| FR-003 | The system must record the date and time that a support request is created. | Must Have |
| FR-004 | The system must allow a support request to be categorised. | Must Have |
| FR-005 | The system must allow the request description and relevant supporting information to be recorded. | Must Have |

### Request Assignment

| ID | Functional Requirement | Priority |
|---|---|---|
| FR-006 | The system must allow a support request to be assigned to an appropriate support staff member. | Must Have |
| FR-007 | The system must record the staff member responsible for an assigned request. | Must Have |
| FR-008 | The system should allow an authorised user to reassign a request when necessary. | Should Have |

### Request Status

| ID | Functional Requirement | Priority |
|---|---|---|
| FR-009 | The system must allow authorised users to update the status of a support request. | Must Have |
| FR-010 | The system must display the current status of each support request. | Must Have |
| FR-011 | The system should record relevant status changes for tracking purposes. | Should Have |
| FR-012 | The system must allow a request to be marked as resolved or closed. | Must Have |

### Prioritisation and Overdue Requests

| ID | Functional Requirement | Priority |
|---|---|---|
| FR-013 | The system must allow support requests to be assigned a priority level. | Must Have |
| FR-014 | The system should identify requests that have exceeded the expected response timeframe. | Should Have |
| FR-015 | The system should allow support staff to view outstanding requests requiring attention. | Should Have |

### Student Communication

| ID | Functional Requirement | Priority |
|---|---|---|
| FR-016 | The system should allow students to view the status of their support requests. | Should Have |
| FR-017 | The system should provide confirmation when a student support request has been successfully submitted. | Should Have |
| FR-018 | The system should allow relevant updates to be communicated to the student. | Should Have |

### Search and Reporting

| ID | Functional Requirement | Priority |
|---|---|---|
| FR-019 | The system must allow authorised users to search for support requests using relevant information such as request reference, category or status. | Must Have |
| FR-020 | The system should allow managers to view outstanding and overdue requests. | Should Have |
| FR-021 | The system should provide information that can be used to generate management reports. | Should Have |
| FR-022 | The system could provide summary information about request volumes, categories and resolution times. | Could Have |

---

## Non-Functional Requirements

Non-functional requirements describe the qualities and conditions that the solution must meet.

### Security

| ID | Non-Functional Requirement | Priority |
|---|---|---|
| NFR-001 | The system must restrict access to authorised users. | Must Have |
| NFR-002 | The system must ensure that users can only access information appropriate to their role. | Must Have |
| NFR-003 | Sensitive student information must be protected from unauthorised access. | Must Have |

### Performance

| ID | Non-Functional Requirement | Priority |
|---|---|---|
| NFR-004 | The system should respond to normal user actions within an acceptable timeframe under expected usage conditions. | Should Have |
| NFR-005 | Search results should be displayed within an acceptable timeframe when users search for support requests. | Should Have |

### Availability and Reliability

| ID | Non-Functional Requirement | Priority |
|---|---|---|
| NFR-006 | The system should be available during the Student Support Department's normal operating hours. | Should Have |
| NFR-007 | The system should maintain accurate request information and minimise data loss. | Must Have |

### Usability

| ID | Non-Functional Requirement | Priority |
|---|---|---|
| NFR-008 | The system should provide a clear and easy-to-understand interface for authorised users. | Should Have |
| NFR-009 | Request information should be presented in a consistent format. | Should Have |

### Maintainability

| ID | Non-Functional Requirement | Priority |
|---|---|---|
| NFR-010 | The solution should be maintainable so that authorised technical staff can support and update it when required. | Should Have |

---

## Requirement Traceability

The requirements are connected to the original business problem and objectives.

| Requirement Area | Business Problem Addressed | Related Objective |
|---|---|---|
| Request Capture | Inconsistent and manual recording | Centralise and standardise request capture |
| Request Assignment | Unclear responsibility | Assign requests to appropriate staff |
| Status Tracking | Limited visibility of request progress | Track requests from submission to resolution |
| Prioritisation | Difficulty identifying urgent requests | Improve request management |
| Overdue Monitoring | Difficulty identifying overdue requests | Monitor outstanding requests |
| Reporting | Manual management reporting | Improve management visibility |
| Access Control | Risk of inappropriate access to information | Protect student information |
| Search | Difficulty locating request information | Improve efficiency and information access |

## Requirement Quality Check

The requirements have been reviewed to ensure that they are:

- Clear and understandable.
- Relevant to the identified business problem.
- Prioritised according to business importance.
- Traceable to stakeholder needs and business objectives.
- Specific enough to be further developed into acceptance criteria.
- Suitable for validation and testing.

## Requirements Conclusion

The requirements establish the core capabilities and quality expectations needed to address CLI's student support management problem.

The highest-priority requirements focus on consistently capturing requests, assigning responsibility, tracking status, protecting information and maintaining accurate records.

The requirements will be used as the basis for developing acceptance criteria and further analysing the proposed solution.
