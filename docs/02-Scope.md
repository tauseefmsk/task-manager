# Scope Document

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

# 1. Purpose

This document defines the scope of the Task Manager Application project, including features that are included in the current release and features that are explicitly excluded.

The objective is to establish clear project boundaries and prevent scope creep during development.

---

# 2. Project Objectives

The project aims to provide a simple and intuitive task management application that enables users to:

- Create tasks
- Manage existing tasks
- Track task completion status
- Persist task data across browser sessions

---

# 3. In Scope

The following features are included in Version 1.0.

| Scope ID | Feature Name | Priority |
|-----------|-------------|----------|
| SC-001 | Task Creation | High |
| SC-002 | Task Viewing | High |
| SC-003 | Task Editing | High |
| SC-004 | Task Deletion | High |
| SC-005 | Task Completion Tracking | High |
| SC-006 | Local Storage Persistence | High |
| SC-007 | Responsive User Interface | Medium |
| SC-008 | Basic Input Validation | Medium |

---

# 4. Feature Summary

## SC-001 - Task Creation

Allow users to create new tasks within the application.

---

## SC-002 - Task Viewing

Allow users to view all existing tasks.

---

## SC-003 - Task Editing

Allow users to modify existing tasks.

---

## SC-004 - Task Deletion

Allow users to permanently remove tasks.

---

## SC-005 - Task Completion Tracking

Allow users to mark tasks as completed or incomplete.

---

## SC-006 - Local Storage Persistence

Ensure task information remains available after browser refresh or restart.

---

## SC-007 - Responsive User Interface

Provide a user interface that functions correctly on desktop and tablet screen sizes.

---

## SC-008 - Basic Input Validation

Prevent invalid task creation and improve user experience.

---

# 5. Out of Scope

The following features are explicitly excluded from Version 1.0.

| Scope ID | Feature Name |
|-----------|-------------|
| OOS-001 | User Authentication |
| OOS-002 | User Registration |
| OOS-003 | Cloud Data Storage |
| OOS-004 | Multi-User Support |
| OOS-005 | Task Sharing |
| OOS-006 | Email Notifications |
| OOS-007 | Push Notifications |
| OOS-008 | Mobile Application |
| OOS-009 | Task Categories |
| OOS-010 | Task Priorities |
| OOS-011 | Task Due Dates |
| OOS-012 | Search Functionality |
| OOS-013 | File Attachments |
| OOS-014 | Dark Mode |
| OOS-015 | Analytics Dashboard |

---

# 6. Future Releases

## Version 2.0

Potential future enhancements:

| Feature |
|-----------|
| Task Categories |
| Task Priorities |
| Search Tasks |
| Due Dates |
| Task Filtering |

---

## Version 3.0

Potential future enhancements:

| Feature |
|-----------|
| User Authentication |
| Cloud Synchronization |
| Multi-Device Access |
| Notifications |
| Team Collaboration |

---

# 7. Assumptions

- Users have access to a modern web browser.
- Browser Local Storage is available.
- Internet connectivity is not required after application load.
- Application will be used by a single user.

---

# 8. Constraints

- No backend services in Version 1.0.
- No database implementation in Version 1.0.
- No external APIs will be used.
- Data storage is limited to browser Local Storage.

---

# 9. Scope Change Log

| Change ID | Date | Description |
|-----------|----------|-------------|
| SCG-001 | 21-Jun-2026 | Initial Scope Definition |

---

# 10. Version History

| Version | Date | Author | Description |
|----------|----------|----------|----------|
| 1.0 | 21-Jun-2026 | Tauseef Shaikh | Initial Draft |