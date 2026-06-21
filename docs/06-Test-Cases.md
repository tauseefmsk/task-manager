# Test Cases

# Task Manager Application

## Document Information

| Field | Value |
|---------|---------|
| Project Name | Task Manager |
| Version | 1.0 |
| Author | Tauseef Shaikh |
| Date | 21-Jun-2026 |
| Status | Draft |

---

# 1. Test Strategy

## Objective

Validate that all functional requirements and acceptance criteria defined in the PRD are implemented successfully.

## Test Scope

The following features will be tested:

- Task Creation
- Task Viewing
- Task Editing
- Task Deletion
- Task Completion Tracking
- Local Storage Persistence
- Input Validation

---

# 2. Test Case Summary

| TC ID | Requirement | Test Scenario |
|---------|---------|---------|
| TC-001 | FR-001 | Create Task Successfully |
| TC-002 | FR-001 | Create Multiple Tasks |
| TC-003 | FR-008 | Empty Task Validation |
| TC-004 | FR-002 | View Existing Tasks |
| TC-005 | FR-003 | Edit Existing Task |
| TC-006 | FR-004 | Delete Existing Task |
| TC-007 | FR-005 | Mark Task Complete |
| TC-008 | FR-005 | Mark Task Incomplete |
| TC-009 | FR-006 | Verify Data After Refresh |
| TC-010 | FR-006 | Verify Data After Browser Restart |
| TC-011 | FR-007 | Verify Desktop Layout |
| TC-012 | FR-007 | Verify Tablet Layout |

---

# 3. Test Cases

## TC-001 Create Task Successfully

### Related Requirement

FR-001

### Related User Story

US-001

### Related Acceptance Criteria

AC-001, AC-002, AC-003, AC-004

### Preconditions

- Application is loaded

### Test Steps

1. Enter task title
2. Click Add Task

### Expected Result

- Task is created successfully
- Task appears in task list

---

## TC-002 Create Multiple Tasks

### Related Requirement

FR-001

### Test Steps

1. Create Task A
2. Create Task B
3. Create Task C

### Expected Result

- All tasks are displayed
- Tasks maintain creation order

---

## TC-003 Empty Task Validation

### Related Requirement

FR-008

### Related Acceptance Criteria

AC-023, AC-024, AC-025

### Test Steps

1. Leave task title empty
2. Click Add Task

### Expected Result

- Validation message displayed
- Task is not created

---

## TC-004 View Existing Tasks

### Related Requirement

FR-002

### Related Acceptance Criteria

AC-005, AC-006, AC-007

### Test Steps

1. Open application with existing tasks

### Expected Result

- All tasks are displayed
- Task information is visible

---

## TC-005 Edit Existing Task

### Related Requirement

FR-003

### Related Acceptance Criteria

AC-008, AC-009, AC-010

### Test Steps

1. Select Edit
2. Modify task title
3. Save changes

### Expected Result

- Updated task information displayed
- Changes saved successfully

---

## TC-006 Delete Existing Task

### Related Requirement

FR-004

### Related Acceptance Criteria

AC-011, AC-012, AC-013

### Test Steps

1. Select Delete
2. Confirm deletion

### Expected Result

- Task removed from list
- Task no longer exists

---

## TC-007 Mark Task Complete

### Related Requirement

FR-005

### Related Acceptance Criteria

AC-014, AC-015, AC-016

### Test Steps

1. Select incomplete task
2. Mark task complete

### Expected Result

- Task displays completed state
- Status saved successfully

---

## TC-008 Mark Task Incomplete

### Related Requirement

FR-005

### Test Steps

1. Select completed task
2. Mark task incomplete

### Expected Result

- Task returns to pending state

---

## TC-009 Verify Data After Refresh

### Related Requirement

FR-006

### Related Acceptance Criteria

AC-017

### Test Steps

1. Create task
2. Refresh browser

### Expected Result

- Task remains visible

---

## TC-010 Verify Data After Browser Restart

### Related Requirement

FR-006

### Related Acceptance Criteria

AC-018, AC-019

### Test Steps

1. Create task
2. Close browser
3. Reopen application

### Expected Result

- Task data loads successfully

---

## TC-011 Verify Desktop Layout

### Related Requirement

FR-007

### Related Acceptance Criteria

AC-020

### Test Steps

1. Open application on desktop

### Expected Result

- Layout renders correctly
- No overlapping elements

---

## TC-012 Verify Tablet Layout

### Related Requirement

FR-007

### Related Acceptance Criteria

AC-021, AC-022

### Test Steps

1. Open application on tablet viewport

### Expected Result

- Layout adapts correctly
- Controls remain usable

---

# 4. Requirements Traceability Matrix (RTM)

| Requirement | User Story | Acceptance Criteria | Test Cases |
|-------------|------------|--------------------|------------|
| FR-001 | US-001 | AC-001, AC-002, AC-003, AC-004 | TC-001, TC-002 |
| FR-002 | US-002 | AC-005, AC-006, AC-007 | TC-004 |
| FR-003 | US-003 | AC-008, AC-009, AC-010 | TC-005 |
| FR-004 | US-004 | AC-011, AC-012, AC-013 | TC-006 |
| FR-005 | US-005 | AC-014, AC-015, AC-016 | TC-007, TC-008 |
| FR-006 | US-006 | AC-017, AC-018, AC-019 | TC-009, TC-010 |
| FR-007 | N/A | AC-020, AC-021, AC-022 | TC-011, TC-012 |
| FR-008 | N/A | AC-023, AC-024, AC-025 | TC-003 |

---

# 5. Test Execution Results

| TC ID | Status | Comments |
|---------|---------|---------|
| TC-001 | Not Executed | |
| TC-002 | Not Executed | |
| TC-003 | Not Executed | |
| TC-004 | Not Executed | |
| TC-005 | Not Executed | |
| TC-006 | Not Executed | |
| TC-007 | Not Executed | |
| TC-008 | Not Executed | |
| TC-009 | Not Executed | |
| TC-010 | Not Executed | |
| TC-011 | Not Executed | |
| TC-012 | Not Executed | |

---

# 6. Defect Log

| Bug ID | Description | Severity | Status |
|---------|---------|---------|---------|
| BUG-001 | | | |

---

# 7. Version History

| Version | Date | Author | Description |
|---------|---------|---------|---------|
| 1.0 | 21-Jun-2026 | Tauseef Shaikh | Initial Draft |