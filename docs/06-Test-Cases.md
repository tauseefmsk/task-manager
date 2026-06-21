# Test Cases

# <Project Name>

## Document Information

| Field | Value |
|---------|---------|
| Project Name | |
| Version | 1.0 |
| Author | |
| Date | |
| Status | Draft |

---

# 1. Test Strategy

## Objective

Validate that all functional requirements and acceptance criteria are implemented correctly.

## Test Types

- Functional Testing
- Validation Testing
- User Acceptance Testing

---

# 2. Test Case Summary

| Test Case ID | Requirement | Test Scenario | Status |
|--------------|-------------|---------------|--------|
| TC-001 | FR-001 | Add Task | Not Started |
| TC-002 | FR-001 | Validate Empty Task | Not Started |
| TC-003 | FR-002 | Edit Task | Not Started |

---

# 3. Test Cases

## TC-001 - Add Task Successfully

### Related Requirement

FR-001

### Related User Story

US-001

### Preconditions

- Application is loaded

### Test Steps

1. Enter task title
2. Click Add button

### Expected Result

- Task is added successfully
- Task appears in task list

### Actual Result

TBD

### Status

Not Executed

---

## TC-002 - Empty Task Validation

### Related Requirement

FR-001

### Related User Story

US-001

### Preconditions

- Application is loaded

### Test Steps

1. Leave task field empty
2. Click Add button

### Expected Result

- Validation message displayed
- Task is not created

### Actual Result

TBD

### Status

Not Executed

---

## TC-003 - Edit Existing Task

### Related Requirement

FR-002

### Related User Story

US-002

### Preconditions

- Existing task available

### Test Steps

1. Click Edit
2. Update task title
3. Save changes

### Expected Result

- Task updated successfully
- Updated value displayed

### Actual Result

TBD

### Status

Not Executed

---

# 4. Traceability Matrix

| Requirement | User Story | Test Cases |
|-------------|------------|------------|
| FR-001 | US-001 | TC-001, TC-002 |
| FR-002 | US-002 | TC-003 |
| FR-003 | US-003 | TC-004 |
| FR-004 | US-004 | TC-005 |

---

# 5. Test Execution Summary

| Test Case | Result |
|------------|---------|
| TC-001 | Pass / Fail |
| TC-002 | Pass / Fail |
| TC-003 | Pass / Fail |

---

# 6. Defects

| Defect ID | Description | Severity | Status |
|------------|-------------|----------|--------|
| BUG-001 | | High | Open |

---

# 7. Version History

| Version | Date | Author | Description |
|----------|----------|----------|----------|
| 1.0 | | | Initial Draft |