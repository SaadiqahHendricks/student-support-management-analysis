# As-Is Process

## Purpose

This document describes the current-state process used by Cape Learning Institute (CLI) to receive, record, manage and resolve student support requests.

The process represents a simulated current-state analysis for this fictional case study. It is based on the business problem, stakeholder needs and simulated elicitation findings identified during the requirements analysis.

## Process Scope

### Process Start

The process begins when a student identifies a problem or requires assistance and contacts the Student Support Department.

### Process End

The process ends when the student's request has been resolved and the request is recorded as completed.

## Process Actors

The main actors involved in the current process are:

- Student
- Support Staff
- Support Manager
- Academic / Faculty Staff, where academic assistance is required

## Inputs

The main inputs to the process include:

- Student details
- Student support request
- Request description
- Request category
- Supporting information
- Communication received through email, WhatsApp, telephone or in-person contact

## As-Is Process Flow

```text
START
  ↓
Student identifies a problem
  ↓
Student contacts Student Support
  ↓
Support receives request through email, WhatsApp,
telephone or in-person visit
  ↓
Support staff reviews the request
  ↓
Is sufficient information available?
  ├── NO → Contact student for additional information
  │          ↓
  │       Receive additional information
  │          ↓
  │       Review request again
  │
  └── YES
       ↓
Support staff records request in spreadsheet
       ↓
Request is reviewed and categorised
       ↓
Request is assigned to appropriate staff member
       ↓
Staff member investigates and handles request
       ↓
Is additional assistance required?
  ├── YES → Refer request to appropriate department
  │          ↓
  │       Receive information / assistance
  │          ↓
  │       Continue handling request
  │
  └── NO
       ↓
Staff member responds to student
       ↓
Request is manually updated in spreadsheet
       ↓
Request is considered resolved
       ↓
END
