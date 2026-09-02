# Acceptance Criteria

## Purpose

Acceptance criteria define the conditions that must be met for a requirement to be considered successfully implemented.

They provide a clear way for stakeholders, developers and testers to determine whether the proposed solution meets the agreed requirements.

The acceptance criteria below are based on the highest-priority functional requirements identified during requirements analysis.

---

## FR-001: Create a Student Support Request

**Requirement:**  
The system must allow an authorised user to create a student support request.

### Acceptance Criteria

- A support request can be created by an authorised user.
- The user must provide all required information before submitting the request.
- The system must prevent submission when mandatory information is missing.
- A successfully submitted request must be stored in the system.
- The system must provide confirmation that the request was successfully created.

---

## FR-002: Generate a Unique Request Reference

**Requirement:**  
The system must generate a unique reference number for each support request.

### Acceptance Criteria

- A reference number must be generated when a new request is successfully created.
- Each request must have a unique reference number.
- The reference number must be stored with the request.
- The reference number must be available to authorised users when viewing the request.
- A reference number must not be assigned to more than one request.

---

## FR-006: Assign a Support Request

**Requirement:**  
The system must allow a support request to be assigned to an appropriate support staff member.

### Acceptance Criteria

- An authorised user must be able to assign a request to a support staff member.
- The selected staff member must be recorded against the request.
- The assigned staff member must be able to identify requests assigned to them.
- A request must display its current assigned staff member.
- The system must prevent unauthorised users from changing request assignments.

---

## FR-009: Update Request Status

**Requirement:**  
The system must allow authorised users to update the status of a support request.

### Acceptance Criteria

- An authorised user must be able to update the status of a request.
- The available status values must be clearly defined.
- The current status must be displayed when viewing a request.
- A status change must be saved successfully.
- Unauthorised users must not be able to change the request status.

---

## FR-010: Display Request Status

**Requirement:**  
The system must display the current status of each support request.

### Acceptance Criteria

- Each request must have a current status.
- The status must be visible to authorised users.
- The displayed status must match the status stored for the request.
- The status must update when an authorised user changes it.
- Users must be able to distinguish between different request statuses.

---

## FR-012: Close a Resolved Request

**Requirement:**  
The system must allow a request to be marked as resolved or closed.

### Acceptance Criteria

- An authorised user must be able to mark a request as resolved.
- A resolved request must display an appropriate closed or resolved status.
- The request must remain available for authorised users to review.
- A closed request must not appear as an outstanding request.
- The system must prevent unauthorised users from closing requests.

---

## FR-013: Assign Request Priority

**Requirement:**  
The system must allow support requests to be assigned a priority level.

### Acceptance Criteria

- An authorised user must be able to assign a priority to a request.
- The available priority levels must be clearly defined.
- The priority must be stored with the request.
- The priority must be visible to authorised support staff.
- Support staff must be able to identify higher-priority requests.

---

## FR-019: Search for Support Requests

**Requirement:**  
The system must allow authorised users to search for support requests using relevant information such as request reference, category or status.

### Acceptance Criteria

- An authorised user must be able to search for requests.
- The user must be able to search using the request reference number.
- The user must be able to search using relevant request information such as category or status.
- Matching requests must be displayed to the user.
- Requests that do not match the search criteria must not be displayed as matching results.

---

## NFR-001: Authorised Access

**Requirement:**  
The system must restrict access to authorised users.

### Acceptance Criteria

- Users must authenticate before accessing restricted system functions.
- Unauthorised users must not be able to access restricted information.
- User access must be controlled according to defined permissions.
- Access attempts must be handled securely.

---

## NFR-003: Protect Student Information

**Requirement:**  
Sensitive student information must be protected from unauthorised access.

### Acceptance Criteria

- Sensitive student information must only be accessible to authorised users.
- Users must not be able to access information outside their permitted role.
- Student information must not be unnecessarily exposed to other users.
- Access permissions must be reviewed and managed appropriately.

---

## Acceptance Criteria Principles

The acceptance criteria should be:

- Clear and specific.
- Relevant to the associated requirement.
- Testable.
- Understandable by both business and technical stakeholders.
- Focused on the expected outcome rather than how the solution will be technically implemented.

## Conclusion

The acceptance criteria provide measurable conditions that can later be used during testing and User Acceptance Testing (UAT).

They also create a connection between the requirements identified during analysis and the testing activities that will be developed later in the project.
